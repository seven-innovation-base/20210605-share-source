---
# try also 'default' to start simple
theme: 'apple-basic'

# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# image: 'https://source.unsplash.com/collection/94734566/1920x1080'
image: 'https://cdn.jsdelivr.net/gh/ssmath/mypic/banner.jpg'

# apply any windi css classes to the current slide
# class: 'text-center'

layout: intro-image
# https://sli.dev/custom/highlighters.html
# highlighter: shiki

# # some information about the slides, markdown enabled
# info: |
#   ## Slidev
#   Presentation slides for developers.

#   Learn more at [Sli.dev](https://sli.dev)
---

<div class="absolute top-10">
  <span class="font-700">
    2021 年 6 月 4 日
  </span>
</div>

<div class="absolute bottom-35">
  <h1>Hybrid Share</h1>
  <p>Created by yeshan333</p>
  <div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Get Started <carbon:arrow-right class="inline"/>
  </span>
  </div>
</div>

<a href="https://github.com/seven-innovation-base/20210605-share-source" target="_blank" alt="GitHub"
  class="abs-br m-6 text-xl icon-btn opacity-50 !border-none !hover:text-white">
   <carbon-logo-github />Slide 源码
</a>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-right
image: 'https://cdn.jsdelivr.net/gh/ssmath/mypic/2021mypicavatar.jpg'
---

# About Me

<!-- Component usage: this will be invisible until you press "next" -->
<v-click>

- ShanSan、yeshan333、Cloudys
<br />

</v-click>

<v-click>

- “基地底层人员”
<br />

</v-click>

<v-click>

- Interest: 👻Cloud Native、Front-end
<br />

</v-click>

<v-click>

- blogger: https://shansan.top
<br />

</v-click>

<v-click>

- slides: https://slides.shan333.cn 👉[old](https://slide.shan333.cn)
<br />

</v-click>

<br />

<div v-click>

```go
package main

import "fmt"

func main() {
	fmt.Println("talk to me")
}
```

</div>

<!-- Directive usage: this will be invisible until you press "next" the second time -->
<div v-click class="absolute bottom-3">

Hey!
<a href="https://twitter.com/CloudysYe" target="_blank" alt="Twitter"
  class="text-3xl icon-btn !border-none !hover:text-white">
  <mdi-twitter-circle />
</a>
<a href="https://github.com/yeshan333" target="_blank" alt="GitHub"
  class="text-3xl icon-btn !border-none !hover:text-white">
  <mdi-github-circle />
</a>
<a href="https://stackoverflow.com/users/11864006/cloudys" target="_blank" alt="Stack Overflow"
  class="text-3xl icon-btn !border-none !hover:text-white">
  <mdi-stackoverflow />
</a>
<a href="https://www.douban.com/people/178862094/" target="_blank" alt="Douban"
  class="text-3xl icon-btn !border-none !hover:text-white">
  <mdi-douban />
</a>
<a href="https://www.zhihu.com/people/si-kong-ji-54" target="_blank" alt="Zhihu"
  class="text-3xl icon-btn !border-none !hover:text-white">
  <img src="https://cdn.jsdelivr.net/gh/ssmath/mypic/zhihu.svg" />
</a>

</div>

<style>
  li {
    @apply text-xl font-black;
  }
</style>

---
layout: center
class: text-center
---

# 曾经在基地的做过的事 & 一些思考

<br />
<br />

# proposals •『建议』

<!--

介绍那些对我有意义的操作：博客、外文翻译，

一些建议<之前没给那是我觉得 18 级的视野应该差不多了，>

上述会有交叉内容出现

-->

---

## 曾经在基地做的一些事情 & 一些思考

<div class="text-center">

<br />
<br />

<p class="font-bold text-xl">考核 & 高年级存在的意义</p>

<br />

<p class="font-bold text-xl">个人博客推广-基地的博客</p>

<br />

<p class="font-bold text-xl">🧑‍💻比赛的宣传-计算机</p>

<br />

<p class="font-bold text-xl">技术分享-Lightning Talk</p>

<br />

<p class="font-bold text-xl">🧑‍💻GitHub Organization & LAN Wiki</p>

</div>

---

## 考核 & 高年级存在的意义

<div class="absolute top-45 left-70">

<ul>
<li v-click class="text-2xl">KPI？<span class="text-3xl" style="color:red">×</span>&ensp;压力<span class="text-3xl" style="color:red">×</span></li>
<br/>
<li v-click class="text-2xl">打开技术视野，能给的帮助其实不多</li>
<br/>
<li v-click class="text-2xl">Teacher？or Student？</li>
<br/>
<li v-click class="text-2xl" style="color:red;">Teach Yourself</li>
</ul>
</div>

