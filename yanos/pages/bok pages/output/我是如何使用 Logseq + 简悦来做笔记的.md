> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/561093847)

> 这是简悦资深用户 lyserenity 使用 Logseq + 简悦实现的一套笔记方案，希望可以对其他用户一些借鉴。

视频
--

<video src="https://vdn6.vzuu.com/HD/6c190332-2b44-11ed-b3ed-86559f0a3251-v8_t121-wjdVQOZaXp.mp4?pkey=AAVIxUayt6PMfRhDCHzAhMyES2en3NVAZc7ZG5WvsT6eL8BMlvrOTGbnBP1TEIPPJaYyicGm7OefIoCDxC1H65Xz&c=avc.8.0&f=mp4&pu=e59e796c&bu=1513c7c2&expiration=1711297136&v=ks6&pp=ChMxNDAxNjIzODY1NzM5NTc5MzkyGGMiC2ZlZWRfY2hvaWNlMhMxMzY5MDA1NjA4NTk5OTA0MjU3PXu830Q%3D&pf=Web&pt=zhihu" control></video>

![](https://picx.zhimg.com/v2-5f830e70939cdbc01b6f84c076fc6d85.jpg?source=382ee89a)00:34

前言
--

身处网路时代，对于来自网路的文章与信息，「精读」──标注和笔记，抑或「精致收藏」，一直是个议题。

### 精致收藏

一开始觉得文章无需「精读」，毕竟当下的标注日后可能毫无价值，抑或忽视的地方有机会日后成宝，不如做好收集，必要时加上备注以利寻找即可。

为了达到完美收藏的目的，我试过 Pocket、Instapaper、[http://Raindrop.io](http://Raindrop.io) 和 Notion 等等，也因为持续在 Inoreader 阅读来自 RSS 源的文章，用过以标星的方式保存条目；更进一步也尝试经由「自动化」──用 Zapier 与 IFTTT，将链接转发到其他收藏工具。

经长年实践，惊觉网页信息多如过江之鲫，文中的只字片语在脑海里仿佛蒙上了薄纱，需要时却遍寻不见其真容，如鲠在喉，悔不当初为何不详实笔记。

在某个阴雨绵绵的下午，我打开了各大工具的收藏夹，在「漫漫长页」里，一则一则地舍断离了。

我不是个有「收藏趣 」的人，根据不完全记忆统计，最终不过清理了约 600 多则「无用」——无法妥善利用的条目，只能说在「精致收藏」这条路上，我尽力过，且证明不适合。

### 精读

从网路截取下来的内容，如果没有与其他笔记系统整合的机制，信息就成了「孤岛」。

每个人阅读的思维与方法都不一样，对于一些「能力」很强悍的人而言，碎片化的信息可以直接在「脑袋」里联结成完整的数据库；而我对于「知识」的态度则是不背诵不强求，只希望在想查询的时候，可以快速地唤醒「记忆」。

在网页阅读的部分，我最终选择「一气呵成」的记录方法──文章分类、基本的笔记、标签和标注内容的「重构」必须一步到位，非必要日后不进行二次整理，并且「碎片」能有效率地整合在一起。

虽然口口声声说要「精读」，但在很长的时间里从没认真地执行这件事──我一直没能找到合适的笔记工具；直到最近── Logseq 和带有 EJS 引擎的简悦模板横空出世，「笔记工具」与「网页阅读与标注」在我心中才算真正到位。

以下分别谈下为何选择 Logseq 和「简悦」。

### Logseq

Notion 曾经一度是「知识库」的主力笔记，后来几经挣扎，Notion 最终变成了辅助软件，成為项目管理和数据的集中地。

聊个在 Notion 笔记的「挣扎」经验：我在阅读一本关于「行为」的书籍后，内心澎湃，惊为天人，遂为此书新建笔记，记录下某章某节「海马回」一词；之后的某日，我在关于大脑的科普文章中，又读到「海马回」的相关知识，决定新建一则同名笔记来保留信息；但却也心生疑惑──我该如何连结这两个不同来源的笔记？建立反向链接是个方法，但笔记依旧分散，查看内容需要要在笔记间反复横跳，可行吗？

几乎是同一时间， Notion 发布 Synced blocks，这本书的前三章笔记采用了新上线的功能；想当然耳，结局是心得笔记停摆了，一方面是这么做太累，时间基本都浪费在新建笔记和跳转上，另一部分则是我卡在到底是「书籍」同步给「海马回」，还是该「反向」同步回去；更有甚者，「额叶皮质」后来加入了「海马回」的相关阵营，同步问题变成了「while true」，无限循环。

需要解释一下的是，我之所以选择 Logseq 而不是更成熟的 Obsidian ，仅因为前者支持 emacs 里的 org-mode，而后者需要外挂；虽然 .org 比起 .md 更鲜为人知，各种应用也较为限缩，但多款的 md 格式笔记工具在适配上有所微调，考量到学习与「搬家」亦所费不赀。

身为轻度的 emacs 用户，蓦然回首，发现 .org 于我而言，进可攻（长期使用 Logseq），退可守（回到 emacs 上使用，或导出各种格式的文件），虽死板却不失稳定。

### SimpRead

再谈网页阅读与标注。

一度最符合要求，也是我用过最久的是 Notion 搭配非官方浏览器扩展「Save to Notion」，这组合将高亮与笔记整合在一起；一些对「排版」有特殊需求的网页文章或笔记，Notion 依旧为一时之选。

> Notion 是真漂亮，排版也相对容易；事实上，Notion 的优化与功能迭代十分频繁，社群的活动也热络得多。

简悦最打动我的不是「专注阅读」或「离线快照」，而是「定制导出」。

作为一个网页阅读与标注扩展，简悦在跟其他笔记软件的整合算得上非常完整了，这点在眼花缭乱的「服务」选项页里可见一斑，尤其是定制导出，在模板的设计过程中，头发都多掉了一缕；可惜的是，实际使用后依旧觉得「个人化」的程度不足，顶多利用简悦进行阅读与简单的标注，而内置的标签、笔记、内部引用和反向链接等功能，都处于试用但没落实的阶段。

幸好简悦升级后的模板有了 EJS 引擎支持后，这个「窟窿」终被填补上了。

顺带一提，强烈建议简悦的用户阅读「[简悦 + SimpRead Unread Sync + Obsidian 打造第二大脑「养成游戏」](https://github.com/Kenshin/simpread/discussions/3999)」这篇文章。

我虽然不是 Obsidian 的用户，但在拜读这篇教程文后获益良多，即便自诩是「简悦 」用户里的「老人」，但仍在读到关于简悦的基本概念后豁然开朗；如果是 Obsidian 用户，那这篇从工作流程到模板，都会给人新的启发！

工作流程
----

不管需不需要精读，对于决定要保留全文的文章，我会先用 [Live Editor](https://simpread.ksria.cn/plugins/details/y8Mai5IBwN) 调整内容，其次进行标注，最后再存成离线 HTML。

这节分为：

*   标注方法
*   关于标注
*   实际应用
*   Logseq 及简悦的整合应用

需要特别说明的是，由于模板一共 130 行，对于细节不多作说明，会在文末附上完整的内容与扩展及软件的相关设置。

### 前期准备

本文使用的相关软件及插件如下：

*   [OverflowCat/logseq-simpread: The official Logseq plugin of SimpRead.](https://github.com/OverflowCat/logseq-simpread)：Logseq 的插件，可以从 marketplace 安装

感谢 Logseq 有 OverflowCat 这样的高端用户，否则 Logseq 始终存在个「点击简悦的 deeplink 跳转浏览器」的缺憾（难道我会告诉你：每次一跳浏览器我就会分心逛起别的网站的事吗）。

*   简悦扩展
*   [Markdown 模板辅助增强](https://simpread.ksria.cn/plugins/details/HD9GmoatXd)
*   [导出 org-mode](https://simpread.ksria.cn/plugins/details/etyod6A5ZT)
*   [同步助手](http://ksria.com/simpread/docs/#/Sync)

### 关于标注

为了达到「精读」的目的，需要充分利用了标注面板内的每一项功能：

**高亮的颜色**

与利用荧光笔划重点大抵是同样的思维，但考虑到 emacs 上的 org-mode 没办法实时渲染 html 的语法，所以在模板里是用符号注记（ '','=!=','', '=:=', '=≡=', '=‼='）来替代。

**高亮的样式**

简悦一共内置 4 种样式，其中 3 个作为标题 h1-h3，最后一个用于高亮一些「虽然高亮了，但导出会忽略掉」的文字。 利用「标题」的层级属性，表达标注文本间的从属关系、相关性和因果关系。 此外，图片跟代码块的标注只有颜色的区别，而**没有**「样式」可供选择，故这两种形式的标注是用高亮的颜色的序列作为标题层级。

**备注**

![](https://pic3.zhimg.com/v2-2b2c636fe969f7aea0913b9380871856_r.jpg)

第一行：标签

简悦自带的标签有层级分类的性质，使用上往往需要预设逻辑，故另辟区域记录。

虽然统称「标签」，使用上是将「知识点」和「关键字」作为关注程度多至寡的光谱两端。

标签在多数的笔记工具里因赋予特殊语法与功能，所以用法偏向「知识点」，而「关键字」属于一般注记；例如：使用 Notion 是提示**此篇文章的重点**，而用 #Notion 则表示需要关注的「议题」。

我将标签依标记语法的不同，划分成： [[tag]]、#tag、 tag 三个类型，前两个是 Logseq 特有的标签，其中的区别可参考[这篇文章](https://aryansawhney.com/pages/page-links-vs-tags-in-logseq/)，在此不赘述；最后一个意义上更近似于关键字：

*   [[name]] 属于「知识点」，信息需要琢磨，会有单独的文档汇整笔记。
*   #name 属于弱需求的类型，不一定会有单独的笔记，作为「观察重点」，性质落在「知识」与「重点」中间。
*   name 属于「重点、关键」，但没有关注的需求，仅为作为提示之用。

因为用「- tags ::」这样的语法纪录，故万一某日，「Notion」变成了知识点，只要利用寻找替代的功能，随时可以转换，反之亦然。

第二行：标题

可在第二行对标注的文本加上「核心」说明，后文会有实际应用。

第三行：笔记

第三行及其以下方为备注，可以记录感想或做笔记。

**内置的标签**

![](https://pic1.zhimg.com/v2-a294a086a88160a39a5a5c6f36d67054_b.jpg)

将简悦内置的标签「功能」化：用以文章分类、代码块语法渲染和一般性标签（少用）。 因而模板里有一大部分是在处理内置标签的「分门别类」，每个人的使用方法都不一样，仅作参考。

稍后读的元数据里也有标签与备注，但用法与标注的部分大同小异，唯一差异是备注没有「标题」的需求，笔记直接从第二行开始。

### **实际应用**

![](https://pic4.zhimg.com/v2-729921f47cc8a5ea2d6f78ef930e8747_r.jpg)

*   以图中 ❶ 为例 「特指环境温度 > 身体温度时」在原文中是以脚注的形式存在，如果高亮「想要降低身体核心温度，就...」并把脚注作为这段的标题，笔记就会精简很多。
*   图中 ❷ 是个完整的示例 标签的 #card 在 Logseq 里是功能性标签──「闪卡」，约略等于简化版的「Anki」；如果考虑把简悦的内置标签纳入 #todo ，那在 Logseq 里，这篇文章还可以往 GTD 迈进一步。

建议，不妨把 #card 当作提醒，也是不错的选择。

**Logseq 与简悦的整合应用**
-------------------

### **Logseq: 维护一分来自简悦的文章阅读列表**

利用 Logseq 的高级查询 (query) 功能，把所有文章集结成一个表格，方便日后寻找或查看。

![](https://pic2.zhimg.com/v2-506183518ab743ba6e5f7cfb5c14118d_r.jpg)

Logseq 的 query 很强大但也略有难度，本文是利用模板里的元数据（:source: Simpread）来作为查询的依据，建议到官方文档与用户们分享的教程一观：

*   [Contents](https://docs.logseq.com/#/page/Contents)
*   [OKR + GTD + Note => Logseq · 构建我的被动收入](https://www.bmpi.dev/self/okr-gtd-note-logseq/)
*   [datalog/Intro to Datalog](https://qwxlea.github.io/#/page/datalog%2Fintro%20to%20datalog) 属于更基础的教程，如果一点基础都没有的人，可以先看这篇。
*   [Logseq Graph Query Service](https://frosty-cherry-9258.fly.dev/) 在线测试网站，可以用来练习。

### **logseq-simpread 插件**

OverflowCat 发布了 Logseq 端的 logseq-simpread 插件──该插件会劫持跟简悦相关的链接：

*   http://localhost:7026/unread/{{idx}}?embed=logseq 该链接展开正文（离线文件）
*   http://localhost:7026/unread/{{idx}}?embed=logseq#id={{an_id}} 该链接展开正文，并跳转对应的标注

**注意**

*   「[Logseq Plugin: SimpRead Sync](https://github.com/Kenshin/simpread/discussions/4220)」这篇教程有完整的视频展示，在此不多作说明。
*   关于 {{idx}} 和 {{an_id}} 的用法，请见教程：[Markdown 模板辅助增强](https://github.com/Kenshin/simpread/discussions/3725)

点击链接后会在右侧的 sidebar 展开全文，加上简悦实时同步标注的功能，不管是增加、删除或编辑标注，都可以直接在 Logseq 里操作，直观许多。

要稍微吐槽的部分：如果是简悦的沉浸式用户，应该可以发现从 Logseq 开启的标注面板较一般阅读模式内置的少了「开启拖拽排序」的功能。

> 该「问题」已请教过简悦的作者，其表示拖拽功能移植上难度颇高。

前文所述，这套标注流程有较为严谨的顺序关系，导出后所增加的标注只会出现在笔记的底部，可能会破坏了标注间的相关性。

目前的解决方法有两种：

1.  在 Logseq 里直接拖拽「增加的标注」到指定的位置。但因为简悦对于每次的修改都会重写文件，除非有把握这是最后一次变动，否则「拖拽」的步骤理所当然会需要一再重复。
2.  开启原文链接，进入阅读模式对标注重新排序，然后再执行导出，覆盖标注文件。

在模板稳定后，新文章几乎不需要调整标注；毕竟当采取「第一次标注即一次到位」的方法后，增加标注的情况减少，而删除与修改并不会造成这问题，故影响不大。

### **关于笔记间的联动**

Logseq 相较于 Obsidian 有个比较「致命」的缺点，就是无法手动定制 ID。

[此篇文章](https://github.com/Kenshin/simpread/discussions/3999)的「简悦标注系统的应用」中有提到，Obsidian 可以经由模板预设的 Block ID，引用指定的「笔记块」到别的笔记里。

然而，ID 在 Logseq 里是内部机制生成的，指定不生效果，这导致 Logseq 如果想要达到和 Obsidian 一样的功能，稍后读跟标注的元数据都不能变动，否则因引用而生成的 ID 会被简悦重新生成的页面覆盖掉。

若有笔记的需求：

1.  在标注面板的备注里完成
2.  使用双链或标签 例如：如果觉得「热射病」是个重点，可以用 [[ 框住关键字或加上 # 变成标签。 当鼠标悬停在标签上方，就可以直接在悬浮窗口笔记；若点开链接，页面下方会出现 Linked Refrencee 和 Unlinked Refrencee ，所有相关的记录都会呈现在这两个区块里。

Logseq 最美好的地方：一个「关键字」种子，在零碎的片段点点滴滴汇集之后，长成了一棵完整的「知识树」。

在工具齐全后，标注过的文章从累计一年多的 92 飙升到 125 篇，我终于开始「精读」文章之路，摆脱了「精致收藏」的魔咒。

**模板**
------

先附上各插件的设置，最后才是模板

### **插件选项：简悦端**

下图包括

*   Markdown 模板辅助增强
*   导出 Org-Mode 选项

![](https://pic3.zhimg.com/v2-7e479310aa57a4c67776f5a248e605da_r.jpg)

### **简悦・同步助手**

![](https://pic3.zhimg.com/v2-ac53d4e14da600d23653719c49a86266_r.jpg)

虽然简悦无法将网页快照跟标注分别存放，但可以就文件后缀区分项目，放在不同的文件夹内：

*   快照（html）： SimpRead 的文件夹
*   标注（org）： Logseq 的笔记夹

### **设置：Logseq 端的插件── logseq-simpread**

点击 http://localhost:7026/unread/{{idx}}?embed=logseq 开启页面，会看到上方出现设置的图标（如下图左上角），按需求填写。

![](https://pic3.zhimg.com/v2-e47f767a1fdb569e534009d61d458c9a_r.jpg)

注意

*   如果稍后读的文章已经累积到一定数量，建议谨慎使用「生成全部」，有卡死 Logseq 的风险
*   根据反复测试的经验，如果设置图标忽然不见，可以试试重启同步助手

### **模板**

注意事项（针对 org-mode 的用户）：

*   对于 base64 编码的图片 Logseq 只能使用 markdown 的语法，用 org-mode 的语法会卡死 Logseq。 如果是在 emacs 上使用 org-mode 的用户，需要修改模板，或是写脚本转化成一般格式。
*   模板虽然已有针对 html 语法转换成 org-mode，但也可能有尚未覆盖到的部分

```
<% //s-sr-unread
const refs = ((unread.refs === undefined)? false : unread.refs.split('\n'));
const tags = unread.tags;
const ar_note = unread.note.split(/\n/);

const regex = /\d\d\d\/\d\d/;
let jd_tags = tags.filter(x => x.match(regex)).map(x => String(x).replace(/(.+)/, "[[$1]]"));
let jd_tags2 = tags.filter(x => !x.match(regex)).map(x => String(x).replace(/(.+)/, "#$1"));
let jd = (jd_tags)? jd_tags.join(" ") : "";
let fileTags = (jd_tags2)? jd_tags2.join(" ") : "";

-%>
:PROPERTIES:
:ROAM_REFS: {{host}}
:CUSTOM_ID: sr-{{idx}}-{{timestamp}}
:TIMESTAMP: [{{create|yyyy-mm-dd ddd}}]
:JD_Index: <%= jd %>
:SR_Index: {{idx}}
:Source: SimpRead
:END:
#+TITLE: {{title}}@annote

<% if ( fileTags || ar_note[0] ) { -%>
- Tags :: <%= fileTags %><%= (ar_note[0] == '')? '' : ' ' + ar_note[0].trim().split(/\s+/).map(x => x).join(' ') %>
<% } -%>
- Created :: [[{{create|yyyy-mm-dd}}]]
- Local :: [[simpread://open?type=unread&idx=<%= unread.idx %>][馃寪]] [[http://localhost:7026/unread/<%= unread.idx %>?embed=logseq][馃搩]]
- Url :: [[{{url}}][{{title}}]]
<% if ( refs != '' ) { -%>
- Reference :: <%= refs.map(x => '[[' + x + '][link_' + refs.indexOf(x) + ']]' ).join(' ') %>
<% } -%>
<% if ( unread.backlinks ) { -%>
- Backlinks :: {{backlinks}}<% //pass -%>
<% } -%>
<% if ( unread.desc ) { -%>

* Desc
#+BEGIN_QUOTE
{{desc}}
#+END_QUOTE
<% } -%>
<% if ( ar_note[1] ) { -%>
* Note :note:
<%= ar_note.slice(1,).join('\n') -%>
<% } -%>

<% for( let i = 0; i < unread.annotations.length; ++i ) { -%>
    <%_
        let annote = unread.annotations[i],
            org_tags   = annote.tags.filter(x => !x.match(/\//)),
            tags = annote.tags.filter(x => x.match(/\//)),
            note = annote.note.split('\n'),
            style = annote.style,
            id = annote.id,
            backlinks = sr_tmpl_fun.parseBakinks( annote.backlinks ),
            refs = ((annote.refs === undefined)? false : annote.refs.split('\n'));

        const is_img = (annote.type == 'img')?((/data:image\/\w+;base64,/.test(annote.text))? 'base64':'img') : false;
        const is_codeBlock = (annote.type != 'code')? false : ((tags.filter(x => x.match(/CodeSRC\/\w+/))[0])? tags.filter(x => x.match(/CodeSRC\/\w+/))[0].replace(/CodeSRC\//, "") : "shell")

        let htmlTags = { '<strong>' : " *", '</strong>': "* ", '<b>' : " *", '</b>': "* ", '<code>' : " ~", '</code>': "~ ", '<s>': " +", '</s>': "+ ", '<em>': " /", "</em>": "/ ", "<blockquote>": "#+BEGIN_QUOTE", "</blockquote>": "#+END_QUOTE" },
            replace = Object.keys(htmlTags).join('|');
        const re = new RegExp(`${replace}`,"g");
        let orgSyntax = annote.html.replace(/(?:[\r\n])/g, "").replace(/<a\s+(?:[^>]*?\s+)?href=(["'])(.*?)\1(?:[^>]*?)>(.*?)<\/a>/g, "[[$2][$3]]").replace(/\s{2,}/g, " ");
        let orgText = orgSyntax.replace(re, m => htmlTags[m] );
            // let orgText = orgSyntax.replace(/<a href="(.+?)".*?>(.*?)<\/a>/g, "[[$1][$2]]").replace(/\s{2,}/g, ' ');

        let text = annote.text;

        let colors = [ '#B4D9FB', '#ffeb3b', '#a2e9f2', '#a1e0ff', '#a8ea68', '#ffb7da' ],
        // color  = colors[ annote.color ],
            def = [ '', '=!=', '', '=:=', '=鈮?', '=鈥?'][ annote.color ]; // [ '', '=!=', '', '=DESC=', '=DEF=', '=CONCL=']

        const heading = ['** ', '**** ', '*** ', '* '],
              Hn = (!is_img && !is_codeBlock)? heading[ annote.style ] : (Array(+annote.color +1).join('*') + ' '),
              Hn_embed = '[[http://localhost:7026/unread/' + unread.idx + '?embed=logseq#id=' + id + '][锔忊Ж]]';
    -%>
<% if ( style != '1' ) { //s-style-not-1 -%>
<%- Hn + Hn_embed %><%= (def)? " " + def : "" -%>
<% if ( !is_codeBlock && !is_img && ( !note[1]) ) { //s-if-A -%>
 {{{html_format|<p>|<%- orgText %>}}}<% //remove newlines -%>
<% } else { -%>
 <%- note[1] -%>
<% } //e-if-A -%>
<%= (org_tags.length == 0)? '': ' :' + org_tags.join(':') +':' %>
:PROPERTIES:
:CUSTOM_ID: sr-{{idx}}-<%= id %>
:END:
 <%= '[fn:' + id + ']' %>
<% if ( (note && note[0].trim()) || tags.length > 0 ) { //s-tags -%>
<%- '- tags :: ' + tags.map(x => String(x).replace(/^/, "#")).join(' ') + ' ' + note[0] %>
<% } //e-tags -%>
<% if ( is_img == 'img' ) { //s-if-img -%>
#+ATTR_ORG: :width 700px
<%= '[[' + text.replace(/\.(gif|jpe?g|tiff?|png|webp|bmp).*$/i, ".$1") + ']]' %>
<% } else if ( is_img == 'base64' ) { -%>
<%= '![](' + text + ')' %>
<% } else { -%>
<% if ( annote.type == 'code' ) { //codeBlock -%>
#+BEGIN_SRC <%- is_codeBlock %>
<%- text.replace(/^(.)/gm, '  $1') %>
#+END_SRC
<% } else { //codeBlock -%>
<% if ( note[1] ) { //s-if-B -%>
{{{html_format|<p>|<%- orgText %>}}}
<% } //e-if-B -%>
<% } //codeBlock -%>
<% } //e-if-img -%>
<% if ( refs != '' ) { -%>
- refs :: <%= refs.map(x => '[[' + x + '][link_' + refs.indexOf(x) + ']]' ).join(' ') %>
<% } -%>
<% if ( backlinks ) { -%>
- backlinks :: <%= backlinks %>
<% } -%>
<% if ( note[2] !== undefined ) { -%>
<%- Array(Hn.length +1).join('*') + " 馃敄 :note:" %>
<%- note.slice(2,).join('\n') %>
<% } -%>
<% } else { //e-style-not-1 -%>
<%= annote.note %>

- logseq_link :: <%= '[[http://localhost:7026/unread/' + unread.idx + '?embed=logseq#id=' + id + '][锔忦煍梋]' %> <%= '[fn:' + id + ']' %>
<% } -%>
<% } //e-sr-unread -%>

<% if ( unread.annotations.length > 0 ) { -%>
* Footnotes
<% for( let i = 0; i < unread.annotations.length; ++i ) { -%>
    <%_
        let annote = unread.annotations[i],
            id = annote.id;
    -%>
[fn:<%= id %>] 锛?[[https://simpublish-fork.vercel.app/articles/<%= unread.idx %>#id=<%= id %>][馃敆]] [[simpread://open?type=unread&idx=<%= unread.idx %>&id=<%= id %>][馃搫]]
<% } -%>
<% } -%>
<%# v.5.3.6 %>

```

配置库
---

[简悦 · 配置库](https://zhuanlan.zhihu.com/p/572115260) 是简悦官方推出的一套针对新用户的极简配置方案，方便新用户用最快的方式使用简悦的各种高级服务，配置库内置了常用的双链笔记用法，如：Notion、Obsidian、Logseq、Roam Research，同时包含了简悦在阅读模式上的一些常规插件：Live Editor、题图、Safari 阅读模式等。

与 Loqseq 有关的配置库 [请看这里](https://zhuanlan.zhihu.com/p/577462555)。（此插件已经内置到 Logseq 配置库中）