title: 整洁代码
speaker: 苑朋飞
prismTheme: solarizedlight

<slide class="bg-black-blue aligncenter" image="https://source.unsplash.com/C1HhAQrbykQ/">

# 整洁代码 {.text-landing.text-shadow}

By 苑朋飞 {.text-intro}

<slide class="bg-blue aligncenter">

## 为什么分享这个主题 {.text-landing.text-shadow}
----

<slide class="bg-blue aligncenter">

- **老生常谈 却很难做到** {.lightSpeedIn}
- **众说纷纭 无统一标准** {.lightSpeedIn}
- **自以为是 另类别致** {.lightSpeedIn}
  {.build}

<slide class="bg-blue aligncenter">

## 非整洁 Vs 整洁  {.text-landing.text-shadow}
----

<slide class="bg-blue aligncenter">

### 非整洁代码

- 乱（组织乱，职责乱，名称乱起）{.lightSpeedIn}
- 逻辑不清晰（if-else 嵌套太多）{.lightSpeedIn}
- 绕弯子（简单的事写的很复杂）{.lightSpeedIn}
- 看不懂（只有写的人能理解）{.lightSpeedIn}
- 难修改（耦合严重，各种写死）{.lightSpeedIn}
{.build}
:::

<slide class="bg-blue aligncenter">

### 整洁代码

- 清晰（是什么，做了什么，一眼看得出来）{.lightSpeedIn}
- 简单（职责少，代码少，逻辑少）{.lightSpeedIn}
- 干净（没有冗余的逻辑）{.lightSpeedIn}
- 好拓展（依赖的比较少，修改不会影响很多）{.lightSpeedIn}
{.build}

<slide class="bg-blue aligncenter">

## 如何写整洁代码
----

<slide class="bg-blue aligncenter">

### 涵盖的方面

- 命名 {.lightSpeedIn}
- 注释 {.lightSpeedIn}
- 函数（封装）{.lightSpeedIn}
- 参数 {.lightSpeedIn}
- 排版 {.lightSpeedIn}
{.build}

<slide class="bg-blue aligncenter">

### 思想上 && 行为上
----

<slide class="bg-blue aligncenter">

#### 思想上 {.lightSpeedIn}

- 自我要求 {.lightSpeedIn}
- 养成习惯 {.lightSpeedIn}
{.build}

<slide class="bg-blue aligncenter">

#### 行为上 {.lightSpeedIn}

- 定期自我 review + refactor {.lightSpeedIn}
- code review + refactor {.lightSpeedIn}

{.build}

<slide class="bg-blue aligncenter">

## 针对 React
----

<slide class="bg-blue aligncenter">

### 组件的封装

- 按模块 {.lightSpeedIn}
- 粒度适中 {.lightSpeedIn}
- 高内聚 {.lightSpeedIn}
- 低耦合 {.lightSpeedIn}
- 可复用 {.lightSpeedIn}
{.build}

<slide class="bg-blue aligncenter">

### 业务逻辑处理

- 依赖清晰 {.lightSpeedIn}
- 函数封装细节 {.lightSpeedIn}
- error 及边界情况处理 {.lightSpeedIn}
{.build}

<slide class="bg-blue aligncenter" >

## 书籍推荐
----

<slide class="aligncenter bg-blue">

:::gallery

![](https://ebook23new.hi67.cn/forum/201812/03/172433t3crc2ukrffekl2r.jpg)
## 代码整洁之道

Robert C. Martin

---
![](https://www.javaweb.shop/upload/image/20191030/1572413997214.jpeg)
## 重构

Martin Fowler

---
![](https://s3.cn-north-1.amazonaws.com.cn/sitbweb-cn/content/B00E593N1U/images/cover.jpg)
## 编写可读代码的艺术

Dustin Boswell 

---
![](http://www.java1234.com/uploads/allimg/160110/1-1601100JA3127.jpg)
## Javascript设计模式开发实践

曾探
:::

<slide class="bg-blue aligncenter" >

# Thanks