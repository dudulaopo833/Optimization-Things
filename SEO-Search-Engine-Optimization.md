# 内容优化
* 网站标题， 关键字， 描述等优化
* 网站内容优化
* Robot.txt 文件 -> TBC
* 网站地图 -> TBC
* 增加外链引用(引流)

# 网站结构优化
### 扁平化目录层次，控制在三层目录跳转就能访问所有数据
### 面包屑导航， 有助于快速知道现在的层级位置
### 不可以忽略的细节
* 一般网站上面有"logo及标题"一栏， 下面有"版权信息及链接"一栏， 左边是"正文标题及正文"（一般有"面包屑导航"）, 而右边一般有"热门文章", "相关文章"
* 对于上一页下一页这个细节， 以下几种依次更加优化
1. 首页 - 上页 - 下页 - 尾页 --> 小蜘蛛一般爬三层就不爬了
2. 首页 1 2 3 4 5 6 7 8 9 10 下一页 
3. 首页 1 2 3 4 5 6 7 8 9 10 下拉框可以选择所有页数 --> 这样小蜘蛛不需要请求就可以拿到所有数据(推荐这种方式)

# 网页代码优化
### 标题，关键词，描述优化
* <title> 标题
* <meta keywords> 关键词
* <meta description> 网页描述
```
<title>慕课网-免费的IT技能学习</title>
<meta name="Keywords" content="慕课网，慕课，MOOC， 移动开发， IT技能培训， 免费编程视频， web前端开发" />
<meta name="Description" content="慕课网(IMOOC)是学习编程最简单的免费平台， 慕课网提供了丰富的移动端开发， php开发， web前端等课程资源" />
```
###语义化代码
* H1~H6标签用于标题 - 一般用h1和h2，因为对于小蜘蛛来说权重很重, H3~H6 就没必要用了
* UL标签用于无序列表
* OL标签用于有序列表
* DL标签用于定义数据列表
* strong, em表示强调, em是斜体
**正确示范**
```
<ul id ="main-menu" class="main-menu">
  <li>课程</li>
  <li>问答</li>
  <li>我的课程</li>
</ul>
.main-menu{
 dispaly: block;
 border-right: 1px solid #000;
}
```
**错误示范**
```
<ul id ="main-menu" class="main-menu">
  <span>课程</span>
  <span>|</span>
  <span>问答</span>
  <span>|</span>
  <span>我的课程</span>
</ul>
```


