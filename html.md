# HTML（超文本标记语言）

## 一个html文件整体大致结构



1. #### 声明版本

   ```html
   <!DOCTYPE html
   ```

2. #### 开头

   ```html
   <html lang="en">
   ```

3. #### 头部文件

   ```html
   <head>
   	<meta charset="UTF-8"><!--字符编码-->
   	<title></title><!--网页名称-->
   </head>
   ```

4. #### 主体

   ```html
   <body></body>
   ```

5. #### 结尾

   ```html
   </html>
   ```

   

## 标签笔记

### 标题标签(h1~h6)

```html
<h1>h1</h1>
<h1>h2</h1>
<h1>h3</h1>
<h1>h4</h1>
<h1>h5</h1>
<h1>h6</h1>
```

### 段落标签

```html
<p></p>
```

### 水平线

```html
<hr>
```

### 换行

```html
<br>
```

### 加粗

```html
<b></b>
```

### 斜体

```html
<i></i>
```

### 下划线

```html
<u></u>
```

### 有序列表

```html
<ol type="">
    <li>内容</li>
    <li>内容</li>
    <li>内容</li>
    <li>内容</li>
</ol>
```

### 无序列表

```html
<ul type="">
    <li>内容</li>
    <li>内容</li>
    <li>内容</li>
    <li>内容</li>
</ul>
```

### 自定义列表

```html
<dl>
	<dt>列表名称</dt>
    	<dd>列表内容</dd>
    	<dd>列表内容</dd>
        <dd>列表内容</dd>
        <dd>列表内容</dd>
    <dt>列表名称</dt>
    	<dd>列表内容</dd>
    	<dd>列表内容</dd>
        <dd>列表内容</dd>
        <dd>列表内容</dd>
</dl>
```

### 超链接

```html
<a href=""></a>
```

### 锚点

```html
<a href="#id">  <p id="id">跳转目标</p>
```

### 图片

```html
<img src="" title="" alt="" width="" height="" >
```

### 固定格式化（写作用的）

```html
<pre></pre>
```

## 路径

### 相对路径

```.```为当前路径

```..```上级

相对路径以当前文件所在位置为参照物

### 绝对路径

以盘符为参照路径