## Readonly <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>

## Answer

```ts
type MyReadonly<T> = {
  readonly [K in keyof T]: T[K];
};
```
