SegCNAWord is a library for Chinese segmentation one by one word(中文分字).

Example，代码示例：

A、

------
import seg_cn_a_word

seg_list = seg_cn_a_word.seg_cont("小明硕士毕业于中国科学院计算所，后在日本京都大学深造")
print(" ".join(seg_list))

------

B、

------
from seg_cn_a_word import SegCNAWord

seg_cn_a_word = SegCNAWord()
seg_list = seg_cn_a_word.seg_cont("小明硕士毕业于中国科学院计算所，后在日本京都大学深造")
print(" ".join(seg_list))

------

Before 中文分字: 小明硕士毕业于中国科学院计算所，后在日本京都大学深造

After 中文分字: 小 明 硕 士 毕 业 于 中 国 科 学 院 计 算 所 ， 后 在 日 本 京 都 大 学 深 造
