# Byer

Byer is a simple and (**truly**) clean Hexo theme currently based on [Ayer](https://github.com/Shen-Yu/hexo-theme-ayer). By designing Byer, we value your page's loading speed to the utmost and try to create an atmosphere where readers focus on your **own** contents.

## Features

### Sun and Moon!

Byer is among the few Hexo themes that contains **both light and dark themes (named Sun & Moon)**. Moreover, instead of choosing the theme in advance, Byer supports **changing theme by users live!** We optimize this feature to make it as fast as possible, and it now contributes to just a tiny bit of page loading time. It is also highly configurable as you may soon find out.

## Configuring Byer

### 粗鄙的业务逻辑先放在这里

* 若不开启默认黑暗
  * 若头一次访问，且系统为暗色模式
    * 黑暗
  * 若不是头一次访问
    * 沿用上一次的设置
* 若默认黑暗
  * 若头一次访问
    * 黑暗 (无视系统主题色)
  * 若不是头一次访问
    * 沿用上一次的设置


system项:

* 若头一次访问，配置中默认是亮色模式，且系统为暗色模式
  * 自动切换到暗色模式
* 若在开启页面时改变系统主题色
  * 自动切换到主题色

## Coming Soon

* 减少动画的选项
* 重置无封面的模式；原来那个无封面真就把封面砍了
* 加一个timeline
* 重写一个gallery
* 精简CSS