http://edu.site/api/index/query  //分数查询接口

参数|参数值|参数说明
---|--|--
score_subject|理科|考生科目文科或理科 必传
score_province|安徽|考生的生源地 必传
score_level|较稳妥|考生的意愿可冲击 较稳妥 可保底三种 必传
score|500|考生分数 必传
page|1|每页 必传
page_size|10|每页数量 必传
college_province|北京|考生意愿上学的位置 可传
college_type|学校类型|比如综合 理工 医科  可传
batch|学校批次|本科一批二批等 可传

<pre>
<code>
data:
list: Array(10)
0:
batch_score: 432     //学校批次分数
batch_year: "2018"
college_batch: "本科第二批"   //学校批次
college_name: "内蒙古财经大学"  //学校名称
college_province: "内蒙古"     //学校位置
college_rank: 190            //学校排名
desire_type: "较稳妥"
desire_weight: "66"
img: "http://t11.baidu.com/it/u=3829237039,4207002110&fm=179&app=42&f=JPEG?w=250&h=250"   //学校logo
lowest_score: 463
lowest_year: "2017"
score: 500     //考生分数
score_batch: "本科第二批"      
score_province: "安徽"
score_subject: "理科"
tag: (2) ["财经类", "薪酬超过83%院校"]  
type: "财经类"  //学校类型
url: "https://m.baidu.com/sf?pd=education_school&openapi=1&dspName=iphone&from_sf=1&resource_id=5087&word=内蒙古财经大学&group=32880&ext={"sf_tab_name":"intro"}&title=内蒙古财经大学"
1: {batch_score: 487, batch_year: "2017", college_batch: "本科第二批", college_name: "内蒙古医科大学", college_province: "内蒙古", …}
2: {batch_score: 432, batch_year: "2018", college_batch: "本科第二批", college_name: "内蒙古工业大学", college_province: "内蒙古", …}
3: {batch_score: 432, batch_year: "2018", college_batch: "本科第二批", college_name: "内蒙古科技大学", college_province: "内蒙古", …}
4: {batch_score: 487, batch_year: "2017", college_batch: "本科第二批", college_name: "新乡医学院", college_province: "河南", …}
5: {batch_score: 432, batch_year: "2018", college_batch: "本科第二批", college_name: "河北科技师范学院", college_province: "河北", …}
6: {batch_score: 432, batch_year: "2018", college_batch: "本科第二批", college_name: "石家庄学院", college_province: "河北", …}
7: {batch_score: 432, batch_year: "2018", college_batch: "本科第二批", college_name: "唐山学院", college_province: "河北", …}
8: {batch_score: 432, batch_year: "2018", college_batch: "本科第二批", college_name: "廊坊师范学院", college_province: "河北", …}
9: {batch_score: 487, batch_year: "2017", college_batch: "本科第二批", college_name: "北京石油化工学院", college_province: "北京", …}

otherinfo:
batch: Array(2)    //考生可选择的批次
0: {sa: "本科第二批", su: 109, hasSubCate: 0}
1: {sa: "高职专科一批", su: 12, hasSubCate: 0}

college_prov: Array(28)    //考生可以选择的学校地区  跟随分数而变化
0: {sa: "北京", su: 4, hasSubCate: 0}
1: {sa: "安徽", su: 8, hasSubCate: 0}
2: {sa: "重庆", su: 3, hasSubCate: 0}
3: {sa: "福建", su: 4, hasSubCate: 0}
4: {sa: "甘肃", su: 5, hasSubCate: 0}
5: {sa: "广东", su: 5, hasSubCate: 0}
6: {sa: "广西", su: 4, hasSubCate: 0}
7: {sa: "贵州", su: 3, hasSubCate: 0}
8: {sa: "河北", su: 8, hasSubCate: 0}
9: {sa: "黑龙江", su: 7, hasSubCate: 0}
10: {sa: "河南", su: 8, hasSubCate: 0}
11: {sa: "湖北", su: 5, hasSubCate: 0}
12: {sa: "湖南", su: 5, hasSubCate: 0}
13: {sa: "江苏", su: 5, hasSubCate: 0}
14: {sa: "江西", su: 7, hasSubCate: 0}
15: {sa: "吉林", su: 4, hasSubCate: 0}
16: {sa: "辽宁", su: 3, hasSubCate: 0}
17: {sa: "内蒙古", su: 6, hasSubCate: 0}
18: {sa: "宁夏", su: 1, hasSubCate: 0}
19: {sa: "青海", su: 2, hasSubCate: 0}
20: {sa: "陕西", su: 2, hasSubCate: 0}
21: {sa: "山东", su: 7, hasSubCate: 0}
22: {sa: "上海", su: 1, hasSubCate: 0}
23: {sa: "山西", su: 4, hasSubCate: 0}
24: {sa: "四川", su: 4, hasSubCate: 0}
25: {sa: "天津", su: 1, hasSubCate: 0}
26: {sa: "云南", su: 2, hasSubCate: 0}
27: {sa: "浙江", su: 3, hasSubCate: 0}

desire_type: Array(1)  //考生选择的意愿
0:
hasSubCate: 0
sa: "较稳妥"
su: 121

type: Array(10)   //考生可报考的学校类型
0: {sa: "综合类", su: 33, hasSubCate: 0}
1: {sa: "理工类", su: 22, hasSubCate: 0}
2: {sa: "农林类", su: 5, hasSubCate: 0}
3: {sa: "医药类", su: 17, hasSubCate: 0}
4: {sa: "师范类", su: 25, hasSubCate: 0}
5: {sa: "财经类", su: 7, hasSubCate: 0}
6: {sa: "政法类", su: 1, hasSubCate: 0}
7: {sa: "体育类", su: 3, hasSubCate: 0}
8: {sa: "艺术类", su: 2, hasSubCate: 0}
9: {sa: "民族类", su: 6, hasSubCate: 0}

</code>
</pre>
