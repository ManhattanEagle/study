### \#\#\# Python虚拟环境介绍与安装：

**1、**因为python的框架更新迭代太快了，有时候需要在电脑上存在一个框架的多个版本，这时候虚拟环境就可以解决这个问题。

**2、**通过以下命令安装虚拟环境：pip install virtualenv

![](/assets/import.png)

![](/assets/version.png)

**3、**开辟新的虚拟环境：virtualenv \[virtualenv-name\]

```
                                    virtualenv flask-env
```

![](/assets/flask-env.png)

**4、**激活虚拟环境：

```
    ※【Windows】：直接进入到虚拟环境的目录，然后执行activate
        C:\Users\wangxu5\flask-env\Scripts>activate
        如下图，输入activate命令后，显示了虚拟环境(flask-env)，证明已经进入该虚拟环境
    ※退出虚拟环境：deactivate
```

### ![](/assets/activate.png)

### 

### \#\#\# pip安装flask：

**1、**在创建的虚拟环境中安装flask

```
        ※进入虚拟环境，并激活：C:\Users\wangxu5\flask-env\Scripts>activate

        ※安装flask：(flask-env) C:\Users\wangxu5\flask-env\Scripts>pip install flask
```

![](/assets/flask.png)

