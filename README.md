# fangtianxia_redis
​	scrapy redis分布式爬虫，爬取房天下新房二手房数据

​	``start_urls``为房天下[城市列表页](https://esf.fang.com/esfcities.aspx)，对所有城市链接进行提取，并通过拼接生成新房链接和二手房链接，再对新房链接和二手房链接进行请求，爬取``新房``房名、价格、地址、户型、区域和链接等信息，爬取``二手房``房名、户型、区域、年代、楼层、联系人、地址、价格和链接等信息

