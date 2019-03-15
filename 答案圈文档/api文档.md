* #### 答案圈第二次改版新增接口
  * [首页专题列表](#主页专题列表)
  * [首页标签列表](#主页标签列表)

#### 主页专题列表    
v1/zt/index

[返回](#答案圈第二次改版新增接口)

参数名|参数值|参数意义
---|---|---
无| 无| 无

<pre>
<code>
array (
  'code' => 1,
  'msg' => 'Success',
  'data' =>
    'list'=>array(
        array (
          'ztid' => 1588,   //专题介绍
          'ztimg' => "http://www.mxqe.com/d/file/20180709/ba4a8324bfe9765004edbd3c40583076.png",  //专题图片
          'ztname' => "小学六年级数学习题答案",   //专题名称
          'ztpath' => "http://m.mxqe.com/s/xxlnjsxda" //专题的h5链接
        ),  
        *******  //固定返回6条数据  
      )
)
</code>
</pre>


#### 主页标签列表    
v1/tag/index

[返回](#答案圈第二次改版新增接口)

参数名|参数值|参数意义
---|---|---
无| 无| 无

<pre>
<code>
array (
  'code' => 1,
  'msg' => 'Success',
  'data' =>
    'list'=>array(
        array (
          'tagid' => 17265,   //标签id
          'tagname' => "高三联考",   //标签名称
        ),
        ******   //固定返回6条数据    
      )
)
</code>
</pre>
