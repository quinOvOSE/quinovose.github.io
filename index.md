## 记录

You can use the [editor on GitHub](https://github.com/quinOvOSE/quinovose.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/quinOvOSE/quinovose.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

### basic of Emacs
```markdown
打开文件 Ctrl x f
保存文件 Ctrl x s
查看有什么文件打开在缓冲区  Ctrl x b

保留当前屏幕 Ctrl x 1
横向切分屏幕 Ctrl x 2
纵向切分屏幕 Ctrl x 3
切换屏幕 Ctrl x o

复制 C y
选择剪切 C space 然后选中需要剪切的地方C w
如果是整行剪切 C k 


浏览器使用
code显示 M-s
前进 M-f
后退 M-b



```
### basic of Org-mode
开始工作时间 C-c C-x C-i
停止工作时间 C-c C-x C-o


### Emacs 环境配置
1. 整体环境参考 https://github.com/purcell/emacs.d
2. 配置eaf https://github.com/emacs-eaf/emacs-application-framework/blob/master/README.zh-CN.md 
3. 不能说的这么设置
    (setq eaf-proxy-type "http")
    (setq eaf-proxy-host "127.0.0.1")
    (setq eaf-proxy-port "这是对应端口")
