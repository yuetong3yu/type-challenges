## Awaited <img src="https://img.shields.io/badge/-easy-7aad0c" alt="warm-up"/>

## Solution

```ts
type Awaited<T> = T extends Promise<infer K> ? K : never;
```
