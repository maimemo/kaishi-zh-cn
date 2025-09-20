# Kaishi 1.5k zh-CN

欢迎使用 Kaishi 1.5k 中文版！这是一个基于日语基础词汇牌组 [Kaishi 1.5k](https://github.com/donkuri/Kaishi) 的汉化项目，旨在为国内的日语学习者提供一个更加便捷的学习资源。

下载地址：<https://github.com/maimemo/kaishi-zh-cn/releases>，文件名：Kaishi 1.5k zh-CN.apkg

## 主要特点

原牌组由 [donkuri](https://github.com/donkuri) 和 TheMoeWay 社区制作，经过多次优化和改进，有以下特点：

-   **问题解决：** 针对 Core 2k 和 Tango 等牌组的翻译错误、生僻词汇、格式限制及例句不佳等常见问题进行优化。
-   **内容精选：**
    -   **高频词汇：** 从多来源整合并按频率筛选出约 1500 个核心词汇。
    -   **准确性：** 修正词汇翻译，精选并修正例句。
    -   **语音与声调：** 包含高质量词汇音频、精确声调数据（经人工校对）。
    -   **阅读辅助：** 提供词汇及例句假名标注。
-   **质量保障：**
    -   **卡片设计：** 提供优化的提示目标例句卡片 CSS。
    -   **严格校对：** 经过多轮人工校对，最大程度减少错误。

本项目在此基础上，进行了全面的汉化处理，并添加了活用相关的说明，力求为中文用户提供更好的使用体验。

以下是原牌组的 README.md 的翻译。

# Kaishi 1.5k

欢迎访问 **Kaishi 1.5k** 的公开代码仓库。这是一款现代化的 Anki 牌组，旨在帮助初学者入门基础日语词汇。Kaishi 1.5k 采用高度模块化设计，本页面将为你详细介绍各种自定义选项，让你可以随心所欲地调整牌组。牌组正面效果如下：

[![Kaishi 1.5k 卡片正面示例](https://github.com/donkuri/Kaishi/raw/main/pics/kaishi-front.png)](https://github.com/donkuri/Kaishi/blob/main/pics/kaishi-front.png)

如你所见，卡片正面同时显示单词和例句，并且单词在句子中被高亮显示，方便你迅速抓住核心信息。当你对单词足够熟悉后，复习效率会更高，因为单词总会最先映入眼帘。默认牌组的背面如下：

[![Kaishi 1.5k 卡片背面示例](https://github.com/donkuri/Kaishi/raw/main/pics/kaishi-back.png)](https://github.com/donkuri/Kaishi/blob/main/pics/kaishi-back.png)

与大多数「核心词汇」（Core）类牌组不同，本牌组的振假名（furigana）直接标注了单词读音，其正下方就是词义。接着，你还可以收听单词和例句的音频。如果你需要，也可以添加音高重音（详见下文）。如果某张卡片有相关笔记，笔记会显示在最下方。

[如果你是日语初学者或刚接触沉浸式学习法，请先阅读本指南。](https://donkuri.github.io/learn-japanese/guide/)

### 目录

- [如何获取本牌组？](https://github.com/maimemo/kaishi-zh-cn#如何获取本牌组？)
- [如何使用本牌组？](https://github.com/maimemo/kaishi-zh-cn#如何使用本牌组？)
- [其他相关牌组](https://github.com/maimemo/kaishi-zh-cn#其他相关牌组)
- [牌组有哪些自定义选项？](https://github.com/maimemo/kaishi-zh-cn#牌组有哪些自定义选项？)
- [我不喜欢这些图片！](https://github.com/maimemo/kaishi-zh-cn#我不喜欢这些图片！)
- [如何将 Kaishi 导入到现有牌组中？](https://github.com/maimemo/kaishi-zh-cn#如何将-kaishi-导入到现有牌组中？)
- [牌组的诞生故事](https://github.com/maimemo/kaishi-zh-cn#牌组的诞生故事)
- [牌组的多语言翻译](https://github.com/maimemo/kaishi-zh-cn#牌组的多语言翻译)
- [学完这个牌组后该做什么？](https://github.com/maimemo/kaishi-zh-cn#学完这个牌组后该做什么？)
- [致谢名单](https://github.com/maimemo/kaishi-zh-cn#致谢名单)

## 如何获取本牌组？

你可以在本 GitHub 项目的 [releases](https://github.com/donkuri/Kaishi/releases/) 页面下载，或者在 [AnkiWeb](https://ankiweb.net/shared/info/1196762551) 上获取（前提是牌组未处于审核状态）。**本牌组支持 Anki 2.1.50 及以上版本。**

## 如何使用本牌组？

若想了解 Kaishi 如何融入更宏大的日语学习计划，请参阅[这份指南](https://donkuri.github.io/learn-japanese/guide/)。

## 其他相关牌组

用户 ねむい 基于 Kaishi 1.5k 制作了一款部首牌组。它将 Kaishi 1.5k 中出现的每一个汉字部首，都与牌组中首个包含该部首的单词关联起来，同时还额外收录了一些 Kaishi 未包含的部首。**如果你觉得汉字很难，可以将这款部首牌组与 Kaishi 配合使用**，因为它会随着你的学习进度同步介绍汉字部首，助你更高效地拆解汉字。你可以在 [AnkiWeb](https://ankiweb.net/shared/info/1722008986) 上找到它。非常感谢 ねむい！

## 牌组有哪些自定义选项？

你可以通过多种选项来修改卡片。操作方法是：选中 Kaishi 牌组，点击「浏览」（Browse），在牌组中任选一张卡片，然后点击右上角的「卡片...」（Cards...）按钮。

### 音高重音

最重要的选项莫过于是否在卡片上显示音高重音。目前，关于是否应该学习音高重音，社区里时常有非常激烈的讨论。我们选择了一种折衷方案：我们为你提供了音高重音数据，但用不用由你决定。即使你现在选择不用，以后也随时可以开启。开启方法很简单，下面是牌组的「背面模板」（Back Template）代码（点击「搜索」栏上方的小圆点切换）：

```
<div lang="ja">
{{furigana:Word Furigana}}

<!-- This part enables pitch accent.

{{#Pitch Accent}}
	<br><div style='font-size: 24px'>{{Pitch Accent}}</div>
{{/Pitch Accent}} 

-->

<div style='font-size: 25px; padding-bottom:20px'>{{Word Meaning}}</div>
<div style='font-size: 25px;'>{{furigana:Sentence Furigana}}</div>
<div style='font-size: 25px; padding-bottom:10px'>{{Sentence Meaning}}</div>

{{Word Audio}}
{{Sentence Audio}}
<br>
{{Picture}}

{{#Notes}}
	<br>
	<div style="font-size: 20px; padding-top:12px">Note: {{Notes}}</div>
{{/Notes}}

<!-- This part enables pitch accent notes.

{{#Pitch Accent Notes}}
<div style="font-size: 20px; width: fit-content; max-width:40vw; margin: auto">
	<details><summary>Pitch Accent Notes</summary>
		<br>{{Pitch Accent Notes}}
	</details>
</div>
{{/Pitch Accent Notes}}

-->

</div>
```

要启用音高重音，你只需移除所有代表注释的`<!--`和`-->`符号即可，就像这样：

```
<div lang="ja">
{{furigana:Word Furigana}}

{{#Pitch Accent}}
	<br><div style='font-size: 24px'>{{Pitch Accent}}</div>
{{/Pitch Accent}} 

<div style='font-size: 25px; padding-bottom:20px'>{{Word Meaning}}</div>
<div style='font-size: 25px;'>{{furigana:Sentence Furigana}}</div>
<div style='font-size: 25px; padding-bottom:10px'>{{Sentence Meaning}}</div>

{{Word Audio}}
{{Sentence Audio}}
<br>
{{Picture}}

{{#Notes}}
	<br>
	<div style="font-size: 20px; padding-top:12px">Note: {{Notes}}</div>
{{/Notes}}

{{#Pitch Accent Notes}}
<div style="font-size: 20px; width: fit-content; max-width:40vw; margin: auto">
	<details><summary>Pitch Accent Notes</summary>
		<br>{{Pitch Accent Notes}}
	</details>
</div>
{{/Pitch Accent Notes}}

</div>
```

**想了解音高重音的标记方法，请参阅[这个 issue](https://github.com/donkuri/Kaishi/issues/104#issuecomment-3171889366)。**

### 其他次要选项

你还可以调整一些次要选项。

#### 振假名（Furigana）

如果你想移除振假名，只需删除背面模板中的`furigana:`部分即可。

#### 其他卡片选项

你也可以随心所欲地改变卡片类型。这是 Kaishi 1.5k 的「正面模板」（Front Template）：

```
<div lang="ja">
{{Word}}
<div style='font-size: 20px;'>{{Sentence}}</div>
</div>
```

如你所见，默认只显示单词和例句。如果你想要**句子**卡片，只需删除`{{Word}}`部分，或者用`{{Sentence}}`替换它并删除其余部分。如果你想要**单词**卡片，只需删除`<div style='font-size: 20px;'>{{Sentence}}</div>`部分。如果你想要**音频**卡片，就删掉所有内容，然后添加`{{Word Audio}}`、`{{Sentence Audio}}`或两者皆加。

#### 更改字体、字号或其他样式

这是 Kaishi 1.5k 的「样式」（Styling）模板：

```
.card {
 font-family: "ヒラギノ角ゴ Pro W3", "Hiragino Kaku Gothic Pro", "Noto Sans JP", Osaka, "メイリオ", Meiryo, "ＭＳ Ｐゴシック", "MS PGothic", "MS UI Gothic", sans-serif;
 font-size: 44px;
 text-align: center;
}

img {
max-width: 300px;
max-height: 250px;
}

.mobile img {
max-width: 50vw;
}

/* This part defines the bold color. */
b{color: #5586cd}
```

你可以在[这里](https://docs.ankiweb.net/templates/styling.html)找到各种样式选项。可以看到，Kaishi 1.5k 直接在样式标签页里用的选项很少。你可以修改`font-family`来更换字体，`font-size`来调整字号，`text-align`来改变文本对齐方式（比如设为左对齐）。默认情况下，Kaishi 1.5k 会给**粗体**文字上色。修改颜色的选项是`b{color: }`。只需填入一个十六进制颜色代码或颜色名（如 `red`）即可。如果你不想要任何颜色，删掉整行`b{color: }`即可。

## 如何将 Kaishi 导入到现有牌组中？

如果你已经开始学习 Core2k 或 Tango N4-N5（或其他类似牌组），又想转而使用 Kaishi 1.5k，可以参考 [Kuuube](https://github.com/Kuuuube) 编写的以下步骤。

1.  使用 .apkg 文件正常导入 Kaishi 牌组。
2.  前往「文件 > 导出...」（File > Export...），选择「笔记（纯文本格式 .txt）」来导出 Kaishi 牌组，其他设置保持默认。
3.  删除刚刚导入的 Kaishi 牌组。
4.  选中你想并入 Kaishi 的目标牌组，点击「浏览」（Browse），任选一张卡片，按 `ctrl + a` 全选，然后点击左上角菜单的「笔记 > 更改笔记类型...」（Notes > Change Note Type...）。请确保你选中的所有笔记都属于同一种笔记类型，否则该选项可能不会出现。
5.  将笔记类型更改为 `Kaishi 1.5k`。在弹出的窗口中，确保「新」列的「Word」字段对应的是你原牌组中表示单词的字段。如果你不打算删除原牌组中任何 Kaishi 未包含的卡片，请确保其他字段也正确对应。否则，直接使用默认设置并点击「保存」（Save）。
6.  导入在第 2 步中导出的 Kaishi .txt 文件。
7.  导入时，确保「笔记类型」设置为 `Kaishi 1.5k`，「牌组」设置为你的目标牌组。如果你打算删除所有非 Kaishi 的卡片，请在「为所有笔记添加标签」选项中填入 `Kaishi`。
8.  点击「导入」（Import）。
9.  要删除非 Kaishi 的卡片，请选中你的牌组，点击「浏览」（Browse），在左侧菜单中选中该牌组，然后在搜索框末尾追加 ` -tag:Kaishi`，接着任选一张卡片，按 `ctrl + a` 全选，最后从左上角菜单进入「笔记 > 删除」（Notes > Delete）。

**如果你要导入的目标是 Core 2.3k，请参考[这个链接](https://github.com/Manhhao/anki.transfer-review-history)。**

## 我不喜欢这些图片！

完全可以理解。为这个牌组寻找 1500 张风格统一且可免费使用的图片是一项巨大的挑战（再次感谢 [liarbeast](https://github.com/liarbeast) 的付出！）。因此，许多图片与单词或例句的意境并非完美契合。这是个中肯的批评。如果你想移除图片，可以这样做：在浏览器中点击任意一张 Kaishi 卡片，打开「卡片...」编辑界面，找到「背面」模板，然后将里面的`{{Picture}}`字段删除即可。或者，你也可以直接用以下代码替换整个模板：

```
<div lang="ja">
{{furigana:Word Furigana}}

<!-- This part enables pitch accent.

{{#Pitch Accent}}
	<br><div style='font-size: 24px'>{{Pitch Accent}}</div>
{{/Pitch Accent}} 

-->

<div style='font-size: 25px; padding-bottom:20px'>{{Word Meaning}}</div>
<div style='font-size: 25px;'>{{furigana:Sentence Furigana}}</div>
<div style='font-size: 25px; padding-bottom:10px'>{{Sentence Meaning}}</div>

{{Word Audio}}
{{Sentence Audio}}
<br>

{{#Notes}}
	<br>
	<div style="font-size: 20px; padding-top:12px">Note: {{Notes}}</div>
{{/Notes}}

<!-- This part enables pitch accent notes.

{{#Pitch Accent Notes}}
<div style="font-size: 20px; width: fit-content; max-width:40vw; margin: auto">
	<details><summary>Pitch Accent Notes</summary>
		<br>{{Pitch Accent Notes}}
	</details>
</div>
{{/Pitch Accent Notes}}

-->

</div>
```

## 牌组的诞生故事

本牌组的诞生，源于我和 Tyogin 在 [TMW discord 服务器](https://learnjapanese.moe/join/) 上的一次讨论。我们都对当时流行的几款初学者牌组中那些恼人的缺陷感到惋惜。由于种种问题，许多初学者在使用 Core 2k 和 Tango 时常常感到困惑。Tango 牌组中包含一些生僻词，比如「ナンプラー」（一种泰国鱼露），而且很多人对牌组中充斥着大量基础短语和国家名并不感兴趣。此外，它的字段格式设计得极差，导致用户几乎无法以其预设的「句子卡片」之外的任何方式使用。而 Core 2k 虽然是模块化的，却存在不少翻译错误、图片缺失或不相关的问题，有些例句也并不实用，甚至无法准确反映单词的含义。

这些问题都非常恼人，以至于差不多每两周就有新手向我们提问。于是 Tyogin 提议，不如我们自己动手解决这些问题吧。一个小型团队就此成立。我们主要整合了来自 Core2k、Core10k、Tango N4 和 Tango N5 的数据，然后使用多种 Yomichan/Yomitan 词频词典对单词进行排序，并从中挑选了约 1500 个词。接着，我们修正了每个单词的翻译，为其挑选了最合适的例句，并对需要修改的例句进行了调整（1500 个例句中我们修正了大约 120 个）。随后，我们从 [AJT Japanese](https://ankiweb.net/shared/info/1344485230) 为那些缺少合适音频的单词获取了音高重音数据和音频，并由 Karifurai 和 cindsa 两人团队对音高重音数据进行了核对，还为有需要的单词添加了音高重音笔记。我们还裁剪了音频中的静音部分，并统一了所有音频文件的音量。此外，我们同样利用 AJT Japanese 为单词和例句生成了振假名。在此之后，我们为牌组的默认版本设计了一套简洁的、以提示为目标的句子卡片 CSS 样式。最后，多位成员对牌组进行了校对，以确保错误降到最低。

Kaishi，写作「開始」，意为「开始、开端」。我们觉得这个名字非常贴切，便定了下来。希望这个牌组能为你的日语学习之旅开启一个美妙的篇章。

## 学完这个牌组后该做什么？

如果你还没开始，现在就去[开始挖掘（mining）](https://donkuri.github.io/learn-japanese/guide/#consuming-native-content)吧。关于可用的挖掘笔记类型列表，请参阅[这里](https://github.com/donkuri/japanese-resources/?tab=readme-ov-file#mining)。

## 牌组的多语言翻译

如果你有兴趣将本牌组翻译成你的母语，请在 [GitHub 的 issue 追踪器](https://github.com/donkuri/Kaishi/issues)上提出。本牌组已被翻译成 **[俄语](https://github.com/NeonGooRoo/KaishiRu)**、**[印尼语](https://ankiweb.net/shared/info/1512066033)**、**[越南语](https://github.com/duy103zxc/kaishi-vi/releases)**、**[乌克兰语](https://github.com/maksiksq/KaishiUa)**、**[巴西葡萄牙语](https://github.com/nonsolvent/Kaishi-pt-BR)** 和 **[西班牙语](https://github.com/Dogi5/Kaishi-ESP)**。

## 致谢名单

本牌组的制作离不开以下成员的帮助：

[栗](https://github.com/donkuri/) - 总负责人，负责所有技术、翻译和校对工作

Tyogin - 总负责人，重新排序了前 200 张卡片，修改了例句，并参与校对

shoui - 校对了整个牌组，并修正了翻译

Julian - 协助添加笔记并核对部分例句翻译

karifurai - 核对了前 750 个单词的音高重音并添加了音高笔记

cindsa - 核对了后 750 个单词的音高重音并添加了音高笔记

[Kuuube](https://github.com/Kuuuube) - 建议使用 FFmpeg，并撰写了上文关于迁移卡片至 Kaishi 1.5k 的教程

[stephenmk](https://github.com/stephenmk) - 使用 Jmdict Furigana 工具修复了 Kaishi 1.5k 的振假名问题（详见 v1.3.0）

[Kaanium](https://github.com/kaanium) - 协助编写脚本，将牌组转换为手写练习版本

[Lars](https://github.com/liarbeast) - 从 [irasutoya](https://www.irasutoya.com/) 网站添加了图片

在牌组制作过程中，我们使用了以下工具：

[AJT Japanese](https://github.com/Ajatt-Tools/Japanese) - 音高重音、振假名和部分音频通过此插件生成

[FFmpeg](https://ffmpeg.org/) - 用于移除音频文件中的静音片段

[Tenacity](https://tenacityaudio.org/) - 用于编辑音频文件中的爆音

我们还从 TMW discord 服务器的许多成员那里获得了宝贵的建议，其中就包括牌组的名字。牌组中的例句则来源于 AnkiWeb 上的各种 Core 系列牌组。