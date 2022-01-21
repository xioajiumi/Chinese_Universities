# Chinese_Universities 中国528所大学基本信息
中国528所高校的校名、英文名、校徽、地址、2021软科排名与总分、办学层次、学校类型、官网链接的python、json、csv数据文件
528 universities's datas about names, logos, ranks, locations, level, types, websites etc. In a format like json or csv.

1.为什么要建立这个小项目？No such data set, maybe we can build one.
  自己想研究下是不是学校越'nb'，然后青年大学习就越'垃圾'（逻辑没问题吧🤣）。但很可惜网上并没有现成大学信息数据源可供我白嫖。
  所以是时候自己动手来为开源运动付出自己的努力了。

2.这个项目有什么用？E-data is a break through and it's interesting to work with Spider and Search Engine API. 
  这个项目的信息并不多，但起的作用却是基础性和连结性的。把现成的数据和Google或Bing的search API结合起来，可能会大大减少你的精力消耗，有了官网链接也方便爬虫批量分析。
  也许你像我一样需要进行一些学校层次的数据分析，但是为了取得数据需要干一些无聊的重复性工作😪。
  
3.这个项目的未来发展？More data, more contributors, and help more. 
  1.丰富度。以后可能会加上官网链接、经费等，从横向纵向两个方向扩展基本信息。
  2.参与度。一个人的精力是有限的，所以欢迎一起添砖加瓦😘。
  3.影响力。先弄个英文版，这样外国的盆友也方便用。

4.如何使用？User guide.
  1.没有编程基础的可以使用csv文件转为xls使用。CSV 2 XLS.
  2.熟悉python可以load pkl文件，得到一个list，里面为582个实例。Python pickel.
  可以使用dir()来获取["name","name_eng","rank","total_score", "school_level","type","note", "location","link","logo"]等信息。
  3.其他语言可以使用json数据和CSV数据。JSON and CSV is sufficient to use for Java or JS.
  csv数据的表头为["name","name_eng","rank","total_score", "school_level","type","note", "location","link","logo"]，共583行。
  json数据格式为：{"rank": xx, "logo":xx, ....."link": "xx"}{"rank": 2, ...., "link": "https://www.pku.edu.cn/\n"}
