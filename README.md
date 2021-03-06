# 水滴钱包

> 一个可批量操作账户的以太坊系列钱包，
> 支持 MAC 和 Windows 双系统

> An electron-vue project

#### Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9080
npm run dev

# build electron application for production
npm run build


```

---

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue) using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).

---

## 功能

### key密码
    key密码是用于账户批量加解密的密码，所以要牢记哦！！
   ![key密码][1]

### 添加账户
    进入内部后，可以选择添加账户或导入账户，导入账户需要填写账户的秘钥，添加账户可以随意选择要添加的个数，例如添加20个新账户
   ![添加账户][2]
   ![导入账户][3]

### 导出账户
    导出账户有两种导出方式，一种是keyStores方式，一种是privateKey，privateKey导出后，是json格式
   ![导出账户][5]

### 删除账户
    可以对账户进行操作，例如删除或者交易
   ![删除账户][4]

### 账户交易
    账户交易分三种，一对一，一对多，多对一转账

#### 一对一转账
    一对一转账可以单独对某个账户转账，填入接受账户，转账金额即可。
   ![一对一转账][6]

#### 一对多转账
    一对多转账可以批量对多个账户转账，选择接收账户，填入转账金额即可。注意：一对多转账因为技术问题，会很慢，需要上一笔转账完成才能执行下一笔，所以如果接收账户多的话，需要等一段时间在去查询余额
   ![一对多转账][7]

#### 多对一转账
    多对一转账可以批量让多个账户对一个账户转账，在要接收的账户中操作，选择发送账户，填入转账金额即可。
   ![一对多转账][7]

---
钱包交流群：109346212

[1]: https://raw.githubusercontent.com/chengle123/waterDropWallet/master/img/1.png
[2]: https://raw.githubusercontent.com/chengle123/waterDropWallet/master/img/2.png
[3]: https://raw.githubusercontent.com/chengle123/waterDropWallet/master/img/3.png
[4]: https://raw.githubusercontent.com/chengle123/waterDropWallet/master/img/4.png
[5]: https://raw.githubusercontent.com/chengle123/waterDropWallet/master/img/5.png
[6]: https://raw.githubusercontent.com/chengle123/waterDropWallet/master/img/6.png
[7]: https://raw.githubusercontent.com/chengle123/waterDropWallet/master/img/7.png
[8]: https://raw.githubusercontent.com/chengle123/waterDropWallet/master/img/8.png
