## 操作场景
该指南指导您如何在堡垒机系统添加 Linux 资源账号。添加资源账号后，运维用户可通过该资源账号登录资源。




## 操作步骤
1. 登录腾讯云 [堡垒机控制台](https://console.cloud.tencent.com/cds/dasb)，并使用管理员账号登录堡垒机。
2. 单击【资源管理】>【Linux】，进入管理页面。
3. 找到您要配置账号的资源，在其所在行中，单击<img src="https://main.qcloudimg.com/raw/6ce56e0ba623b3c88ac789505dd16234.png"  style="margin:0;">，即可进入资源账号配置页面。
![1](https://main.qcloudimg.com/raw/b04669730acd62048622192f6211c8d3.png)
4. 单击【新建】，进入创建账号页面，请配置如下信息：
 - **账号**：填写 Linux 资源的管理员账号。
 - **口令**：填写管理员密码。
 - **确认口令**：填写管理员密码。
 - **管理状态**：全接管、半接管和不接管。修改账号信息完成并需要推送至 Linux 资源时，需要将管理状态配置为全接管或半接管。
 - **鉴别状态**：岗位授权相关，默认为已鉴别，若更改为未鉴别，则岗位授权策略会自动清除该账号授权。
 - **是否拨测**：修改账号口令相关。在进行账号修改前，进行拨测。
 - **访问方式**：访问 Linux 资源的访问方式，可多选。
![1](https://main.qcloudimg.com/raw/23fd8d4ff66938091dddb0c4829aa4f0.png)
5. 确认配置信息无误后，单击【保存】，即可完成帐号的添加。
