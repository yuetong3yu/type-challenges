## If <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>

## Answer

```ts
type If<T extends boolean, C, F> = T extends true ? C : F;
```