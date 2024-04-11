### 需要注意⚠️

1. 默认情况下，null与undefined可以作为其他类型的值进行赋值

2. 如果不允许，需要在tsconfig中进行设置

   ```
   "strictNullChecks":true
   ```

3. 然后重新运行tsc -w，就可以禁止使用了

