# spider_shanbei

这是一个python 写的爬虫
目的是抓取[扇贝](http://www.shanbay.com/)网站上的单词书

主要为学习用途... 如有疑问或建议, 欢迎交流:

`SnowstarCyan$gmail.com` 或 `QQ: 997596439`

## 使用(example)
  
  1. 其中 html 解析使用了 Python 的 [BeautifulSoup 库][bs], 请先[安装][bs_d]:
  ```
  pip install beautifulsoup4
  ```

  [bs]: http://www.crummy.com/software/BeautifulSoup/ "BeautifulSoup"
  [bs_d]: http://www.crummy.com/software/BeautifulSoup/#Download "BeautifulSoup Download"

  2. 需要输入的参数为单词书的网址列表
  例如:(inputs:)
  ```
  http://www.shanbay.com/wordbook/100804/
  http://www.shanbay.com/wordbook/100810/
  http://www.shanbay.com/wordbook/100813/
  ```
  
  
  返回格式大概是这样(outputs:)
  ```
  人教版高中英语必修1
  
  Unit 1
  
  survey | n. 调查；测验
  add up | 合计
  upset | adj. 心烦意乱的；不安的；不适的 // vt. (upset, upset) 使不安；使心烦
  ignore | vt. 不理睬；忽视
  ...
  swap | vt. 交换
  item | n. 项目；条款
  
  Unit 2
  
  subway | n. 地下人行道；<美> 地铁
  elevator | n. 电梯；升降机
  petrol | n. <英> 汽油 （=<美>gasoline）
  gas | n. 汽油；气体；煤气；毒气
  ...
  
  ```


## 有任何想法请直接联系
```
QQ: 997596439
mail: SnowstarCyan$gmail.com
```
