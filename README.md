# ByPassBehinder4.1
魔改冰蝎4.1
# ByPassBehinder4.1 / 冰蝎WebShell魔改二开

## Code By:gaoxiaobai

##### 

##### :x:风险概述:

本工具仅限授权安全测试使用,禁止非法攻击未授权站点

##### :ballot_box_with_check:使用教程

Behinder（冰蝎）是一款流行的WebShell管理工具，但由于其流量特征明显，容易被安全设备（如WAF、IDS、EDR）检测拦截。本项目对Behinder进行二次开发，主要目标：

- **去除强特征**（如固定请求头、密钥交换方式、默认加密算法）。
- **新增10种加密算法**，逃避安全设备检测。
- **自带PHP/ASPX免杀WebShell**，绕过常见杀软（如360、火绒、Defender）。

只需要本地安装JDK8及以上环境即可

命令行输入:java -jar ByPassBehinder4.1.jar 

![image-20250725154850534](C:\Users\22019\AppData\Roaming\Typora\typora-user-images\image-20250725154850534.png)

二开内容包括：

1、去除原版强特征

2、新加入10种加密算法，自带算法php和aspx默认过火绒、360、df、沙箱。jsp的建议使用网上其他免杀后使用。

![image-20250725155205154](C:\Users\22019\AppData\Roaming\Typora\typora-user-images\image-20250725155205154.png)



点击生成服务器后，会在本地生成jsp、php、aspx木马

![image-20250725155841120](C:\Users\22019\AppData\Roaming\Typora\typora-user-images\image-20250725155841120.png)

![image-20250725155440782](C:\Users\22019\AppData\Roaming\Typora\typora-user-images\image-20250725155440782.png)

连接时选择对应的加密算法即可成功连接

![image-20250725155638222](C:\Users\22019\AppData\Roaming\Typora\typora-user-images\image-20250725155638222.png)

![image-20250725155804722](C:\Users\22019\AppData\Roaming\Typora\typora-user-images\image-20250725155804722.png)

自写加密算法流量特征

![image-20250725161120676](C:\Users\22019\AppData\Roaming\Typora\typora-user-images\image-20250725161120676.png)

##### :trident:免杀测试

(数据更新至2025.07.25 16:00)

**免杀**冰蝎rebeyond的php和aspx WebShell免杀效率如下:

![image-20250725160024380](C:\Users\22019\AppData\Roaming\Typora\typora-user-images\image-20250725160024380.png)
**注：注意尊重原版开发人员知识产权，开源不易，原版地址https://github.com/rebeyond/Behinder**

**注：注意尊重原版开发人员知识产权，开源不易，原版地址https://github.com/rebeyond/Behinder**

**注：注意尊重原版开发人员知识产权，开源不易，原版地址https://github.com/rebeyond/Behinder**


##### :part_alternation_mark:持续性开发

其他语言免杀WebShell正在随缘开发中
