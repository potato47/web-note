# 结构化标记

* **标题 &lt;h1&gt;**

```html
<h1>这是一级标题</h1>
<h2>这是二级标题</h2>
<h3>这是三级标题</h3>
<h4>这是四级标题</h4>
<h5>这是五级标题</h5>
<h6>这是六级标题</h6>
```

* **段落 &lt;p&gt;**

```html
<p>这是一段文字。</p>
```

* **粗体 &lt;b&gt;**

```html
<b>这是加粗的文字</b>
```

* **斜体 &lt;i&gt;**

```html
<i>这是斜体的文字</i>
```

* **上标 &lt;sup&gt;**

```html
<sup>我会变成上标</sup>
```

* **下标 &lt;sub&gt;**

```html
<sub>我会变成下标</sub>
```

> 当浏览器遇到两个或两个以上连续空格时，只讲其显示为一个空格。同样，当遇到一次换行时，浏览器也会将其看作一个空格，这一特性称为**白色空间折叠**。

* **换行符 &lt;br/&gt;**

```html
<br/>
```

* **水平线 &lt;hr/&gt;**

```html
<hr/>
```

# 语义化标记

> 有一些文本元素，它们不影响网页结构，却为所在页面添加了额外信息——这些元素称为 语义化标记。

* **加粗 &lt;strong&gt;**

```html
<strong>加粗重点</strong>
```

> &lt;strong&gt;元素的作用是表示其中的内容十分重要。默认情况下，&lt;strong&gt;元素中的内容在浏览器 中显示为粗体。

* **强调 &lt;em&gt;**

```html
<em>稍微强调一下</em>
```

> &lt;em&gt;元素起强调操作，能够细微改变语句的含义。默认情况下，&lt;em&gt;元素中的内容在浏览器中显示为斜体。

* **长引用 &lt;blockquote&gt;**

```html
<blockquote>我是一段引用文字。</blockquote>
```

> &lt;blockquote&gt;元素用来标记占用一整段的较长的引用。浏览器通常会对&lt;blockquote&gt;元素中的内容进行缩进。

* **短引用 &lt;q&gt;**

```html
<q>我是短引用。</q>
```

> &lt;q&gt;元素用来标记位于段落中的较短引用。按照惯例，浏览器理应在&lt;q&gt;元素的两侧添加引号，可是IE浏览器却不支持。不建议使用。

* **缩写词 &lt;addr&gt;**

```html
<addr title="Professor">Prof</addr>
```

> 对于界面来说没什么卵用

* **引文 &lt;cite&gt;**

```html
<cite>我是引文</cite>
```

> 浏览器会把&lt;cite&gt;元素显示为斜体。

* **定义 &lt;dfn&gt;**

```html
<dfn>我是定义</dfn>
```

* **设计者详细信息 &lt;address&gt;**

```html
<address>
  <p>
    <a href="mailto:homer@example.org">homer@example.org</a>
  </p>
</address>
```

* **内容的修改 &lt;ins&gt; &lt;del&gt; &lt;s&gt;**

```html
<p>
  It was the <del>worst</del> <ins>best</ins> idea she had ever had.
</P>
```

> &lt;ins&gt;元素用来显示已经插入到文档中的内容（下划线），&lt;del&gt;元素用来显示从文档中删除的文本（删除线 ）。

```html
<p>Laptop computer:</p>
<p><s>Was $995</s></p>
<p>Now only $375</p>
```

> &lt;s&gt;元素标识不准确或不想管却不应当删除的内容。

# 综合示例

```html
<html>
  <head>
    <title>Text</title>
  </head>
  <body>
    <h1>The Story in the Book</h1>
    <h2>Chapter 1</h2>
    <p>
      Molly had been staring out of her window for about an hour now. On her desk,
      lying between the copies of <i>Nature</i>, <i>New Scientist</i>. and all the 
      other scientific journals her work had appeared in,was a well thumbed copy 
      of <cite>On The Road</cite>.It had been Molly's favorite book since college,
      and the longer she spent in these four walls the more she felt she needed to 
      be free.
    </p>
    <p>
      She had spent the last ten years in this room,sitting under aposter with an 
      Oscar Wilde quote proclaiming that <q>Work is the refuge of people who have 
      nothing better to do</q>.Although many considered her pioneering work,unraveling 
      the secrets of the llama <abbr title="Deoxyribonucleicacid">DNA</abbr>,to be 
      an outstanding achievement.Molly <em>did</em> think she had something better to do. 
    </p>
  </body>
</html>
```

![](/assets/text-test.png)

