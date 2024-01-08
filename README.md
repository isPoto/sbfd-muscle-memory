# 声笔飞单部首肌肉记忆训练 - 1.0.0

程序集成了著名的 [SuperMemo](https://supermemo.guru/wiki/SuperMemo) 记忆算法，能够有效的帮助用户快速且牢固的记忆声笔飞系的部首所在按键。

## 快速入门

1. 按空格开始训练
2. 看到卡牌中显示的部首后，按下对应的按键
3. 持续进行训练，直到达到满意的速度

## 程序介绍

在（重新）开始训练时程序会将一个个的部首和对应的按键制作成一张张的卡牌，顺序是随机的。卡牌的正面是部首，背面是你需要输入的对应按键。在卡牌显示后，你要以最快的速度按下键盘上相应的按键。如果按键正确，则会自动显示下一张卡牌，且程序会根据你的响应时间来为你的记忆评级。

- 如果在 200ms 以内（5击以上），则认为是非常好的成绩，即 5 级
- 如果在 300ms 以内，则认为是不错的成绩，即 4 级
- 3 级 500ms 内
- 2 级 1s 内
- 超过 1s 只要输入正确，就是 1 级
- 输入错误为 0 级，按键错误时会显示该部首对应的按键，你需要按下该按键才能继续训练。

程序会根据这个评级来安排该卡牌下次出现的时间，以便巩固你的记忆。

程序会在退出（关闭页面、刷新页面、关闭浏览器等）时自动将当前进度记录到浏览器的本地存储当中；当下载再次打开时，会自动尝试从本地存储中加载进度。**这个存储是存储在本地的，所以换了浏览器之后就需要重来了**


## 版本历史

### 1.0.0

初始版本


## 依赖项目

- [SM-15](https://github.com/slaypni/SM-15)
- [Element Plus](https://element-plus.gitee.io)
- [Fontello](https://fontello.com)