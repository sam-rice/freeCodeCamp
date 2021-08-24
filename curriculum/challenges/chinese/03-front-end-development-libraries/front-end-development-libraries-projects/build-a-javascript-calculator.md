---
id: bd7158d8c442eddfaeb5bd17
title: 构建一个 JavaScript 计算器
challengeType: 3
forumTopicId: 301371
dashedName: build-a-javascript-calculator
---

# --description--

**目标：** 在 [CodePen.io](https://codepen.io) 上实现一个功能类似 <https://codepen.io/freeCodeCamp/full/wgGVVX> 的 App。

在满足以下[需求](https://en.wikipedia.org/wiki/User_story)并能通过所有测试的前提下， 可以根据自己的喜好来美化 app。

可以使用 HTML、JavaScript、CSS、Bootstrap、SASS、React、Redux、jQuery 来完成这个挑战。 但鉴于这个章节的学习内容与前端框架相关，推荐使用一款前端框架（比如 React）来完成这个挑战。 不推荐使用前面没有提到的技术，否则风险自负。 我们有计划新增其他前端框架课程，例如 Angular 和 Vue，不过目前还没有这些内容。 我们会接受并尝试修复使用推荐技术栈遇到的反馈问题。 编码愉快！

**需求 1：** 计算器应该包含一个具有 `id="equals"` 属性的可以点击的元素，元素的文本内容为 `=`（等于符号）。

**需求 2：** 计算器应该包含 10 个具有如下 id 属性的可以点击的元素，每个元素的文本内容对应 0-9 的数字：`id="zero"`、`id="one"`、`id="two"`、`id="three"`、`id="four"`、`id="five"`、`id="six"`、`id="seven"`、`id="eight"`、`id="nine"`。

**需求 3：** 计算器应该包含四个可以点击的元素，文本内容对应4个主要数学运算符，且应具有如下 id 属性： `id="add"`, `id="subtract"`, `id="multiply"`, `id="divide"`。

**需求 4：** 计算器应该包含一个可点击的 `.`（小数点）符号，对应的 `id="decimal"`。

**需求 5：** 计算器应该包含一个具有 `id="clear"` 属性的可以点击的元素。

**需求 6：** 我的计算器应该包含一个用于展示数值的元素，这个元素具有 `id="display"` 属性。

**需求 7：** 在任何时候按下 `clear` 键，都会清空输入和输出的数值并且使计算器回到初始状态；此时在 id 为 `display` 的元素中应该显示数字 0。

**需求 8：** 在输入数字的同时，应该能看到输入的数字展示在 id 为 `display` 的元素中。

**需求 9：** 应该可以在任意顺序下对一串任意长度的数字执行加、减、乘、除操作，并且当按下 `=` 时，正确答案应该显示在 id 为 `display` 的元素中。

**需求 10：** 在输入数字的同时，计算器应该不允许一个数字以多个零开头。

**需求 11：** 当点击小数点元素时，当前展示的数值后面应该添加一个 `.` 符号；数字中不允许出现两个 `.` 符号。

**需求 12：** 我可以对包含小数点的数字执行任何四则运算（`+`、`-`、`*`、`/`）。

**需求 13：** 如果连续键入了两个及以上的运算符，应该执行最后一次键入的运算符（负数（`-`）运算符除外）。 例如，如果输入 `5 + * 7 =`，结果应该是 `35` （等同于 `5 * 7`）；如果输入 `5 * - 5 =`，结果应该是 `-25`（等同于 `5 * (-5)`）。

**需求 14：** 如果在按下 `=` 符号后继续按一个运算符，则应该在上一次计算结果的基础上进行新的计算。

**需求 15：** 当需要四舍五入时，计算器可以处理结果的精度（注意：处理到多少位没有一个准确的标准，但是至少能处理类似 `2 / 7` 这样的计算，使之至少有 4 位小数的精度）。

**注意计算器的逻辑：** 应当注意的是，计算器输入逻辑主要有两种思路：<dfn>立即执行逻辑</dfn> 和 <dfn>公式逻辑</dfn>。 我们的示例使用公式逻辑并遵守运算优先顺序，而立即执行则不然。 两者都是可以接受的，但请注意，根据你的选择，你的计算器对于某些算式可能会得到与示例不同的计算结果（参见下面的示例）。 只要数学计算可以通过其它现实中计算器的验证，那么代码就是合理的。

**示例：** `3 + 5 x 6 - 2 / 4 =`

-   **立即执行逻辑：** `11.5`
-   **公式／表达式逻辑：** `32.5`

你可以<a href='https://codepen.io/pen?template=MJjpwO' target='_blank' rel='nofollow'>使用这个 CodePen 模板</a>，点击 `Save` 即可创建你自己的项目。 或者可以在任何喜欢的环境中使用以下 CDN 链接来运行测试：`https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js`。

当你完成了本项目，并且该项目所有测试运行通过，请提交项目的 URL。

# --solutions--

```js
// solution required
```