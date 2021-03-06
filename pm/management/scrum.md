## 什么是Scrum？
Scrum的英文意思是橄榄球运动的一个专业术语，表示“争球”的动作；把一个开发流程的名字取名为Scrum，我想你一定能想象出你的开发团队在开发一个项目时，大家像打橄榄球一样迅速、富有战斗激情、人人你争我抢地完成它，你一定会感到非常兴奋的。

而Scrum就是这样的一个开发流程，运用该流程，你就能看到你团队高效的工作。

## Scrum开发流程中的三大角色
1. `产品负责人（Product Owner）`:主要负责确定产品的功能和达到要求的标准，指定软件的发布日期和交付的内容，同时有权力接受或拒绝开发团队的工作成果。
1. `流程管理员（Scrum Master）`:主要负责整个Scrum流程在项目中的顺利实施和进行，以及清除挡在客户和开发工作之间的沟通障碍，使得客户可以直接驱动开发。
1. `开发团队（Scrum Team）`:主要负责软件产品在Scrum规定流程下进行开发工作，人数控制在5~10人左右，每个成员可能负责不同的技术方面，但要求每成员必须要有很强的自我管理能力，同时具有一定的表达能力；成员可以采用任何工作方式，只要能达到Sprint的目标。

## Scrum流程图
![scrummodel](ScrumModel.jpg)

## 什么是Sprint？
Sprint是短距离赛跑的意思，这里面指的是一次迭代，而一次迭代的周期是1个月时间（即4个星期），也就是我们要把一次迭代的开发内容以最快的速度完成它，这个过程我们称它为Sprint。

## 如何进行Scrum开发？
1. 我们首先需要确定一个Product Backlog（按优先顺序排列的一个产品需求列表），这个是由Product Owner 负责的；
1. Scrum Team根据Product Backlog列表，做工作量的预估和安排；
1. 有了Product Backlog列表，我们需要通过 Sprint Planning Meeting（Sprint计划会议） 来从中挑选出一个Story作为本次迭代完成的目标，这个目标的时间周期是1~4个星期，然后把这个Story进行细化，形成一个Sprint Backlog；
1. Sprint Backlog是由Scrum Team去完成的，每个成员根据Sprint Backlog再细化成更小的任务（细到每个任务的工作量在2天内能完成）；
1. 在Scrum Team完成计划会议上选出的Sprint Backlog过程中，需要进行 Daily Scrum Meeting（每日站立会议），每次会议控制在15分钟左右，每个人都必须发言，并且要向所有成员当面汇报你昨天完成了什么，并且向所有成员承诺你今天要完成什么，同时遇到不能解决的问题也可以提出，每个人回答完成后，要走到黑板前更新自己的 Sprint burn down（Sprint燃尽图）；
1. 做到每日集成，也就是每天都要有一个可以成功编译、并且可以演示的版本；
1. 当一个Story完成，也就是Sprint Backlog被完成，也就表示一次Sprint完成，这时，我们要进行 Srpint Review Meeting（演示会议），也称为评审会议，产品负责人和客户都要参加（最好本公司老板也参加），每一个Scrum Team的成员都要向他们演示自己完成的软件产品（这个会议非常重要，一定不能取消）；
1. 最后就是 Sprint Retrospective Meeting（回顾会议），也称为总结会议，以轮流发言方式进行，每个人都要发言，总结并讨论改进的地方，放入下一轮Sprint的产品需求中；

## Scrum开发流程中的一些场景图
Product Backlog:

![backlog](backlog.png)

每日站会：

![meeting](meeting.png)

任务看版包含 未完成、正在做、已完成 的工作状态，假设你今天把一个未完成的工作已经完成，那么你要把小卡片从未完成区域贴到已完成区域。

![board](board.png)

每个人的工作进度和完成情况都是公开的，如果有一个人的工作任务在某一个位置放了好几天，大家都能发现他的工作进度出现了什么问题（成员人数最好是5~7个，这样每人可以使用一种专用颜色的标签纸，一眼就可以从任务版看出谁的工作进度快，谁的工作进度慢）

![board2](board2.png)

计划纸牌，它的作用是防止项目在开发过程中，被某些人所领导。怎么用的呢？比如A程序员开发一个功能，需要5个小时，B程序员认为只需要半小时，那他们各自取相应的牌，藏在手中，最后摊牌，如果时间差距很大，那么A和B就可以讨论A为什么要5个小时...

![card](card.png)

## 参考资料
1. [Scrum (software development)](https://en.wikipedia.org/wiki/Scrum_(software_development))
1. [硝烟中的Scrum和XP](http://www.infoq.com/cn/minibooks/scrum-xp-from-the-trenches)
