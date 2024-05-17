# ct8 - 控制面板自动登录脚本
## 使用方法
　　在 GitHub 仓库中，进入右上角`Settings`，在侧边栏找到`Secrets and variables`，点击展开选择`Actions`，点击`New repository secret`，然后创建一个名为`ACCOUNTS_JSON`的`Secret`，将 JSON 格式的账号密码字符串作为它的值。
  
~~Serv00格式如下(不适合CT8)：~~
```
[  
  { "username": "qinshihuang", "password": "linux.do", "panelnum": "0" },  
  { "username": "zhaogao", "password": "daqinzhonggong", "panelnum": "2" },  
  { "username": "heiheihei", "password": "shaibopengke", "panelnum": "3" }  
]
```
> 其中`panelnum`参数为面板编号，即为你所收到注册邮件的`panel*.ct8.com`中的`*`数值。上边是套用的Serv00的参数，因ct8无panelnum,所以留空。

CT8格式如下（CT8请用此示例）：  
```
[  
  { "username": "qinshihuang", "password": "linux.do", "panelnum": "" },  
  { "username": "zhaogao", "password": "daqinzhonggong", "panelnum": "" },  
  { "username": "heiheihei", "password": "shaibopengke", "panelnum": "" }  
]
```

## 贡献
|姓名|主页|内容|
| :------------: | :------------: | :------------: |
|linzjian666|https://github.com/linzjian666|增加多面板支持|

## 参考信息
|  名称 |来源|地址|
| :------------: | :------------: | :------------: |
|Limkon|Github|https://github.com/Limkon|
