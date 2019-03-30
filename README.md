# Web-Crawler
爬取FT、Wikipedia、Telegraph等网站的英国公司非结构化数据，包括公司简介、经营活动等。

使用如Request、urllib、bearutifulsoup 等包，通过selector或Xpath对网站指定内容进行爬取。

使用公司股票代码作为Unique ID，通过公司代码遍历，搜索各个公司在FT、telegraph的网站进行特定内容的爬取。

预处理包括对结构化数据的单位标准化，部分缺失值的填充等。
