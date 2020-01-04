This directory contains the Hall of Fame dataset crawled from Sina Weibo. Feel free to use the data for any research. To cite this dataset, please use the following:
@incollection{tu2015prism,
  title={PRISM: Profession Identification in Social Media with Personal Information and Community Structure},
  author={Tu, Cunchao and Liu, Zhiyuan and Sun, Maosong},
  booktitle={Social Media Processing},
  pages={15--27},
  year={2015},
  publisher={Springer}
}

FILE SUMMARY:
The file 'profession.json' contains profession information in JSON format. In each line, the fields of 'profession1', 'profession2' and 'profession3' represent the professions in different levels of current user. It means that 'profession2' is a sub-class of 'profession1' and 'profession3' is a sub-class of 'profession2'.
The file 'verifiedText.json' contains verified information in JSON format. In each line, the field 'verifiedText' represent the verified reason of current user, which is annotated by the officials of Sina Weibo.
The file 'introduction.json' contains introduction information in JSON format. In each line, the field 'introduction' represent the introduction of current user, which is filled in by itself.
The file 'tags.json' contains tag information in JSON format. In each line, the field 'tags' is an array of tags of current user.
introduction.json: json格式存储的用户个人简介，title对应个人简介，tags对应上述的class1职业类别。
tags.json: json格式存储的用户标签信息，tags对应标签列表。
The compressed file ‘microblogs.zip’ contains short messages posted by these users. You can find 14 files after decompression. In each file, it contains messages of 5000 users at most. In each line, the field 'microblogs' is an array of all posted messages of current user. 


本文件夹包含从新浪微博抓取的名人堂认证用户数据，本数据仅供学术研究使用，如若使用，请引用如下论文：
@incollection{tu2015prism,
  title={PRISM: Profession Identification in Social Media with Personal Information and Community Structure},
  author={Tu, Cunchao and Liu, Zhiyuan and Sun, Maosong},
  booktitle={Social Media Processing},
  pages={15--27},
  year={2015},
  publisher={Springer}
}

文件说明：
profession.json: json格式存储的用户职业数据。profession1、profession2及profession3三个字段分别对应用户从高到低三个层次的职业信息。其中，profession2是profession1的子类，profession3是profession2的子类。
verifiedText.json: json格式存储的用户认证信息。每一行中，verifiedText字段对应当前用户的认证信息，这个认证信息是由新浪微博官方人员标注的。
introduction.json: json格式存储的用户个人简介。每一行中，introduction字段对应当前用户的个人简介，这个简短的个人简介是由用户自己填写的。
tags.json: json格式存储的用户标签信息。每一行中，tags字段对应当前用户的标签列表。
microblogs.zip: json格式存储的用户发布的微博信息。解压后，包含14个文件。每个文件包含至多5000个用户的微博信息。每一行中，microblogs字段对应当前用户发布的微博列表。