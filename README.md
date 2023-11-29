# envdlib 

usage:

```envd
lib = include('https://github.com/gfhe/envdlib')

def build():
  lib.base_cuda12()
```

> 注意：导入的lib 可以直接使用 lib 代码库 envd 文件中函数和属性。
> 例如:
> ✅：`lib.base_cuda12()`
> ❌：`lib.cuda.base_cuda12()`