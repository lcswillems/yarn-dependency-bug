# Yarn dependency bug

`package-a` has `string` as dependency. `package-b` has no dependency. However, `package-b` is able to use `string` package. Execute:

```
node package-b/index.js
```

It logs:
```
false
true
```
