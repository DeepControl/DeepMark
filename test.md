# 我
## 你
### 他
>Markdown语法极简,易写易读,配合有道云「即看即所得」的编辑设计实时云端同步,三重备份,多渠道分享的天然属性,为用户提供了一个更高效更聪明的书写工具
> ## 这是一个标题。
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
>
> 给出一些例子代码：
>
>     return shell_exec("echo $input | $markdown_script");

*   Red
*   Green
*   Blue


1.  Bird
2.  McHale
3.  Parish


*   A list item with a blockquote:
    > This is a blockquote
    > inside a list item.


    这是一个代码区块。

***
This is [an example](http://example.com/ "Title") inline link.

See my [About](/about/) page for details.

This is [an example][id] reference-style link.
[id]: http://example.com/  "Optional Title Here"

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].
[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"

I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].
  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"


  *single asterisks*

  _single underscores_

  **double asterisks**

  __double underscores__

  Use the `printf()` function.

  ``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

Please don't use any `<blink>` tags.

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")

![Alt text][id]
[id]: url/to/image  "Optional title attribute"

~~Mistaken text.~~

```
x = 0
x = 2 + 2
what is x
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
