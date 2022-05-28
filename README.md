# Awesome-research-tools

Awesome research tools!!!

欢迎结合自己的研究方向提 PR、Issue。

如果有长期缺乏维护的 paper list、library 或失效的链接、网站，敬请告知。

## 阅读、写作

### 文献管理

- [Zotero](https://zotero.org/)：免费、开源的文献管理软件，支持分组、标签、笔记、导出引文、云同步。
- [Juris-m](https://juris-m.github.io/)：基于开源的Zotero项目，有着更进一步的功能和对中文更好的支持。
- [小绿鲸SCI阅读器](https://www.xljsci.com)：集成了 PDF 翻译、笔记、收藏语料、文献管理、云阅读等功能，非常全能的一款科研工具。

<details><summary>more</summary><p>

- [papers](https://www.papersapp.com/)：待补充完善。
- [mendeley](https://www.mendeley.com/)：待补充完善。

</p></details>

### 阅读、翻译

- [DeepL翻译器](https://www.deepl.com/translator)：有时候比谷歌、百度的翻译更为智能一些。
- [知云文献翻译软件](https://www.yuque.com/xtranslator/zy/gga6xa)：带划词翻译的 PDF 阅读器，免费，可自己选择调用的翻译接口（百度、谷歌等），在阅读英文文献时非常好用。


### 语法检查、优化

- [grammarly](https://app.grammarly.com/)：能免费进行不限文本长度的语法检测，有单词替换建议等功能，付费订阅能提供更专业的建议。
- [QuillBot](https://quillbot.com/)：重写和增强句子、段落或文章（润色），部分功能收费。
- [LTex](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex)：VsCode 上的 Latex 语法插件，免费，适用于本地进行 LaTeX 写作与编译的情况。

<details><summary>more</summary><p>

- [textranch](https://textranch.com/)：单次100词以内免费，能按照需求进行一部分定置。
- [grammarcheck](https://www.nounplus.net/grammarcheck/)：免费，不限文本长度，但是很简单，只能进行一些基本的语法错误检测。

</p></details>

### 英文例句

- [linguee](https://cn.linguee.com)：DeepL 公司出品的例句搜索，支持中文搜英文。
- [linggle](https://linggle.com/)：英文搜英文，能搜到某个短语的使用数量和比例，有时候访问不上。

### 数学公式

- [AxMath](https://www.amyxun.com/)：便宜好用的国产公式编辑器，按设备永久认证，MathType 的平替（不付费虽然功能受限，但也基本够用）。
- [MathPix](https://mathpix.com/)：公式识别工具，可以使用桌面版进行快捷识别，但是每个月有次数限制（教育邮箱50次/月，其他20次/月，收费订阅可以提高数量限制），使用教育邮箱注册且只识别复杂公式的话是基本够用的。
- [latexlive公式编辑器](https://www.latexlive.com/home)：网页版的 LaTeX 公式编辑器，支持拖拽、上传、剪切板粘贴进行图片识别，支持 Physics、Mhchem 等拓展。

### 其他

- [万词王](https://wantwords.thunlp.org/)：反向词典功能非常好用，能根据一个中文词按照词性、长度、首字母等检索相近意思的英文词。
- [acronymify](http://acronymify.com/search?q)：给定关键词，对模型、算法等进行命名，非常好玩的一个工具。
- [changes](http://mirrors.ibiblio.org/CTAN/macros/latex/contrib/changes/changes.english.pdf)：用于追踪版本修订的 Latex 包，能快速地使用增加、删除、高亮、替换、备注等标注，有自带的脚本接受所有修改并移除对应的标注代码，在 Overleaf 和 TexLive 中都是自带的不必额外安装。

## 绘图、数据可视化

### 独立软件、工具
- [AxGlyph](https://www.amyxun.com/)：和AxMath同厂，平价国产精品绘图软件，支持大部分流程图、设计图、数据图的绘制，按设备收费认证。
- [visio](https://www.microsoft.com/zh-cn/microsoft-365/visio/flowchart-software)：微软的绘图办公套件，基础功能丰富，可通过Office 365订阅使用，也可以选择2016、2019等版本买断使用。
- [chart-studio](https://chart-studio.plotly.com//)：plotly 提供的在线数据图绘制网站，效果和功能不错，可以使用浏览器完成对规整数据的处理、绘制、导出，部分功能需要注册和收费。

<details><summary>more</summary><p>

- [graphviz](https://graphviz.org/)：经典的结构图、流程图绘制工具，同时也有对应 [Python 库](https://graphviz.readthedocs.io/en/stable/index.html)可以方便地使用 Python 进行绘制。

</p></details>

### Python 
> 不同库的比较可以参考 https://anvil.works/blog/plotting-in-matplotlib 。

- [matplotlib](https://matplotlib.org/)：基础的 Python 绘图库。
- [plotly](https://plotly.com/)：支持在浏览器中进行交互的绘图库，交互体验更好。
- [seaborn](https://seaborn.pydata.org/)：基于 matplotlib 的绘图库，有着更好看的配色和更简洁的接口。

<details><summary>more</summary><p>

- [pyecharts](https://pyecharts.org/)：基于百度前端图表库 echarts 的 Python 绘图库，可使用浏览器进行交互。
- [cmaps](https://www.ncl.ucar.edu/Document/Graphics/color_table_gallery.shtml)：包含各种 color map 的 Python 包，需要`pip install cmaps`，与 matplotlib 兼容。

</p></details>

### Matlab
- [FigureBest](https://www.bilibili.com/read/cv10958513)：一款基于MATLAB GUI的数据图自动美化软件，从介绍来看功能是比较丰富的，目前需要关注公众号啥的才能获取下载。

<details><summary>more</summary><p>

</p></details>

## 深度学习

### 通用

- [pytorch-lightning](https://www.pytorchlightning.ai/)：更为高级的 Pytorch 编程接口，能编写出更高质量、更简洁的 PyTorch 代码。

### 优化

- [optuna](optuna.org)：超参数优化框架，用于自动化超参数搜索，不依赖于具体使用的深度学习框架。
- [Ax](https://ax.dev/)：基于 Pytorch 的超参数搜索框架，可简单绘制超参数分析。

### NLP

- [transformers](https://huggingface.co/docs/transformers/index)：可直接调用预训练的 Transformers、BERT 等模型，基于 PyTorch。
- [SentenceTransformers](https://www.sbert.net)：Python 库，可以直接获得句子级嵌入，基于 PyTorch。
- [fairseq](https://github.com/pytorch/fairseq)：PyTorch 团队开发的 seq2seq 库，实现了较多主流模型，可以用于机器翻译、摘要等任务训练。

### GNN

- [DGL](https://www.dgl.ai/)：深度图神经网络库，支持异构图，支持 TensorFlow 和 PyTorch。
- [pytorch_geometric](https://www.pyg.org)、[tf_geometric](https://github.com/CrawlScript/tf_geometric)：相同风格的深度图神经网络库，支持异构图，分别支持 PyTorch 和 TensorFlow。

## 开放数据集

**综合数据集**

- [AMiner](https://www.aminer.cn/data/?nav=openData)：包含涉及社交网络、学术网络、知识图谱、流行病等众多领域的数据集。
- [awesome-twitter-data](https://github.com/shaypal5/awesome-twitter-data)：Twitter 相关的数据集列表。

**按数据类别、研究方向**

<details><summary>图</summary><p>

- [Open Academic Graph (OAG)](https://www.microsoft.com/en-us/research/project/open-academic-graph/)：微软提供的包含微软学术网络和 AMiner 中学术网络的学术网络图。
- [SNAP](http://snap.stanford.edu/data/index.html)：斯坦福大型网络数据集集合。
  

</p></details>

<details><summary>自然语言</summary><p>

- [the open parallel corpus](https://opus.nlpl.eu/)：一个网络翻译文本集合，包含的语言种类和领域都非常多。
- [Statistical Machine Translation](https://www.statmt.org/)：国际机器翻译大赛，每年都会放出很多较为权威的数据集，使用广泛，认可度高。但局限是内容几乎都是新闻领域，语系较多是印欧系语言。

</p></details>



## 其他工具

- [菜鸟工具：正则表达式在线测试](https://c.runoob.com/front-end/854/)：菜鸟工具的正则表达式测试，能提供语法参考，简单好用。
- [CatalyzeX](https://chrome.google.com/webstore/detail/aiml-papers-with-code-eve/aikkeehnlfpamidigaffhfmgbkdeheil?hl=zh-CN)：Chrome 插件，论文源码。
- [connected papers](https://www.connectedpapers.com/)：找引文。

<details><summary>more</summary><p>

- [RGB颜色值与十六进制颜色码转换工具](https://www.sioe.cn/yingyong/yanse-rgb-16/)：颜色的十六进制与 RGB 表示。
- [Dir Tree Noter](https://dir.yardtea.cc/)：列出文件夹树形结构，比较方便的目录展示工具，在写源码或项目相关的材料时用得上。
- [iconfont](https://www.iconfont.cn/)：阿里出品的图标库，有着丰富的图片和矢量格式的图标，可用于绘图、PPT制作等，目前免费。
- [GeoGebra - 数学教学软件](https://www.geogebra.org/)：简单好用的科研数学绘图工具，支持2D、3D的散点、几何、公式等绘制，但是有时候访问较慢。


</p></details>

## Paper List

**综合论文列表**

- [Papers with code](https://paperswithcode.com/)：公开了源码的论文，涵盖多个领域。

<details><summary><strong>按研究方向</strong></summary><p>

- 图强化学习：[Graph Reinforcement Learning Papers](https://github.com/SunQingYun1996/Graph-Reinforcement-Learning-Papers)。
- GNN：[Must-read papers on GNN](https://github.com/thunlp/GNNPapers)。
- 图表示学习（图嵌入）：[Must-read papers on NRL/NE](https://github.com/thunlp/NRLPapers)、[awesome-network-embedding](https://github.com/chihming/awesome-network-embedding)、[Representation-Learning-on-Heterogeneous-Graph](https://github.com/Jhy1993/Representation-Learning-on-Heterogeneous-Graph)。
- 信息传播（影响传播）预测：[Paper List of Information Diffusion Prediction](https://github.com/albertyang33/DiffusionPapers)、[Paper List of Deep Learning-based Information Diffusion Modeling](https://github.com/ChenNed/Awesome-DL-Information-Cascades-Modleing)。
- 社交网络影响力最大化：[awesome-influence-maximization-papers](https://github.com/geopanag/awesome-influence-maximization-papers)。
- 推荐系统：[Must-read papers on Recommender System](https://github.com/hongleizhang/RSPapers)。
- 机器翻译：[Machine Translation Reading List](https://github.com/THUNLP-MT/MT-Reading-List)。
- 知识蒸馏：[awesome-knowledge-distillation](https://github.com/dkozlov/awesome-knowledge-distillation)。
- 图自监督学习：[Awesome Self-Supervised Learning for Graphs](https://github.com/SXKDZ/awesome-self-supervised-learning-for-graphs)。
- 自监督学习：[awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning)。
- 图对比学习框架：[PyGCL](https://github.com/GraphCL/PyGCL)。

</p></details>

## Conference/Journal List

- [Top Computer Science Conferences](https://research.com/conference-rankings/computer-science)：计算机各个领域顶会会议列表及其会议时间、地点、截稿时间和影响因子。
- [Call4Papers](http://123.57.137.208/ccf/ccf-1.jsp)：CCF 推荐列表截稿日期。
- [scirev](https://scirev.org/reviews/nature-communications/?author_id=34152743&event_source=timeline&source=timeline&dt_dapp=1)：SCI 审稿数据统计网站。

<details><summary>more</summary><p>

- [WIKICFP](http://www.wikicfp.com/cfp/)：WikiCFP is a [semantic wiki](http://en.wikipedia.org/wiki/Semantic_wiki) for Calls For Papers in science and technology fields.
- [AI Conference Deadlines](https://aideadlin.es/?sub=ML,CV,NLP,RO,SP,DM)：关于AI会议的截稿时间汇总。


</p></details>

## 热知识

- Overleaf 的会员功能（无限制的历史记录非常好用）可以通过邀请指定数量的新用户解锁，在某购物平台上可以低价解锁。
- [谷歌学术](https://scholar.google.com/)搜索到的论文清单中，直接点击论文左下方的`引用`-`BibTex`可获得精简的论文 Bib 格式引用。
