|  |  |
| :--- | :--- |
|  |  |

# IPython的帮助和文档

符号?用于浏览文档，符号??用于浏览源代码，Tab键可以用于自动补全。

IPython提供了用\*符号来实现通配符匹配的方法。

# IPython shell中的快捷键

快捷键分为：导航、文本输入、历史命令和其他

## 导航

| 快捷键 | 动作 |
| :--- | :--- |
| Ctlr + a | 将光标移到本行的开始处 |
| Ctrl + e | 将光标移到本行的结尾处 |
| Ctrl + b \(或左键箭头键） | 将光标回退一个字符 |
| Ctrl + f（或右键箭头键） | 将光标前进一个字符 |

## 文本

| 快捷键 | 动作 |
| :--- | :--- |
| Backspace键 | 删除前一个字符 |
| Ctrl + d | 删除后一个字符（结合Ctrl+b删除前一个字符） |
| Ctrl + k | 从光标开始剪切至行的末尾 |
| Ctrl + u | 从行的开始剪切至光标 |
| Ctrl + y | yank（即粘贴）之前剪切的文本 |
| Ctrl + t | transport（即交换）前两个字符 |

## 历史命令

| 快捷键 | 动作 |
| :--- | :--- |
| Ctrl + p（或向上箭头） | 获取前一个历史命令 |
| Ctrl + n（或向下箭头） | 获取后一个历史命令 |
| Ctrl + r | 对历史命令的方向搜索 |

## 其他

| 快捷键 | 动作 |
| :--- | :--- |
| Ctrl + l | 清除终端屏幕的内容 |
| Ctrl + c | 中断当前的Python命令 |
| Ctrl + d | 退出IPython会话 |

# IPython魔法命令

IPython魔法命令都是以%符号作为前缀。行魔法以单个%字符作为前缀，作用于单行输入；单元魔法以两个%%作为前缀，作用于多行魔法。

## 粘贴代码块

%paste和%cpaste

## 执行外部代码

%run

## 计算代码运行时间

%timeit

## 魔法函数的帮助

通过?来获取帮助。

获取魔法函数的通用描述：%magic

查看所有内置魔法函数：%lsmagic

# 错误和调试

## 控制异常：%xmode

利用%xmode魔法函数，可以在异常发生时控制打印信息的数量。

## 调试

当阅读轨迹追溯不足以解决问题时，ipython提供ipdb调试。

%qdebug是ipython最方便的调试界面

[https://github.com/gotcha/ipdb](ipdb的在线文档)

