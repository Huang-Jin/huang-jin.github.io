## Homepage of Huang Jin


# Linux Memo
## Command
### ls 列出当前文件夹内所有文件(夹),不包括.开头和隐藏的  
```markdown
-a 列出所有,包括.开头和隐藏的文件  
-l 列出所有文件(夹)以及他们的信息  
```
### find 查找文件  
```markdown
-name 参数 查找这个文件，支持模糊查找,不指明路径即为当前路径下  
```
### put 用于psftp上传数据,支持模糊匹配
```markdown
-r 递归上传,一般用于上传文件夹
```


## Library
```markdown
  Python --> 库路径设置 --> PYTHONPATH  
  C/C++  --> 库路径设置 --> LIBRARY_PATH/LD_LIBRARY_PATH  
         --> 文件头路径设置 --> C_INCLUDE_PATH/CPLUS_INCLUDE_PATH  
  CMake  --> 指定安装目录 --> -DCMAKE_INSTALL_PREFIX  
```

## 创建用户
```markdown
一般这样既可: sudo useradd -m -s /bin/bash -c 备注 用户名  
             -m 自动创建用户主目录  
             -s 设置shell  
             -c 备注  
```
 
# Android Memo
## Activity  
```markdown
1. 对于基本的空Activity,如果需要去除标题栏,则将theme属性修改为以下内容`android:theme="@style/Theme.AppCompat.Light.NoActionBar`  
```
