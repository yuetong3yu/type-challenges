## Length of Tuple <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>

## Answer

```ts
type Length<T extends readonly string[]> = T["length"];
```
