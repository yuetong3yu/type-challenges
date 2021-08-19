## Tuple to Object <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>

## Answer

```ts
type TupleToObject<T extends readonly string[]> = {
  [P in T[number]]: P;
};
```
