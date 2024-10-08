
# bzip2 命令讲解 刘家希



- **与前面2种压缩方式的区别**

| 命令 |   特点   |
| ---- | ---- |
|   zip   |   用于压缩多个文件，支持目录递归和加密   |
|   gzip   |   适用于单文件压缩，速度快，压缩比较低   |
|   **bzip2**   |   **适用于单文件压缩，压缩比高，速度较慢**   |

- **该压缩方式的特点**

压缩效率高，解压缩速度快，适用于压缩大文件

- **命令基本语法**

```
bzip2 <input_file>

bzip2 -d <input_file.bz2>
```

- **常用参数**

| 选项命令 | 作用 |
| ---- | ---- |
|-c|显示处理结果|
|-t|测试压缩包的完整性|
|-d| 执行解压缩操作|
|-v|显示执行过程详细信息|
|-f|强制覆盖已有文件而不询问|
|-z|执行压缩操作|
|-k|保留已有文件|
|-q|跳过所有警告信息|
|-s|降低内存使用量|
|--help|显示帮助信息|
|--version|显示版本信息|
                         
> https://www.linuxcool.com/bzip2

![image](https://github.com/user-attachments/assets/2ea690b9-d278-47b3-9835-e5093eb87d72)

