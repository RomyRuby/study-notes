type可以声明类型的别名

还可以定义多个类型

```ts
type IsAdmin = boolean
type Sex = 'boy' | 'girl'

type User = {
  name: string
  age: number
  isAdmin: IsAdmin
  sex: Sex
  show(): string
  [key: string]: any
}
```



Interface 同名定义会隐式合并

type不可以同名定义



type的组合：

```ts
type Name = {
	name: string
}

type Age = {
	age: number
}

interface Address {
  adress: string
}

type User = Name | Age
type User2 = Name & Age
type User3 = Name & Address //type可以和接口组合

```

