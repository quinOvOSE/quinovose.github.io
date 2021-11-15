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

打开终端 M-x term 


窗口字体大小变大缩小 C-x C-- or C-x C-=
```
### basic of Org-mode
```markdown

小标题向上或向下 M+up or M+down

refile: 将某个task 移动到其他任务中，首先将光标移动到该task上，然后 C+c C+w 选择对应路径 回车

开始工作时间 C-c C-x C-i
停止工作时间 C-c C-x C-o
设置截止时间 C-c C-d
ps. 截止时间上， +1d +1w +1m 等分别指日常工作，间隔为每日，每周或每月
查看每日任务 C-c a a
```

### Emacs 环境配置
1. 整体环境参考 
```markdown
    https://github.com/purcell/emacs.d
```
2. 配置eaf 
```markdown
    https://github.com/emacs-eaf/emacs-application-framework/blob/master/README.zh-CN.md 
```

3. 不能说的这么设置
```markdown
    (setq eaf-proxy-type "http")
    (setq eaf-proxy-host "127.0.0.1")
    (setq eaf-proxy-port "这是对应端口")
```
4. 配置the locate of file with org-agenda
```markdown
  (setq org-agenda-files (list "~/org-file/org_file.org"))
```
5. 切换主题颜色(dark and bright)
```markdown
M+x color-theme-sanityinc-xxxx
```

6. 配置org-agenda的view中现实前3天的tasks
```markdown
(setq org-agenda-span 3)
```
    
