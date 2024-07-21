# 暑期机器学习零基础特训第二期——实战篇——**Datawhale AI 夏令营**
## 我们的公众号对应粉丝交流群为：912860177

## 电力需求预测挑战赛（讯飞开放平台）

[电力需求预测挑战赛（讯飞开放平台）链接](https://challenge.xfyun.cn/topic/info?type=electricity-demand&ch=dw24_uGS8Gs)

- 第一期(Baseline1_code)对应推文地址：https://mp.weixin.qq.com/s/nV7BSSXVxg5GmvC3DSDPFQ
- 第二期(Baseline2_code)对应推文地址：https://mp.weixin.qq.com/s/kKXF6wimA-qN_Crq4JQJWQ
- 第三期(Baseline3_code)对应推文地址：https://mp.weixin.qq.com/s/o2AdE25k0ae0_QRCLg8BbA
### 赛事概要
一、赛题背景\
随着全球经济的快速发展和城市化进程的加速，电力系统面临着越来越大的挑战。电力需求的准确预测对于电网的稳定运行、能源的有效管理以及可再生能源的整合至关重要。
![图片1：背景](https://files.mdnice.com/user/47241/f48a59df-12d5-47a3-8863-4e8330fce111.png)

  然而，电力需求受到多种因素的影响，为了提高电力需求预测的准确性和可靠性，推动智能电网和可持续能源系统的发展，本场以“电力需求预测”为赛题的数据算法挑战赛。选手需要根据历史数据构建有效的模型，能够准确的预测未来电力需求。

二、赛题任务

给定多个房屋对应电力消耗历史N天的相关序列数据等信息，预测房屋对应电力的消耗。

三、评审规则

1.数据说明

赛题数据由训练集和测试集组成，为了保证比赛的公平性，将每日日期进行脱敏，用1-N进行标识，即1为数据集最近一天，其中1-10为测试集数据。

数据集由字段id（房屋id）、 dt（日标识）、type（房屋类型）、target（实际电力消耗）组成。

| 特征字段 |        字段描述        |
| :------: | :--------------------: |
|    id    |         房屋id         |
|    dt    |         日标识         |
|   type   |        房屋类型        |
|  target  | 实际电力消耗，预测目标 |


2.评审规则

预测结果以 mean square error 作为评判标准，具体公式如下：
$$\frac{1}{n}\sum_{n=1}^n(y_i-\bar{y_i})^2$$
其中，$y_i$是真实电力消耗，$\bar{y_i}$是预测电力消耗。

3.测试集数据具体展示：

![data_train_csv文件展示](https://files.mdnice.com/user/47241/ac3e12b2-5ea3-443a-af90-da44e623e167.png)

4.目前得分-排名
      233-60
![1721461837527](https://github.com/user-attachments/assets/09b020f3-b9b4-41d1-904e-e7a689fb276e)


5.注意

- 代码已经系统性整理好在仓库中并且加入基础知识辅助学习
- 允许在非盈利非商业的情况下学习使用，感谢。
## 我们的公众号对应粉丝交流群为：912860177

![image2](https://github.com/user-attachments/assets/08688af2-5c75-4e7b-b545-dcf224fac45e)

- 群里有丰富的资料和各界大神，期待您的加入！