<!--
说说心声
高年级了解的东西还是相对多的，当我在你们这时候的也一直想要学长/学姐的操作一手，实际我们这人口基数少，技术领域又多，很难的，关键还是要学会 teach yourself
我们也是学生，都在学习，这里不会像学校一样帮你排好课<按部就班？>，自主调整时间
“闭门造车” x
“集思广益” 钩
-->

---

# 博客

<div class="absolute top-45 left-70 text-center">


<h2> 个人博客 - Hexo、WordPress、...</h2>

<br />
<br />
<br />
<br />

<h2>基地博客: <a href="https://xn--7gqr3hs9ecxao51c822e.cn/blog" target="_blank">https://七院创新基地.cn/blog</a></h2>

</div>

<!--

个人博客需要维护的，博客朋友圈，打脸式成长，
自己的个人网站自己说了算，没那么多的规规矩矩
基地博客的意义：一个技术团队是应该有技术博客/网站的，对外展现 power 的舞台，之前缺少沉淀

-->

---
layout: image
image: 'https://cdn.jsdelivr.net/gh/ssmath/mypic/%E5%9F%BA%E5%9C%B0%E5%8D%9A%E5%AE%A2.png'
---

yeah!

---

# 比赛

<iframe src="https://slides.shan333.cn/slides/slide_1.html#/" width="100%" height="360">
</iframe>


**Need: 赛事时间表**

<!--
以赛代学也是一种好方式
一些比赛的介绍，虽然有塞氪网：https://www.saikr.com/，但我们需要有自己的赛事时间表

-->

---

# ⚡Lightning Talk
## 源于 PyCon China 2019 闪电演讲，[Link🔗](https://shimo.im/docs/QQTGphyyRhV9GdJV?fallback=1)

<p v-click class="text-center">互相了解下大家都在做什么，一种新的磨练方式 - <span style="color:red">Share & Talk</span></p>

<iframe src="https://slides.shan333.cn/slides/index.html" width="100%" height="330">
</iframe>

2019 年 10 月 19 日，晚

<!--
希望基地多一些沟通交流的方式，比较新，没感受过，之前就个考核能看看大家做的东西
希望能有更多自己想出来的 Topic
后续接触费曼技巧
分享，学生时代的 Demo 价值不高，技术分享，反哺自身
顺便促进基地内部的沟通，了解下别人正在做的事，也许某一天你的 idea需要到
他/她的帮助
-->

---

# 费曼（Feynman）技巧

<br />
<br />

<h2 v-click class="text-center">真的学会了吗？学习感的自我催眠！</h2>

<div v-click class="absolute top-45 left-100">

- 用简单的话
<br />
- 用自己的话说出来
<br />
- 不带行话术语
<br />
- 说给八十岁的老奶奶听
<br />
- 说给八岁的小孩子听

</div>

<div v-click class="absolute bottom-10">上述费曼技巧定义，来自语雀-<a href="https://www.yuque.com/arvinxx/osft8q" target="_blank">小熊熊的《知识管理系统》</a>
</div>

<!--
真正学会，主动创造应用知识的机会，
彩排自己对知识的掌握程度
Lightning Talk - 给你们创造的机会
我没没法说给 80 岁的老人听，8岁的小孩听，
但我们可以说给彼此听
学习金字塔：https://slides.shan333.cn/slides/20201112/t01301346dd3225d2cd.png
-->

---
layout: intro-image
image: 'https://cdn.jsdelivr.net/gh/ssmath/mypic/GitHub_org.png'
---

<h2 class="absolute right-10" style="color:black">🧑‍💻GitHub Organization & LAN Wiki</h2>

<!--
项目协作学习，开源社区协作方式

一段回忆

（工程协作，历史产物上传（之前东西一直在负责人手里，考核的项目是值得分享的，OSS）
-->

---
layout: intro-image
image: 'https://cdn.jsdelivr.net/gh/ssmath/mypic/wikijs.png'
---

<h2 class="absolute top-20 right-10" style="color:black">🧑‍💻GitHub Organization & LAN Wiki</h2>
<h2 class="absolute top-40 right-10" style="color:black">🔗‍<a href="http://125.217.41.230:8080/zh/home" target="_blank">125.217.41.230:8080</a></h2>

<!--
项目协作学习，开源社区协作方式

一段回忆

（工程协作，历史产物上传（之前东西一直在负责人手里，考核的项目是值得分享的，OSS）
-->

---
layout: fact
---

## [Git2Github-practice](https://github.com/seven-innovation-base/Git2Github-practice) @founder: [CkaiGrac](https://github.com/CkaiGrac)

<br />
<br />

## [official-website](https://github.com/seven-innovation-base/official-website) @Created at 2020, Docusaurus-based

<br />
<br />

团队协作 & 工程化技术落地实践

内网wiki、服务器维护仍有许多问题待解决

