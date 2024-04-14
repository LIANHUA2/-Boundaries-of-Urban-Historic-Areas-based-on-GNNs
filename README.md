# -Boundaries-of-Urban-Historic-Areas-based-on-GNNs
#We are maintaining this project, and the current version does not represent the final version.
#
#The establishment of this project is mainly to try to find the historical area of the city quickly by using neural network. The author hopes that this method is simpler and more effective than the previous manual method.
The specific article is expected to be published in 2024 CAD confrence. (Not yet finalized)
#
[主]通用标准代码模块.ipynb is the main program of the project.It uses Jupyter Notebook to write Python program files. You can open it on jupyter, and it is recommended to use Google's colab to open it.
Before running all the programs, you need to download the original data that constitutes a graph. Here I provide some original data of Kaifeng, China.“开封点属性.csv” and “开封边属性.scv”。After downloading them, please link the two original files in the correct position in the third code block in the main program.If you are using Google's colab notebook, you should be able to run this program at this time. If you are running locally, you may need to download some other third-party libraries as prompted.
After running successfully in sequence, you can get the location distribution of Kaifeng's historical city in the last small code block under the code block named "获取核心区位置".
If you want to visually observe the calculation results, you need to manually mark these prompt nodes on the map, or you can directly download the results marked by me in the file. The official planning of Kaifeng City is also included in the document.

April 2(nd), 2024 

“[主]通用标准代码模块。ipynb”是该项目的主程序。它使用Jupyter Notebook编写Python程序文件。可以在jupyter上打开，建议使用谷歌的colab打开。在运行所有程序之前，您需要下载构成graph的原始数据。这里我提供一些中国开封的原始数据:"开封点属性.csv“和”开封边属性.scv。

下载后，请将两个原始文件链接到主程序中第三个代码块的正确位置。如果您使用的是谷歌的colab笔记本电脑，此时应该可以运行该程序。如果您在本地运行，您可能需要根据提示下载一些其他第三方库。

按顺序运行成功后，您可以在名为“获取核心位置”的代码块下的最后一个小代码块中获得开封历史城市的位置分布获取核心区位置".如果你想直观地观察计算结果，你需要在地图上手动标记这些提示节点，或者你可以直接在文件中下载我标记的结果。文件中还包括开封市的官方规划。

2024年4月2日

#
"[副]豪斯多夫距离相似率标准代码模块" is a module for detecting the similarity between the Urban Historic Area boundary computed by the GNN and the actual Urban Historic Area boundary published by the government. Please link the files "潮州计算结果.png" and "潮州真实.png" to image1 and image2 respectively in the third code block "#加载图像", and then run the code blocks in order to calculate the "Hausdorff distance similarity ratio" between the GNN's computed Urban Historic Area boundary for Chaozhou, Guangdong, and the official Urban Historic Area boundary published for Chaozhou.

The Hausdorff distance similarity ratio is a method for measuring the similarity of spatial distributions between two sets of points.

April 14(nd), 2024

“[副]豪斯多夫距离相似率标准代码模块”是检测GNN计算出的历史城区界线与现实中政府公布的历史城区界线相似城区的模块。请将文件“潮州计算结果.png”与“潮州真实.png”分别链接到第三个代码块“#加载图像”中的image1与image2中，然后按顺序运行，就可以计算出GNN对广东潮州的历史城区界线计算结果与潮州官方公布的历史城区界线的“豪斯多夫距离相似率”。

豪斯多夫距离相似率（HAUSDORFF DISTANCE-SIMILARITY RATIO）是一种衡量两个点集空间分布相似程度的方法。

2024年4月14日
