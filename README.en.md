# Chinese Copywriting Guidelines

Chinese copywriting guidelines for better written communication.

Other languages:

- [English](README.en.md)
- [Chinese Traditional](README.md)
- [Chinese Simplified](README.zh-Hans.md)

* * *

## Spacing

> Research shows that, people adding no space between Chinese and English suffer from pathetic relationships. 70% of them are married by the age of 34, with someone they don't love; 30% of them left everything for their cats and died. Blank spaces are essential to both romance and writing.
>
> 與大家共勉之。」——[vinta/paranoid-auto-spacing](https://github.com/vinta/pangu.js)

### Place one space before/after English words

Good:

> 在 LeanCloud 上，數據儲存是圍繞 `AVObject` 進行的。

Bad:

> 在LeanCloud上，數據儲存是圍繞`AVObject`進行的。
>
> 在 LeanCloud上，數據儲存是圍繞`AVObject` 進行的。

An example of complete and correct usage:

> 在 LeanCloud 上，數據儲存是圍繞 `AVObject` 進行的。每個 `AVObject` 都包含了與 JSON 兼容的 key-value 對應的數據。數據是 schema-free 的，你不需要在每個 `AVObject` 上提前指定存在哪些键，只要直接設定對應的 key-value 即可。

Exceptions: For product and brand names, please refer to the writing format of the official definition. For example, use “豆瓣FM” instead of “豆瓣 FM”.

### Place one space before/after numbers

Good:

> 今天出去買菜花了 5000 元。

Bad:

> 今天出去買菜花了 5000元。
>
> 今天出去買菜花了5000元。

### Place one space between numbers and units

Good:

> 我家的光纖入屋寬頻有 10 Gbps，SSD 一共有 20 TB。

Bad:

> 我家的光纖入屋寬頻有 10Gbps，SSD 一共有 20TB。

Exceptions: There should not be any spacing between numbers and degrees/percentages.

Good:

> 角度為 90° 的角，就是直角。
>
> 新 MacBook Pro 有 15% 的 CPU 性能提升。

Bad:

> 角度為 90 ° 的角，就是直角。
>
> 新 MacBook Pro 有 15 % 的 CPU 性能提升。

### No additional spaces before/after punctuation in fullwidth form

Good:

> 剛剛買了一部 iPhone，好開心！

Bad:

> 剛剛買了一部 iPhone ，好開心！
>
> 剛剛買了一部 iPhone， 好開心！

### `text-spacing` to the rescue?

[`text-spacing`](https://www.w3.org/TR/css-text-4/#text-spacing-property) and [`-ms-text-autospace`](https://msdn.microsoft.com/library/ms531164(v=vs.85).aspx) provided by CSS Text Module Level and Microsoft can specify the autospacing and narrow space width adjustment of text. However it's not popular, and on other platforms such as OS X and iOS we can not use this feature. So it's better for you to keep up the habit.

## Punctuation

### Avoid duplicate punctuation

Although the punctuation usage of China mainland admits to duplicate the punctuations, the sentence may become unpleasing to the eye by doing that.

Good:

> 德國隊竟然戰勝了巴西隊！
>
> 她竟然對你說「喵」？！

Bad:

> 德國隊竟然戰勝了巴西隊！！
>
> 德國隊竟然戰勝了巴西隊！！！！！！！！
>
> 她竟然對你說「喵」？？！！
>
> 她竟然對你說「喵」？！？！？？！！

## Fullwidth and halfwidth

If you’re not familiar with fullwidth and halfwidth forms please refer to article [Halfwidth and fullwidth](https://en.wikipedia.org/wiki/Halfwidth_and_fullwidth_forms) on Wikipedia.

### Use punctuation in fullwidth form

Good:

> 嗨！你知道嘛？今天前台的小妹跟我說「喵」了哎！
>
> 核磁共振成像（NMRI）是什麼原理都不知道？JFGI！

Bad:

> 嗨! 你知道嘛? 今天前台的小妹跟我說 "喵" 了哎!
>
> 嗨!你知道嘛?今天前台的小妹跟我說"喵"了哎!
>
> 核磁共振成像 (NMRI) 是什麼原理都不知道? JFGI!
>
> 核磁共振成像(NMRI)是什麼原理都不知道?JFGI!

Exception: inline English titles of books and journals with italics, instead of fullwidth title marks.

### Use numbers in halfwidth form

Good:

> 這件蛋糕只賣 1000 元。

Bad:

> 這件蛋糕只賣 １０００ 元。

Exceptions: fullwidth numbers are acceptable for better visual alignment in graphic design.

### Use punctuation in halfwidth form for English sentences

Good:

> 賈伯斯那句話是怎麼說的？「Stay hungry, stay foolish.」
>
> 推薦你閱讀 *Hackers & Painters: Big Ideas from the Computer Age*，非常地有趣。

Bad:

> 賈伯斯那句話是怎麼說的？「Stay hungry，stay foolish。」
>
> 推薦你閱讀《Hackers＆Painters：Big Ideas from the Computer Age》，非常的有趣。

## Nouns

### Capitalize properly

Capitalization is a matter of English, which is beyond the scope of this wiki. Here we exemplify some typical scenarios.

Good:

> 使用 GitHub 登錄
>
> 我們的客戶有 GitHub、Foursquare、Microsoft Corporation、Google、Facebook, Inc.。

Bad:

> 使用 github 登錄
>
> 使用 GITHUB 登錄
>
> 使用 Github 登錄
>
> 使用 gitHub 登錄
>
> 使用 gｲんĤЦ8 登錄
>
> 我們的客戶有 github、foursquare、microsoft corporation、google、facebook, inc.。
>
> 我們的客戶有 GITHUB、FOURSQUARE、MICROSOFT CORPORATION、GOOGLE、FACEBOOK, INC.。
>
> 我們的客戶有 Github、FourSquare、MicroSoft Corporation、Google、FaceBook, Inc.。
>
> 我們的客戶有 gitHub、fourSquare、microSoft Corporation、google、faceBook, Inc.。
>
> 我們的客戶有 gｲんĤЦ8、ｷouЯƧquﾑгє、๓เςг๏ร๏Ŧt ς๏гק๏гคtเ๏ภ、900913、ƒ4ᄃëв๏๏к, IПᄃ.。

Attention: When a webpage needs to conform to the overall visual style by displaying all uppercase/lowercase letters, please, in HTML,  type those letters following standard case formatting; and define the appearance style via `text-transform: uppercase;`／`text-transform: lowercase;`.

### Avoid jargons

Good:

> 我們需要一位熟悉 TypeScript、HTML5，至少理解一種框架（如 React、Next.js）的前端開發者。

Bad:

> 我們需要一位熟悉 Ts、h5，至少理解一種框架（如 RJS、nextjs）的 FED。

## Dispute

The following usages comprise of personal characteristics. As such, from the perspective of copywriting guidelines, they are **still correct** regardless of whether they comply with the following rules.

### Add extra spaces before/after links

Usage:

> 請 [提交一个 issue](#) 並分配给相關同事。
>
> 訪問我們網站的最新動態，請 [點擊這裡](#) 進行訂閱！

compared with:

> 請[提交一个 issue](#) 並分配给相關同事。
>
> 訪問我們網站的最新動態，請[點擊這裡](#)進行訂閱！

### Use corner brackets for Chinese Simplified

Usage:

> 「老师，『有条不紊』的『紊』是什么意思？」

compared with:

> “老师，‘有条不紊’的‘紊’是什么意思？”

## Tools

Repository | Category | Language
---------- | -------- | --------
[pangu.js](https://github.com/vinta/pangu.js) | pangu | JavaScript
[pangu-go](https://github.com/vinta/pangu) | pangu | Go
[pangu.java](https://github.com/vinta/pangu.java) | pangu | Java
[pangu.py](https://github.com/vinta/pangu.py) | pangu | Python
[pangu.rb](https://github.com/dlackty/pangu.rb) | pangu | Ruby
[pangu.php](https://github.com/cchlorine/pangu.php) | pangu | PHP
[pangu.vim](https://github.com/hotoo/pangu.vim) | pangu | Vim
[vue-pangu](https://github.com/serkodev/vue-pangu) | pangu | Vue.js (Web Converter)
[intellij-pangu](https://plugins.jetbrains.com/plugin/19665-pangu) | pangu | Intellij Platform Plugin
[autocorrect](https://github.com/huacnlee/autocorrect) | autocorrect | Rust, WASM, CLI tool
[autocorrect-node](https://github.com/huacnlee/autocorrect/tree/main/autocorrect-node) | autocorrect | Node.js
[autocorrect-py](https://github.com/huacnlee/autocorrect/tree/main/autocorrect-py) | autocorrect | Python
[autocorrect-rb](https://github.com/huacnlee/autocorrect/tree/main/autocorrect-rb) | autocorrect | Ruby
[autocorrect-java](https://github.com/huacnlee/autocorrect/tree/main/autocorrect-java) | autocorrect | Java
[autocorrect-go](https://github.com/longbridgeapp/autocorrect) | autocorrect | Go
[autocorrect-php](https://github.com/NauxLiu/auto-correct) | autocorrect | PHP
[autocorrect-vscode](https://marketplace.visualstudio.com/items?itemName=huacnlee.autocorrect) | autocorrect | VS Code Extension
[autocorrect-idea-plugin](https://plugins.jetbrains.com/plugin/20244-autocorrect) | autocorrect | Intellij Platform Plugin
[jxlwqq/chinese-typesetting](https://github.com/jxlwqq/chinese-typesetting) | other | PHP
[sparanoid/space-lover](https://github.com/sparanoid/space-lover) | other | PHP (WordPress)
[sparanoid/grunt-auto-spacing](https://github.com/sparanoid/grunt-auto-spacing) | other | Node.js (Grunt)
[hjiang/scripts/add-space-between-latin-and-cjk](https://github.com/hjiang/scripts/blob/master/add-space-between-latin-and-cjk) | other | Python
[hustcc/hint](https://github.com/hustcc/hint) | other | Python
[n0vad3v/Tekorrect](https://github.com/n0vad3v/Tekorrect) | other | Python

## Examples of “Who is doing this?”

Website | Copywriting | UGC
------- | ----------- | ---
[Apple China](https://www.apple.com/cn/) | Yes | N/A
[Apple Hong Kong](https://www.apple.com/hk/) | Yes | N/A
[Apple Taiwan](https://www.apple.com/tw/) | Yes | N/A
[Microsoft China](https://www.microsoft.com/zh-cn/) | Yes | N/A
[Microsoft Hong Kong](https://www.microsoft.com/zh-hk/) | Yes | N/A
[Microsoft Taiwan](https://www.microsoft.com/zh-tw/) | Yes | N/A
[LeanCloud](https://leancloud.cn/) | Yes | N/A
[V2EX](https://www.v2ex.com/) | Yes | Yes
[Apple4us](https://apple4us.com/) | Yes | N/A
[Ruby China](https://ruby-china.org/) | Yes | Yes
[少數派](https://sspai.com/) | Yes | N/A

## References

- [Guidelines for Using Capital Letters - ThoughtCo.](https://www.thoughtco.com/guidelines-for-using-capital-letters-1691724)
- [Letter case - Wikipedia](https://en.wikipedia.org/wiki/Letter_case)
- [Punctuation - Oxford Dictionaries](https://en.oxforddictionaries.com/grammar/punctuation)
- [Punctuation - The Purdue OWL](https://owl.english.purdue.edu/owl/section/1/6/)
- [How to Use English Punctuation Correctly - wikiHow](https://www.wikihow.com/Use-English-Punctuation-Correctly)
- [格式 - openSUSE](https://zh.opensuse.org/index.php?title=Help:%E6%A0%BC%E5%BC%8F)
- [Halfwidth and fullwidth forms - Wikipedia](https://en.wikipedia.org/wiki/Halfwidth_and_fullwidth_forms)
- [引號 - 維基百科](https://zh.wikipedia.org/wiki/%E5%BC%95%E8%99%9F)
- [Interrobang - Wikipedia](https://en.wikipedia.org/wiki/Interrobang)

## Forks

The usage of forked projects may differ from this project.

- [mzlogin/chinese-copywriting-guidelines](https://github.com/mzlogin/chinese-copywriting-guidelines)
