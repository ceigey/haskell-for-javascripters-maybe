# Partial application
_JavaScript_
```javascript
let curryable = a => b => c => a + b + c
```

_Haskell_
```haskell
normalFunction :: a -> a -> a -> a
normalFunction a b c = a + b + c
```

# Application
```javascript
curryable(a)(b)(c)
```

```haskell
normalFunction $ a b c
-- or
normalFunction (a b c) -- doublecheck this
```
