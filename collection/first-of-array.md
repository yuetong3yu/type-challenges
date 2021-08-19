## First of Array <img src="https://img.shields.io/badge/-easy-7aad0c" alt="warm-up"/>

## Answer

```ts
type FirstofArray<T extends any[]> = T extends [] ? never : T[0];
```
