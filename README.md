 ```
 _   _                  _                   _            _          _       
 | | | |___  ___ _ __   | |_   _ _ __  _   _| |_ ___ _ __| |    __ _| |__    
 | | | / __|/ _ \ '__|  | | | | | '_ \| | | | __/ _ \ '__| |   / _` | '_ \  
 | |_| \__ \  __/ | | |_| | |_| | |_) | |_| | ||  __/ |  | |__| (_| | |_) | 
  \___/|___/\___|_|  \___/ \__,_| .__/ \__, |\__\___|_|  |_____\__,_|_.__/  
                                |_|    |___/                UserJupyterLab  
```

# UserJupyterLab

JupyterLab 项目

## 签到项目

使用方法:

1. 添加文件`签到.yaml`
2. 在文件中添加签到配置项目(大部分都支持多账户[ **理论上, 实际上就没测试过** ])
    ```yaml
    # 天翼云盘
    cloud189:
        config:
            - username: '@189.cn'
              password: ''
    # 网易云音乐
    music:
        config:
            -  username: ''
               password: ''

    # 贴吧
    tieba:
      config:
         - cookie: ""
    ```
3. 然后运行OJBK!
