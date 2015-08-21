# centos_mem_release


centos为了提高效率，把部分使用过的文件缓存到了内存里。

如果是这样的话，我又不需要这样的文件性能，那就可以释放。如下两个命令就可以：

```
sync
echo 3 > /proc/sys/vm/drop_caches
```

## Install

    npm install -g cmr

## Usage

    cmr
    
or

    cmfree