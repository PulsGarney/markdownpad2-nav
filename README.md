# MarkdownPad2 Content Navigation Auto Generator

A javascript file to generate a content navigation for the document.

## How to Use

Add the content of the file **4MarkdownPad2-head.html** to MarkdownPad2's **HTML Head Editor**,
Then, Disable your Stylesheets as followed. Or just use mine(PG.css).

```
body {
    /*max-width: 960px;*/
    /*margin: 0 auto;*/
}
```

In MarkdownPad2, You can added the codes through "Menu > Tools > Options > Advanced > HTML Head Editor"

## Functions

* In the JS code, The "Book Name Mode" will be active when the param *FirstH1BookName* equals true(Pic 1) It's specially for somebody might use Markdown to write a book or something, like myself. it'll set the first title as the *Book Name* and Make it look a bit different, for example, apart it from the numbering. and as Regular Mode if it's false(Pic 2). Try it on and you'll see.

* Click the cadetblue little slider on the windows' left will collapse the whole content.

## Effect

It shall work as follow pictures, and also [Link](https://pulsgarney.github.io/markdownpad2-nav/Example.html)

### Book Name Mode

![Book Name Mode](https://pulsgarney.github.io/markdownpad2-nav/exp0.png)

### Regular Mode

![Regular Mode](https://pulsgarney.github.io/markdownpad2-nav/exp1.png)

## NOTE

*It can only reaches to 3 different levels of the content navigator or it comes errors.*



# 中文 CN 

# MarkdownPad2 自動生成目錄 JQuery 插件

## 使用方式

將 **4MarkdownPad2-head.html** 文件中的內容添加到 MarkdownPad 中的 **HTML Head 編輯器** 中，
並作如下禁用掉你的CSS，或者直接使用我的CSS（PG.css）。

```
body {
    /*max-width: 960px;*/
    /*margin: 0 auto;*/
}
```

在MarkdownPad2中，可以通过菜单->工具->选项->高级->HTML head编辑器来自动插入以上代码。

## 功能

* JS代碼中，變量 *FirstH1BookName* 等於true時啟用書名模式（見效果圖1）這是考慮到有的人可能用Markdown來寫書之類的，比如我自己，在書名模式下，第一個標題會被當成 *書名* 並應用不同的格式，並且不會計在編號中，當為False時為普通模式（見效果圖2），不明白的話試試看就清楚了。

* 點擊窗口最左邊的綠色小條可以收起整個目錄。

## 效果

效果如下圖： 示例頁：[傳送](https://pulsgarney.github.io/markdownpad2-nav/Example.html)

### 書名模式

![開啟書名模式](https://pulsgarney.github.io/markdownpad2-nav/exp0.png)

### 普通模式

![關閉書名模式](https://pulsgarney.github.io/markdownpad2-nav/exp1.png)

## 注意

**目錄只能使用到3級目錄，超出3級的話會出錯**



