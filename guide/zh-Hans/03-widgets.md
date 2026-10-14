# 3. 小组件与锁定屏幕

[← 目录](./README.md)

---

小组件的意义，就是让你不必为了看下一件事而打开应用。To-do Calendar 提供了一整套小组件，你可以挑一个符合自己查看习惯的 —— 只看下一件事、看一整个月，或者看带勾选框、能直接点的待办列表。

---

## 主屏幕小组件

### 今天及接下来的安排

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/zh-Hans/widget-today-and-next.png" alt="今天及接下来的安排小组件" width="360">

左边是今天的日期和今天剩下的事，右边是接下来要发生的。没有别的小组件能一次显示这么多。

*中。*

### 事件

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/zh-Hans/widget-event-list.png" alt="事件小组件" width="300">

按天分组、一路排下去的待办与日程列表，也包含你的当前待办。有三种尺寸，越大能看到的天数越多。

*小 · 中 · 大。*

### 今天

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/zh-Hans/widget-today.png" alt="今天小组件" width="200">

只有今天 —— 日期、当天如果是假期就显示假期名称，还有你有几个待办和几个日程。

*小。*

### 最重要事件

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/zh-Hans/widget-foremost.png" alt="最重要事件小组件" width="200">

你钉为最重要的那一个事件，始终在视线里。请参考 [最重要事件](./01-basics.md#最重要事件)。

*锁定屏幕内嵌 · 小 · 中。*

### 倒计时

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/zh-Hans/widget-dday.png" alt="倒计时小组件" width="200">

为你自己选定的一个事件倒数 —— 显示它的名称、还剩几天，以及日期。

- **选择事件** —— 长按小组件、选「编辑小组件」，再点 **事件**。今天前后的日程和假期会列出来供你挑选。
- **把事件放到列表最上面** —— 在日程的更多菜单里选 **添加到倒计时小组件**，或者在当天的事件列表里长按这个日程。下次编辑小组件时，它们会排在最前面。
- **重复日程** —— 选好之后，用 **重复次数** 决定倒数到第几次。

*锁定屏幕圆形 · 矩形 · 内嵌 · 小 · 中。*

### 日历与周视图

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/zh-Hans/widget-month.png" alt="日历小组件" width="360">

日历本身，范围由你决定：

| 小组件 | 尺寸 |
|---|---|
| 日历 | 小 |
| 本周 · 2周 | 中 |
| 3周 · 4周 | 大 |
| 上个月 · 本月 · 下个月 | 大 |

### 组合小组件

一个视图不够用时，把两块面板放进同一个小组件：

| 小组件 | 显示内容 | 尺寸 |
|---|---|---|
| 今天 + 日历 | 今天的摘要和本月日历并排 | 中 |
| 事件 + 日历 | 接下来的事件和本月日历并排 | 中 |
| 事件 + 最重要 | 接下来的事件和你钉住的事件并排 | 中 |
| 日历 + 日历 | 两个月并排显示 | 中 |

### 使用AI添加

点一下就直接进 [AI快捷输入](./02-ai-input.md)。

*锁定屏幕圆形 · 小。*

---

## 在小组件上能做的事

- **勾掉一个待办** —— 点小组件里任意待办前面的圆圈就能完成，不用打开应用。
- **点进事件** —— 点一个事件，会直接打开它的详情界面。
- **按事件类型筛选** —— 长按小组件、选「编辑小组件」，就能把它限定为特定的事件类型。你自己建的类型和已连接的外部日历都会出现在选择器里。

---

## 锁定屏幕

### 锁定屏幕小组件

有几个小组件提供锁定屏幕形态：**下一个事件**（内嵌和矩形）、**今天剩余的事件**（矩形）、**最重要事件**（内嵌）、**倒计时**（圆形、矩形和内嵌）和 **使用AI添加**（圆形）。

### 实时活动倒计时

把一个事件放到锁定屏幕上，就能看着它一点点倒数，灵动岛里也是同一个视图。在事件的更多菜单里选 **在锁定屏幕上显示** 就可以了。

- 只有 8 小时内开始的事件可以显示。
- 一次只能有一个 —— 再选一个新的，应用会问你要不要替换当前那个。
- 待办可以直接在实时活动上完成。

---

## 控制中心

在 iOS 18 及以上的系统里，你可以把 **用AI添加** 控制项加进控制中心，这样在任何地方往下一划、点一下，就能进到 AI 输入界面。

---

## 自定义小组件

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/zh-Hans/widget-gallery.png" alt="小组件图库" width="280">

打开 **设置 › 外观 › 小组件图库**，可以看到所有小组件以及各自的尺寸。选一个小组件，点 **自定义**。

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/zh-Hans/widget-style-edit.png" alt="自定义小组件" width="280">

- **详细选项** —— 逐个打开或关闭小组件上的元素，比如假期名称、时区或事件数量。能关掉哪些，取决于具体的小组件。
- **背景颜色** —— 保持 **跟随通用小组件主题**，或者给这个样式单独设一种颜色或一张照片。
- **新建样式** —— 为同一个小组件保存好几套外观，每套都有自己的名字。用 **复制** 可以从一份副本开始改。

改动会实时显示在预览里。要使用某个样式，在主屏幕上长按小组件、选「编辑小组件」，在 **小组件样式** 里选它 —— 同一个小组件放两个，也可以各用不同的样式。删除一个样式后，用它的小组件会回到 **默认**。

锁定屏幕小组件保持系统给定的外观。

---

## 外观

小组件默认跟随系统的浅色／深色设置，你也可以把它固定成自己喜欢的背景颜色 —— 应用会根据这个颜色有多亮，自动选出读得清的文字颜色。在 **设置 › 外观 › 小组件图库** 最上面的 **小组件主题** 里设定。样式自己设了背景颜色的话，以样式的为准。请参考 [个性化](./05-personalization.md)。

小组件一整天会自己刷新，你在应用里改了什么之后也会马上更新。

---

[← 目录](./README.md) · [下一章：外部日历 →](./04-external-calendars.md)
