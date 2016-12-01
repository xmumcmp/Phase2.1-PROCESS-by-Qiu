# PROCESS-OF-WEBSITES-by-Qiu-Ruodian


##翻译网站(英翻中)搜寻结果##

### 情感词典

* [2014 Master Dictionary](http://www3.nd.edu/~mcdonald/Word_Lists.html)

### 金融专业类翻译网站 ###

* [财经金融会计字典查询-线上字典导览网](http://www.tradict.net/field_finance.php)
 * [证券暨期货中英文专业词汇检索系统 (繁)](http://www.sfi.org.tw/glossary/)
    ：由证期局及证券暨期货相关单位委托建置的网页，可利用中文查询关键词词汇、英文对照、中英文法规。
 * [证券暨期货法令判解中英法规查询系统 (繁)](http://www.selaw.com.tw/)
    ：提供中英文法规查询，包括名称、全文、发布单位与日期，不同证券暨期货的法规体系分类。

* [SCIdict学术词典](http://www.scidict.org/)
 * [商务英语词汇翻译](http://yingyucihui.scientrans.com/shangwucihui/)
     * [企业章程中英翻译数据库](http://yingyucihui.scientrans.com/shangwucihui/207_65_1.html)
     * [商业英汉词典](http://yingyucihui.scientrans.com/shangwucihui/207_65_1.html)
     * [市场专业英语翻译](http://yingyucihui.scientrans.com/shangwucihui/207_65_1.html)
     

###非专业类翻译网站

* [谷歌翻译](https://translate.google.cn/)
* [必应在线翻译](http://www.bing.com/translator/)
* [Free Translation and Professional Translaiton Services From SDL](https://www.freetranslation.com/)


##翻译网站最终决定及日后计划##

###最终选定翻译情感词典网站

* [谷歌翻译](https://translate.google.cn/)


###日后计划###

* 写出基本爬虫
  * import request
  * r = request(即提取翻译结果的url：google translate “检查”-->network-->XHR-->url)
  * 存储为csv格式，格式套用即可
* [pandas read excel](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_excel.html)
  * 用pandas读取情感词典里的words一栏
  * 存储为csv格式
* 套用爬虫
  * 用爬虫翻译情感字典单词
  * 反爬问题：在反爬出现前一段时间设置time limit-->break
* 整理
  * 整理翻译结果
  * 存储为csv格式
