### 【TGE\_Seq2Seq\_pic\_drawer】——绘图

1. 一段程序（.py）对应一张图；  
2. 文件格式：  
如：`1big_exp_EJDT_ACC.py`  
即：`tables.xlsx` 中sheet索引+代码功能  
3. 所有代码通过读取`tables.xlsx`数据绘图，请直接在`tables.xlsx`下修改数据；  
4. 图片存储于`./figure`文件夹中，部分坐标经旋转处理图片需手动保存；（通过命令保存的图片会缺失部分坐标数据。）
5. 环境依赖：Python 3.x，numpy及matplotlib库包。（Anaconda默认安装这两个库包，裸装python请在命令行下分别输入`pip install numpy`、`pip install matplotlib`安装库包。）  

---

### 【TGE\_data\_calculate】——数据统计
1. 数据集存储于`./data`文件夹下；  
2. 对数据集不同需求统计请直接修改源码，详细注释见`dataset_statistics.py`源码。

---

### 【XXX revised by ruyun】——论文
图片全部存储于`./figure`文件夹下，`【TGE\_Seq2Seq\_pic\_drawer】`中生成的图片请再次复制进该文件夹，二者并不同步。

---

### 【Excel2LaTeX-（excel插件，可以将excel内的表格自动转换成latex源码）.zip】——latex制表工具
1. 我觉得文件名说得挺明白的；  
2. 直接将`Excel2LaTeX.xla`拖拽进`Excel`，根据提示启用宏即可；  
3. 选中表格，在标题栏`加载项`中点击第一个图标，复制左侧代码直接粘贴至`bare_adv.tex`即可。
