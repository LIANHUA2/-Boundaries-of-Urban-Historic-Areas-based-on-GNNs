# -Boundaries-of-Urban-Historic-Areas-based-on-GNNs
#我们正在维护这个项目，目前这个版本并不代表最终版。
#
#这个项目的建立主要是为了尝试使用神经网络快速地寻找城市的历史地区，我们希望这个方法相比以前人工的方法更加简单有效。
具体的文章预计将会发表在 2024 CAD confrence 上。（还未最终确定）
#
[主]通用标准代码模块.ipynb 是项目的主程序，它是是使用Jupyter Notebook 来编写Python程序文件。您可以在jupyter上打开，更推荐使用谷歌的colab打开。
在运行全部程序之前，您需要下载构成一个图（graph）的原始数据，这里我提供中国河南开封的部分原始数据，分别是“开封点属性.csv”和“开封边属性.scv”。将它们下载之后，请在主程序中第三个代码块中正确的位置链接上这两个原始文件。如果您使用的是谷歌的colab笔记本，此时您应该就能运行这个程序了。如果您是在本地运行，可能还需要按照提示下载一些其他的第三方库，我们极力推荐您使用谷歌的colab运行。

按照顺序全部运行成功后，您在名为“获取核心区位置”的代码块下的最后一个小代码块中就可以得到计算机认为的开封城的历史城区位置分布了。如果您希望直观地观察出计算结果，需要您手动在地图上标出这些提示节点，您也可以直接在文件中直接下载我标记的结果。在文件中还包括了开封城的官方规划，至于结果是否准确就交由您来评判了。

目前这个说明也未完全写完，也尚未有英文版，实际上我正在学习使用github。

2024年3月4日 编辑
