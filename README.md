# Couplets_with_seq2seq
train couplets with seq2seq 【对联】

# 鉴于github不能上传大于25M的文件，对联数据集放到 AIStudio 上面了。链接：https://aistudio.baidu.com/aistudio/datasetdetail/110057

对联数据集的原版我是在 https://github.com/wb14123/couplet-dataset 下载的，之后我将test与train中的数据合并，之后发现里面有14条是存在问题的。

问题的表现为： 使用sublime text3打开会显示为“方括号包裹问号”，使用Python的split()函数进行分词会显示为“\ue...”.

合并的数据集是test+train（数据顺序），有问题的14条数据为 badid=[103807, 176565, 257631,265657, 358953, 489089, 558495, 561447, 707870, 710226, 236151,517221,549031,707322]。其中前10个问题为上联，后4个问题为下联。

