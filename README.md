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


## 用户配置

用户配置不需要打包到镜像中。
将配置放到`~/.config/envd/config.envd`路径，envd 会自动的加载和启用。
[配置文件](./config.envd)