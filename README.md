# NAT-Type
![Eclipse Marketplace](https://img.shields.io/badge/license-CPL--V3-green)
##关于延迟的说明
本次检测节点是国内可以访问的stun节点，但是由于报文过长，反馈结果会有一定的延迟。
如果想立即出现结果，请使`test2.js`文件进行测试。
### 说明
用来测试您的NAT网络类型。
### 使用方法
> 1.打开**Google**的**Chrome**浏览器
> 
> 2.打开开发人员工具`F12`
> 
> 3.打开控制台
> 
> 4.复制`test.js`文件内容
> 
> 5.按下`Enter`
> 
### 结果查看
浏览器运行后会输出结果。
> `normal nat`: 表示为普通NAT（非对称NAT）
>
> `symmetric nat`：表示对称型NAT
### 引用详情
> https://webrtchacks.com/symmetric-nat/
>
> https://jsfiddle.net/5ftsd5c2/17/
>
> https://github.com/fippo/sdp
