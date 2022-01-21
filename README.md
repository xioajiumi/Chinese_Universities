# Chinese_Universities 中国528所大学基本信息
中国528所高校的校名、英文名、校徽、地址、2021软科排名与总分、办学层次、学校类型的python、json、csv数据文件
528 universities's datas of names, logos, ranks, locations, level, types, in a format like json or csv.

1.为什么要建立这个小项目？
  自己想研究下是不是学校越'nb'，然后青年大学习的表现就越不好（正经人）。但很可惜我发现青年大学习的数据并不好获得，而且网上并没有现成数据源可供我白嫖。
  所以是时候自己动手来为开源运动付出自己的努力了。

2.这个项目有什么用？
  这个项目的信息并不多，但起的作用却是基础性和连结性的。把现成数据的数据和Google结合起来，可能会大大减少你的精力消耗。
  也许你像我一样需要进行一些关于学校层次的数据分析，去干一些无聊的重复性工作。
  
3.这个项目的未来发展？
  1.丰富度。以后可能会加上官网链接、经费等，从横向纵向两个方向扩展。
  2.参与度。一个人的精力是有限的，所以欢迎指正错误，一起贡献。
  3.影响力。先弄个英文版，这样外国的盆友也可以用

4.如何使用？
  没有编程基础的可以使用csv文件转为xls使用。
  熟悉python可以load pkl文件，得到一个list，里面为582个实例。
  可以使用dir()来获取["name","name_eng","rank","total_score", "school_level","type","note", "location","link","logo"]等信息。
  其他语言可以使用json数据和CSV数据。
  csv数据的表头为["name","name_eng","rank","total_score", "school_level","type","note", "location","link","logo"]，共583行。
  json数据格式为：{"rank": xx, "logo":xx, ....."link": "xx"}{"rank": 2, ...., "link": "https://www.pku.edu.cn/\n"}
