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

有几个小组件提供锁定屏幕形态：**下一个事件**（内嵌和矩形）、**今天剩余的事件**（矩形）、**最重要事件**（内嵌）和 **使用AI添加**（圆形）。

### 实时活动倒计时

把一个事件放到锁定屏幕上，就能看着它一点点倒数，灵动岛里也是同一个视图。在事件的更多菜单里选 **在锁定屏幕上显示** 就可以了。

- 只有 8 小时内开始的事件可以显示。
- 一次只能有一个 —— 再选一个新的，应用会问你要不要替换当前那个。
- 待办可以直接在实时活动上完成。

---

## 控制中心

在 iOS 18 及以上的系统里，你可以把 **用AI添加** 控制项加进控制中心，这样在任何地方往下一划、点一下，就能进到 AI 输入界面。

---

## 外观

小组件默认跟随系统的浅色／深色设置，你也可以把它固定成自己喜欢的背景颜色 —— 应用会根据这个颜色有多亮，自动选出读得清的文字颜色。在 **设置 › 外观 › 小组件主题** 里设定。请参考 [个性化](./05-personalization.md)。

小组件一整天会自己刷新，你在应用里改了什么之后也会马上更新。

---

[← 目录](./README.md) · [下一章：外部日历 →](./04-external-calendars.md)
