### void 

1. void类型的值可以是null或undefined

2. void通常可以作为函数的返回值类型

   ```ts
   function test(params): string|void{
     if(params){
       return 'romy'
     }
   }
   ```

   > p.s null和undefined也是单独的基本类型，可以单独定义

### never

1. never的返回值是什么都没有，比如抛出异常的时候，也就是函数并没有执行完毕没有返回值

   ```ts
   function test(): never{
     throw new Error('错误')
   }
   ```

   