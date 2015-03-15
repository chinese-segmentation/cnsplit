中文分词，基于N-short路径，中科院多层隐马模型算法，支持gb2312。

# 功能介绍 #
  * 自定义词典导入
  * 人名识别
  * 地名识别
  * 未登录词识别
  * 词性标注
# API简介 #
  * int cnsplit\_init(const char **home, const enum DEBUG\_LEVEL level);**

  * void cnsplit\_uninit(void);

  * char **cnsplit\_process(const char**src, int len);

  * int cnsplit\_import\_dict(const char **file);**

  * int cnsplit\_delete\_word (const char **word);**

  * int cnsplit\_output\_dict(const char 