### 介绍： 
用[影刀RPA](https://www.yingdao.com/product)低代码开发平台搭建的轮子，检测API链接返回的信息，使飞书文档每天尽可能保持更新，根据哔哩哔哩数字收藏周边的[动态页面](https://space.bilibili.com/1425239276/dynamic)每天更新的内容，争取每天手动运行一次RPA应用。<br>
会手动从飞书在线表格导出Excel文件备份到[Google Drive个人版](https://docs.google.com/spreadsheets/d/1QUEB8C-XdE730gA903xpqncibuOsHwfm)和OneDrive国际个人版，每过半个月，即两周左右备份一次；GitHub不会进行发版，只备份CSV版本的文件到仓库里。<br>
使用方法请看在线文档中最后一张[Sheet表](https://wvu1yssu8zz.feishu.cn/sheets/ZyXwsKaC6hTlRjtdJ8LcTPion7c?sheet=NuUsPA)的内容，查找某个指定收藏集请善用查找`Ctrl+F`组合键的功能，包括不仅限与搜索收藏集标题的关键字，或者用act_id直接查找。
### 项目诞生的原因：
因有部分收藏集，奖池或者奖励有时限，甚至卡面有数量限制；达到条件后只有获取过的用户可以查看到，未登录或者未获取的用户无法查看，甚至从正常接口都拉取不到。<br><br> 
![Image](https://github.com/user-attachments/assets/84fc2c8f-59a8-4a36-9f13-f31062ac8bab)  
![Image](https://github.com/user-attachments/assets/686fef55-30d6-4287-ac53-d7f3f987c995)<br><br>
好在通过官方另外的接口请求可获得相关信息，若要与其他类目一同批量下载使用建议使用[Collection-Down](https://github.com/heartalborada-del/Collection-Down)更佳，当前该项目可能尚未支持，已向该项目提出[改进意见](https://github.com/heartalborada-del/Collection-Down/issues/2)，请静候佳音。
### 待实现的功能与需求：
- 购买专门运行的低功耗小型设备
- 新注册一个专门运行的影刀RPA账号
- 每天自动运行，无需手动触发
- 申请OneDrive中国版账号，使备份文件在中国大陆正常访问
- 自动导出Excel文件并向网盘备份
### 鸣谢：
- [bilibili-API-Collect](https://github.com/SocialSisterYi/bilibili-API-collect)
- [Collection-Down](https://github.com/heartalborada-del/Collection-Down)
