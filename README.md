# cnsplit

中文分词，基于N-short路径，中科院多层隐马模型算法，支持gb2312。

## 功能介绍
自定义词典导入
人名识别
地名识别
未登录词识别
词性标注

##API简介
int cnsplit_init(const char home, const enum DEBUG_LEVEL level);
void cnsplit_uninit(void);
char cnsplit_process(const char src, int len);
int cnsplit_import_dict(const char file);
int cnsplit_delete_word (const char word);
int cnsplit_output_dict(const char file);


## License
MIT

Automatically exported from code.google.com/p/cnsplit
