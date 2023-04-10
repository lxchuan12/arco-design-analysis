`````
组件 / 数据展示

# 空状态 Empty

指当前场景没有对应的数据内容，呈现出的一种状态。
`````

## 基本属性

### 组件定义

指当前场景没有对应的数据内容，呈现出的一种状态。

### 组件构成

空状态由自定义图标或自定义插图、文字、按钮或文字链组成

1. **自定义图标/自定义插图（可选）** ：符合当前场景的图片或图标。
2. **文字（可选）** ：对当前状态的一个简单说明介绍，也可用于指导用户行为。
3. **按钮/文字链（可选）** ：对改变当前状态的的一个引导性操作。

![](https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/86106e67006647e54be96e7ee355c426.png~tplv-uwbnlip3yd-webp.webp)

### 组件类型

| 类型                | 说明                                                           |
| ----------------- | ------------------------------------------------------------ |
| 1.文字型             | 纯文字的提示，对用户干扰较小，但不容易引起用户的注意                                   |
| 2.自定义插图+文字型       | 符合当前场景的插图加文字的说明，有较强的情感化表达，吸引用户注意，利于提升产品形象，但是对用户干扰较大。         |
| 3.自定义图标+文字型       | 符合当前场景的图标加文字的说明，容易被理解，便于用户发现；但是与其他产品差异小，缺少情感化的表达。            |
| 4.自定义插图/自定义图标+按钮型 | 符合当前场景的图标/插图和引导用户操作的按钮，突出引导用户进行其他操作，尽可能减少插图带给用户的理解成本，提升使用效率。 |

![](https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/b0e56300f812be8b2bbb65a03abc094f.png~tplv-uwbnlip3yd-webp.webp)

## 何时使用

用户执行操作并没有展示数据时（例如搜索没有结果时）。

1. **文字型**：页面中的控件没有内容时使用，例如下拉搜索、手风琴、折叠面板、穿梭框、下拉菜单等。
2. **自定义图标+文字型**：页面中有其他内容，且某一个组件或模块没有数据时使用，例如空表单、空数据图等。
3. **自定义插图+文字型**：页面中没有内容时使用，例如页面无数据、网络连接失败、无权限、404、405等。
4. **自定义图标/插图+按钮型**：帮助用户摆脱空状态，提供出口或其他功能链接。

## 布局

- 图标/插图与文字多采用**上下**布局

![](https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/63c93c5bba5f4704959b568ee0290139~tplv-uwbnlip3yd-image.image)

## 文案指南

- 当有图标或插图等有情感温度的信息时，空状态会感觉更好。

- 帮助用户摆脱空状态，进入可以操作的地方，建议突出显示用户可以采取的行动。

- 文字说明建议采用指导的语气而不是责怪和告知。

- 建议非视觉信息清楚明了，插图和图标只是辅助作用。

## 关联组件

[按钮](/react/components/button)

[链接](/react/components/link)