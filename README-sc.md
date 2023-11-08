* redis版本: 6.2.6

```shell
# 安装pip
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py

# 安装compiledb
/Users/xiaozhou.tu/Library/Python/2.7/bin/pip install compiledb

# 编译构建
cd sc-redis
/Users/xiaozhou.tu/Library/Python/2.7/bin/compiledb make noopt

./src/redis-server --version
```

https://juejin.cn/post/6847902217316499470
https://juejin.cn/post/7200376545243643962
