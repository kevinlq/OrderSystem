# OrderSystem
## 使用Qt开发的一个简单的订餐系统
### 开发环境:
window10,Qt5.6 mingw编译器

### 主要模块

本系统分为3个部分，服务器端、手持端、厨房端

### 实现功能：
 1. 手持端实现了顾客开台，选菜，催菜，加菜，退菜等功能；
 2. 服务器端实现了对顾客发送的菜单请求的同意，并将菜单发送给厨房端，通知做菜；
 3. 服务器端可以简单的保存顾客的结账信息；
 4. 厨房端收到菜单后开始做菜，若发现某道菜因为太特殊原因无法做时，发送原因给服务器，服务器收到后发给相应的手持端提示顾客；
 5. 厨房端可以改变菜的状态，做完后点击完成按钮，可以是实现对菜的状态改变。