<!--
项目协作学习，开源社区协作方式

一段回忆

（工程协作，历史产物上传（之前东西一直在负责人手里，考核的项目是值得分享的，OSS）
-->

---
layout: statement
---

# proposals •『建议』

---

# English Level

<div class="absolute top-45 left-80 text-center">

<h2>最新技术了解、学习</h2>

<br />
<br />

<h2>项目文档、开源项目参与</h2>

<br />
<br />

<h2>Stackoverflow、GitHub issue</h2>

<br />
<br />

<h2 v-click style="color:green">
技术文章翻译项目 - GitHub
</h2>

</div>

<!--
后期成长需要我们阅读更多外国的文章，新技术学习

机翻的效果没有那么理想

相对来说 EN 的文章质量水平是更高，More value

我们大四毕设也有个翻译
-->

---

# 一些你们可没接触过的知识来源渠道

<br />

<div class="text-center">

<br />

# RSS Feed

<br />
<br />

# 技术日报/周刊/月刊

<p>（奇舞周刊、GoCN每日新闻、Hello GitHub月刊等）</p>
<p v-click style="color: green">（by the way，也许基地可以有自己的技术周刊），<a href="https://wubaiqing.github.io/zaobao/" target="_blank">e.g. 每日时报</a></p>

<br />
<br />

# 播客（Podcast）

<p v-click><a href="https://pythonhunter.org/">@捕蛇者说</a></p>

<br />

</div>

<!--
RSS：有些大佬只有博客，订阅不像微信公众号
互相推荐文章，基地自己的技术周刊，消息聚合
podcast：捕蛇者说有几期知识输入、输出相关的
-->

---
layout: image-right
image: 'https://cdn.jsdelivr.net/gh/ssmath/mypic/basic.jpg'
---

# 系统化 vs 碎片化

- 书（系统性）
- 微信公众号、CSDN、掘金、知乎、博客园文章（碎片化）
- More ....

<div class="absolute bottom-30">

编译、网络、系统方面的知识需要系统学习

- [为什么这么设计](https://draveness.me/whys-the-design/)
- [what-happens-when-zh_CN](https://github.com/skyline75489/what-happens-when-zh_CN)

</div>

<!-- 提到知识输入不得不提系统性与碎片性 -->

---

# 输出

<h1 class="text-center">博文、Talk（Lighting Talk）、...</h1>

<div v-click>

|     |     |
| :---: | :---: |
| “闭门造车” | <p style="color:red">No❌</p> |
| “集思广益” | <p style="color:green">Yes✔️</p> |

</div>

<br />
<br />

<div v-click class="text-center text-2xl">博客活跃程度？不得不承认，学习热情会随时间慢慢衰减</div>

<!--
别人的建议，打脸式成长，评判空间，历史证据
不得不承认，学习热情会随时间慢慢衰减
不同的阶段，有不同的想法，希望更多的同学能出来分享，互相进步
-->

---

# 练手项目来源，捞点成就感

<br />
<br />
<br />
<br />
<br />

<div class="text-center">

<h2><a href="https://github.com/danistefanovic/build-your-own-x" target="_blank">build-your-own-x - from GitHub</a></h2>

<br />
<br />
<br />

<h2><a href="https://github.com/tuvtran/project-based-learning" target="_blank">project-based-learning - from GitHub</a></h2>

<br />
<br />
<br />

</div>

<h2 class="text-center">一开始总是在模仿中学习，“微微”想法注入</h2>

<!-- 创新自我感觉很难。。。技术演讲也可以捞点成就感，别人的认可 -->

---
layout: center
class: text-center
---

# Thanks

[More Slides](https://slides.shan333.cn) / [GitHub Profile](https://github.com/yeshan333)

---
layout: center
class: text-center
---

# END

---

## 我在基地的成长

<!-- 介绍那些对我有意义的操作：博客、外文翻译，做一些东西获取成就感 -->

<div class="text-center">

📃博客<!-- 记录学习，打脸式成长，扩展技术圈，认识人 -->

🧑‍💻比赛 - “惭愧，我很捞，后续为基地做事捞一手比赛会讲，因为遗憾，有些比赛甚至不知道”<!-- 不容否定比赛的意义，成就感获取 -->

🧑‍💻GitHub-Open Source

大二下~大三的那段时间-瞄准了技术大会（PyCon China等）

reading-读读书（系统学习），微信公众号、博文、CSDN、掘金、博客园等等（碎片化）

<img src="https://cdn.jsdelivr.net/gh/ssmath/mypic/20210605213303.png" />

</div>

总结：上述操作在获取成就感（16级学长讲过），得到别人承认。

<!-- 不得不承认，激情会随时间慢慢衰减 -->

peer pressure（同龄压力）

感慨：做好自己，一直比较还是太累了。
