# boss_scrapy
利用代理IP爬取boss直聘的内容
需要注意的几个点:
  1.setting.py文件中要修改DEFAULT_REQUEST_HEADERS中的Proxy-Authorization和cookie
  2.要先在MySQL数据库中添加一个名为boss的数据库，再在数据库中添加名字为company_detail的表
