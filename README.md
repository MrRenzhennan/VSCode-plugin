
#### 通用插件
- [Chinese (Simplified) Language Pack for Visual Studio Code](#chinese-simplified-language-pack-for-visual-studio-code)
- [Open-In-Browser](#Open-In-Browser)
- [HTML Boilerplate](#html-boilerplate)
- [HTML Snippets](#html-snippets)
- [Auto Close Tag](#auto-close-tag)
- [Auto Rename Tag](#auto-rename-tag)
- [JavaScript(ES6) code snippets](#javascriptes6-code-snippets)
- [Prettier](#prettier)
- [Path Intellisense](#path-intellisense)
- [Bracket Pair Colorizer](#bracket-pair-colorizer)
- [Minify](#minify)
- [Change Case](#change-case)
- [Regex Previewer](#regex-previewer)
- [TODO Highlight](#todo-highlight)
- [SVG Viewer](#svg-viewer)
- [CSS Peek](#css-peek)
- [Faker](#faker)
- [Quokka](#quokka)
- [filesize](#filesize)
- [HTMLHint](#htmlhint)
- [vscode-icon](#vscode-icon)
- [Material Icon Theme](#material-icon-theme)
- [Npm Intellisense](#npm-intellisense)
- [Document this](#document-this)
- [vscode-fileheader](#vscode-fileheader)
#### Vue插件
- [Vetur](#vetur)
- [自动生成代码块](#自动生成代码块)
#### React插件
- [React/Redux/react-router Snippets](#reactreduxreact-router-snippets)
#### Markdown插件
- [Markdown Preview Enhanced](#markdown-preview-enhanced)
- [markdownlint](#markdownlint)
# VSCode-plugin
VSCode 推荐插件 及相关配置  

[https://marketplace.visualstudio.com/vscode](https://marketplace.visualstudio.com/vscode)

## 修改插件默认安装位置
vscode插件默认的安装位置是`C:\Users\用户名\.vscode\extensions`  
1.已安装 Visual Studio Code, 并且已将其添加到了环境变量 path 中  
2.打开cmd，输入code --help, 显示帮助信息  
3.`code --extensions-dir <dir>  目标路径要和vscode 同级,否则修改不生效`

## Chinese (Simplified) Language Pack for Visual Studio Code

适用于 VS Code 的中文（简体）语言包  

安装后，在 locale.json 中添加 "locale": "zh-cn"，即可载入中文（简体）语言包。要修改 locale.json，你可以同时按下 Ctrl+Shift+P 打开命令面板，之后输入 "config" 筛选可用命令列表  


## Open-In-Browser
![Open-In-Browser](http://p3.pstatp.com/large/2eca00035334d5c012af)  

由于 VSCode 没有提供直接在浏览器中打开文件的内置界面，所以此插件在快捷菜单中添加了在默认浏览器查看文件选项，以及在客户端（Firefox，Chrome，IE）中打开命令面板选项。  

>插件地址  [https://marketplace.visualstudio.com/items?itemName=coderfee.open-html-in-browser](https://marketplace.visualstudio.com/items?itemName=coderfee.open-html-in-browser)
  
  
## HTML Boilerplate
![HTML Boilerplate](http://p1.pstatp.com/large/2ed30002e6d0d872426f)  

通过使用 HTML 模版插件，你就摆脱了为 HTML 新文件重新编写头部和正文标签的苦恼。你只需在空文件中输入 html，并按 Tab 键，即可生成干净的文档结构。  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=sidthesloth.html5-boilerplate](https://marketplace.visualstudio.com/items?itemName=sidthesloth.html5-boilerplate)


## HTML Snippets
![HTML Snippets](https://i.imgur.com/VOhBvHb.gif)

智能提示HTML标签，以及标签含义

>插件地址 [https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)


## Auto Close Tag
![Auto Close Tag](https://github.com/formulahendry/vscode-auto-close-tag/raw/master/images/usage.gif)
![Auto Close Tag](https://github.com/formulahendry/vscode-auto-close-tag/raw/master/images/close-tag.gif)

自动添加HTML / XML关闭标签  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)


## Auto Rename Tag
![Auto Rename Tag](https://github.com/formulahendry/vscode-auto-rename-tag/raw/master/images/usage.gif)  

重命名一个HTML / XML标记时，会自动重命名配对的HTML / XML标记  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)


## JavaScript(ES6) code snippets
![..](https://images2018.cnblogs.com/blog/1309897/201803/1309897-20180318232417436-37242668.png)  

ES6语法智能提示，以及快速输入，不仅仅支持.js，还支持.ts，.jsx，.tsx，.html，.vue，省去了配置其支持各种包含js代码文件的时间
  
>插件地址 [https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)



## Prettier
![Prettier](http://p3.pstatp.com/large/2eca00035337e42b3698)  

Prettier 是目前 Web 开发中最受欢迎的代码格式化程序。安装了这个插件，它就能够自动应用 Prettier，并将整个 JS 和 CSS 文档快速格式化为统一的代码样式  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)


## Path Intellisense
![Path Intellisense](http://i.giphy.com/iaHeUiDeTUZuo.gif)  

自动完成文件名的Visual Studio代码插件  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

## Bracket Pair Colorizer
![Bracket Pair Colorizer](https://github.com/CoenraadS/BracketPair/raw/master/images/example.png)  

 此扩展允许使用颜色标识匹配的括号。 用户可以定义要匹配的字符以及要使用的颜色。  
 
>插件地址 [https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)


## Minify
![Minify](http://p1.pstatp.com/large/2ed100033c8077e81d7d)  

这是一款用于压缩合并 JavaScript 和 CSS 文件的应用程序。它提供了大量自定义的设置，以及自动压缩保存并导出为.min文件的选项。它能够分别通过 uglify-js、clean-css 和 html-minifier，与 JavaScript、CSS 和 HTML 协同工作。  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=HookyQR.minify](https://marketplace.visualstudio.com/items?itemName=HookyQR.minify)


## Change Case
![Change Case](http://p1.pstatp.com/large/2ed100033c7f0dbfbcda)  

虽然 VSCode 内置了开箱即用的文本转换选项，但其只能进行文本大小写的转换。而此插件则添加了用于修改文本的更多命名格式，包括驼峰命名、下划线分隔命名，snake_case 命名以及 CONST_CAS 命名等  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)



## Regex Previewer
![Regex Previewer](http://p3.pstatp.com/large/2eca00035338ebfa86bc)  

这是一个用于实时测试正则表达式的实用工具。它可以将正则表达式模式应用在任何打开的文件上，并高亮所有的匹配项。  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=chrmarti.regex](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)



## TODO Highlight
![TODO Highlight](http://p3.pstatp.com/large/2ed100033c7cb57ae591)  

这个插件能够在你的代码中标记出所有的 TODO 注释，以便更容易追踪任何未完成的业务。在默认的情况下，它会查找 TODO 和 FIXME 关键字。当然，你也可以添加自定义表达式  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)


## SVG Viewer
![SVG Viewer](http://p3.pstatp.com/large/2ecc0004e0affa776bb7)  

此插件在 Visual Studio 代码中添加了许多实用的 SVG 程序，你无需离开编辑器，便可以打开 SVG 文件并查看它们。同时，它还包含了用于转换为 PNG 格式和生成数据 URI 模式的选项。  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)


## CSS Peek
![CSS Peek](http://p3.pstatp.com/large/2ed000033cd2344d5528)  

使用此插件，你可以追踪至样式表中 CSS 类和 ids 定义的地方。当你在 HTML 文件中右键单击选择器时，选择“ Go to Definition 和 Peek definition ”选项，它便会给你发送样式设置的 CSS 代码  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)


## Faker
![Faker](http://p3.pstatp.com/large/2ed000033cd1f33e1691)  

使用流行的 JavaScript 库 – Faker，能够帮你快速的插入用例数据。Faker 可以随机生成姓名、地址、图像、电话号码，或者经典的乱数假文段落，并且每个类别还包含了各种子类别，你可以根据自身的需求来使用这些数据。  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=deerawan.vscode-faker](https://marketplace.visualstudio.com/items?itemName=deerawan.vscode-faker)


## Quokka
![Quokka](http://p9.pstatp.com/large/2ed200007a393ef62428)  

Quokka 是一个调试工具插件，能够根据你正在编写的代码提供实时反馈。它易于配置，并能够预览变量的函数和计算值结果。另外，在使用 JSX 或 TypeScript 项目中，它能够开箱即用。  

>插件地址 [https://quokkajs.com/](https://quokkajs.com/)


## filesize
![filesize](https://segmentfault.com/img/bVJ9Yf?w=1400&h=800)  

在底部状态栏显示当前文件大小，点击后还可以看到详细创建、修改时间  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=mkxml.vscode-filesize](https://marketplace.visualstudio.com/items?itemName=mkxml.vscode-filesize)


## HTMLHint
![HTMLHint](https://raw.githubusercontent.com/Microsoft/vscode-htmlhint/master/htmlhint/images/hero.png)  

HTML 代码格式检测  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint](https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint)


## vscode-icon
![vscode-icon](https://raw.githubusercontent.com/vscode-icons/vscode-icons/master/images/screenshot.gif)  

让 vscode 资源树目录加上图标，必备良品！  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)  


## Material Icon Theme
![..](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/fileIcons.png)
![..](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/folderIcons.png)  

个人认为最好的vscode图标主题，支持更换不同色系的图标，值得点出的是，该插件更新极其频繁，基本和vscode更新频率保持一致  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)  


## Npm Intellisense
![Npm Intellisense](https://github.com/ChristianKohler/NpmIntellisense/raw/master/images/auto_complete.gif)  
![Npm Intellisense](https://github.com/ChristianKohler/NpmIntellisense/raw/master/images/require_withname.gif)  

require 时的包提示（最新版的vscode已经集成此功能）  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)  


## Document this
![Document this](https://github.com/joelday/vscode-docthis/raw/master/images/demo.gif)  

`Ctrl+Alt+D` and again `Ctrl+Alt+D` 为代码插入 js 的注释模板  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=joelday.docthis](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)

## vscode-fileheader
![vscode-fileheader](https://github.com/zhaopengme/vscode-fileheader/raw/master/fileheader.gif)  

`ctrl+alt+i` 生成顶部模板注释。  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=mikey.vscode-fileheader](https://marketplace.visualstudio.com/items?itemName=mikey.vscode-fileheader)


## Vetur
![..](https://images2018.cnblogs.com/blog/1309897/201803/1309897-20180318233925285-1751693960.png)  

Vue多功能集成插件，包括：语法高亮，智能提示，emmet，错误提示，格式化，自动补全，debugger。vscode官方钦定Vue插件，Vue开发者必备。  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=octref.vetur#overview](https://marketplace.visualstudio.com/items?itemName=octref.vetur#overview)


## 自动生成代码块
在vs code中，使用快捷键Ctrl+Shift+P打开搜索栏–>输入snippet–>选择首选项，如图： 
![..](https://img-blog.csdn.net/20180603020426978?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MjU2OTQ0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)  
打开了snippet搜索栏–>输入vue–>选择vue.json，如图  
![..](https://img-blog.csdn.net/2018060302081032?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MjU2OTQ0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)  
输入需要生成的vue组件内容  
```json
{
    "Print to console": {
        "prefix": "vue",
        "body": [
            "<template>",
            "  <div>\n",
            "  </div>",
            "</template>\n",
            "<script>",
            "export default {",
            "  data() {",
            "    return {\n",
            "    }",
            "  },",
            "  methods: {\n",
            "  },",
            "  components: {\n",
            "  }",
            "}",
            "</script>\n",
            "<style>\n",
            "</style>",
            "$2"
        ],
        "description": "创建一个自定义的vue组件代码块"
    }
}
```  
![..](https://img-blog.csdn.net/20180603022317118?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MjU2OTQ0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)  
准备完毕，现在来试一下，在src/components/中创建Test.vue文件，输入vue，然后按回车键，如图：   
![..](https://img-blog.csdn.net/2018060302192598?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MjU2OTQ0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)  
接下来就可以看到一段完整的vue组件代码被生成了，如图：   
![..](https://img-blog.csdn.net/20180603022356367?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MjU2OTQ0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)  

可根据自己的需求来定制vue，当然也可以创建其它的代码块。


## React/Redux/react-router Snippets
![React/Redux/react-router Snippets](https://github.com/discountry/vscode-react-redux-react-router-snippets/raw/master/images/screenshot.gif)  

React/Redux/react-router语法智能提示 代码模板  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=discountry.react-redux-react-router-snippets](https://marketplace.visualstudio.com/items?itemName=discountry.react-redux-react-router-snippets)


## Markdown Preview Enhanced
![Markdown Preview Enhanced](https://user-images.githubusercontent.com/1908863/28495106-30b3b15e-6f09-11e7-8eb6-ca4ca001ab15.png)  

实时预览markdown，markdown使用者必备  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)


## markdownlint
![markdownlint](https://images2018.cnblogs.com/blog/1309897/201803/1309897-20180318232941526-1059482055.png)  

markdown语法纠错  

>插件地址 [https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

