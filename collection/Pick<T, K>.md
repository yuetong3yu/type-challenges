## Pick<T, K>

实现一个 Pick。
`K extends keyof T`, keyof T 首先会生成一个 T 对象的 key 的联合类型，然后给到 K。
返回值就比较简单了，在 T 中取到对应的 type 即。

## Answer

```ts
type MyPick<T, K extends keyof T> = {
  [k in K]: T[k];
};
```
