
# 一、竖图（组件id：8）
### 1、创建资源位内容

**1.1 选择类型**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190312120708378.png)

**1.2 填写和编辑数据**

（1）若选择“节目”、“专辑”、“播单”，选择频道以及数据，并根据页面展示需要编辑数据，数据在界面的展示规则参考1.3
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190312120954825.png)

（2）若选择“自定义”，填写自定义数据，数据在界面的展示规则参考1.3

（3）若选择为“直播节目P**”，填写名称以及奇谱ID，并根据页面展示需要编辑数据，数据在界面的展示规则参考1.3

**1.3 各类型数据在界面展示规则**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190312120805359.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTI1NjMyMTU=,size_16,color_FFFFFF,t_70)
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
</head>
<body>
	<table>
		<tr align=center>
			<td colspan="2"  bgcolor=#FFDAB9 width=80>类目</td>
			<td bgcolor=#FFDAB9 width=130>图片下第一行</td>
			<td bgcolor=#FFDAB9 width=130>图片下第二行</td>
			<td bgcolor=#FFDAB9 width=160>图片显示</td>
			<td bgcolor=#FFDAB9 width=130>默认图片</td>
			<td bgcolor=#FFDAB9 width=130>默认跳转链接</td>
			<td bgcolor=#FFDAB9 width=160>图片右下角压标</td>
			<td bgcolor=#FFDAB9 width=130>图片右上角压标</td>
		</tr>
		<tr align=center>
			<td rowspan="2">专辑</td>
			<td>来源类</td>
			<td>专辑名称</td>
			<td>最新一期的视频短标题</td>
			<td rowspan="7">1.若选择取生产动图，优先取资源位内动图；2.若选择不取生产动图，可填写“取哪个节目的动图”；3.若不取生产动图，也不填写“取哪个节目的动图”，显示上传图片；4.若无上传图片，显示默认图片</td>
			<td>最新一期视频图片</td>
			<td>最新一期视频链接</td>
			<td>**-**期</td>
			<td rowspan="11">优先级：自制 > 独播 > 付费>用券 > VIP > 1080 > h5端默认压标    <br>专题：专题</td>
		</tr>
		<tr align=center>
			<td>剧集类</td>
			<td>专辑名称</td>
			<td>一句话推荐</td>
			<td>最新一期视频图片</td>
			<td>资源位页面地址</td>
			<td>更新至**集/**集全</td>
		</tr>
		<tr align=center>
			<td rowspan="4">节目</td>
			<td>电影</td>
			<td>标题</td>
			<td>一句话推荐</td>
			<td>电影封面图</td>
			<td>资源位页面地址</td>
			<td>时长</td>
		</tr>
		<tr align=center>
			<td>来源类</td>
			<td>短标题</td>
			<td>一句话推荐<br>若没有，专辑名称</td>
			<td>封面图</td>
			<td>资源位页面地址</td>
			<td>若为正片视频，压标为：**-**期<br>若为非正片视频，压标为：时长</td>
		</tr>
		<tr align=center>
			<td>剧集类</td>
			<td>短标题<br>若没有，一句话推荐<br>若没有，专辑名称</td>
			<td>副标题</td>
			<td>封面图</td>
			<td>资源位页面地址</td>
			<td>若为正片，无压标<br>若为非正片，压标为时长</td>
		</tr>
		<tr align=center>
			<td>短视频</td>
			<td>短标题</td>
			<td>一句话推荐<br>若没有，爱奇艺号名称<br>若没有，发布时间（****-**-**  **:**:**）</td>
			<td>封面图</td>
			<td>资源位页面地址</td>
			<td>时长</td>
		</tr>
		<tr align=center>
			<td colspan="2">播单</td>
			<td>短标题</td>
			<td>一句话推荐</td>
			<td>封面图</td>
			<td>资源位页面地址</td>
			<td>无</td>
		</tr>
		<tr align=center>
			<td rowspan="2">直播</td>
			<td>直播PPC</td>
			<td rowspan="2">标题</td>
			<td>开播时间（****-**-**  **:**:**）</td>
			<td rowspan="3">不支持动图，只能到编目修改图片</td>
			<td rowspan="2">直播图片</td>
			<td>最新一期视频链接</td>
			<td>无</td>
		</tr>
		<tr align=center>
			<td>直播PGC</td>
			<td>直播人名</td>
			<td>资源位页面地址</td>
			<td>无</td>
		</tr>
		<tr align=center>
			<td colspan="2">人物</td>
			<td>人物名称</td>
			<td>一句话推荐</td>
			<td>人物图片</td>
			<td>人物泡泡，若没有为资源位页面地址</td>
			<td>无</td>
		</tr>
		<tr align=center>
			<td colspan="2">自定义</td>
			<td>短标题</td>
			<td>一句话推荐</td>
			<td>不支持动图，可修改自定义图片</td>
			<td>自定义图片</td>
			<td>自定义跳转</td>
			<td>无</td>
		</tr>
	</table>
	
</body>
</html>

**1.4	数据修改方式**

（1）修改标题、一句话推荐、短标题、动图、自定义跳转链接如图所示修改：
![在这里插入图片描述](https://img-blog.csdnimg.cn/2019031212083392.png)

（2）修改专辑名称、直播名称、直播图片、人物名称、人物图片，到对应的编目下修改对应信息。

### 2. 可视化内容填充

**2.1 从组件库中拖入可视化编辑区域的对应位置**

**2.2 选择组件，点击数据/样式**

（1）样式
<table>
	<tr align=center>
		<td>可编辑数据</td>
		<td>操作</td>
		<td>填写规则</td>
	</tr>
	<tr align=center>
		<td>组件标题</td>
		<td>修改样式组件标题，用户不可见</td>
		<td>无</td>
	</tr>
</table>

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190312121903755.png)

（2）数据

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
</head>
<body>
	<table>
		<tr align=center>
			<td colspan="4" bgcolor="#C6E2FF">通用</td>
		</tr>
		<tr align=center>
			<td bgcolor="#FFDAB9" width=100px>操作</td>
			<td bgcolor="#FFDAB9" width=100px>可编辑数据</td>
			<td bgcolor="#FFDAB9" width=50px>是否必填</td>
			<td bgcolor="#FFDAB9" width=200px>填写规则</td>
		</tr>
		<tr align=center>
			<td>添加/修改大标题</td>
			<td>组件标题</td>
			<td>必填</td>
			<td>填写文本<br>未修改时默认为无大标题</td>
		</tr>
		<tr align=center>
			<td>控制图文显示条数</td>
			<td>显示几条数据</td>
			<td>必填</td>
			<td>填写数字，填写-1显示所有<br>未修改时默认为-1<br>根据资源位奇谱id获取数据</td>
		</tr>
		<tr align=center>
			<td>控制图片下的文字</td>
			<td>图片下显示文字类型</td>
			<td>必填</td>
			<td>可提供选项：<br>（1）1行标题1行描述<br>（2）标题可折行且无副标题<br>未修改时默认为1行标题1行描述<br>内容均来自资源位奇谱id </td>
		</tr>
		<tr align=center>
			<td rowspan="6">添加运营位及编辑运营位信息（最多添加1个）</td>
			<td>标题_最多10个字</td>
			<td>必填</td>
			<td>最多10个字</td>
		</tr>
		<tr align=center>
			<td>跳转类型</td>
			<td>必填</td>
			<td>可提供选项：（1）无（2）播放页（3）页面地址（4）播单</td>
		</tr>
		<tr align=center>
			<td>跳转视频qipuId or 播单qipuId</td>
			<td>由“跳转类型”决定</td>
			<td>当跳转类型：播放器或者播单，必填</td>
		</tr>
		<tr align=center>
			<td>跳转url</td>
			<td>由“跳转类型”决定</td>
			<td>当跳转类型：页面地址，必填</td>
		</tr>
		<tr align=center>
			<td>播单下视频奇谱id</td>
			<td>由“跳转类型”决定</td>
			<td>Phone端Pad端跳转类型为播单，必填</td>
		</tr>
		<tr align=center>
			<td>运营位icon</td>
			<td>必填</td>
			<td>上传72px*72px的图片，必须是.jpg或者.png格式</td>
		</tr>
		<tr align=center>
			<td>修改图文来源</td>
			<td>资源位奇谱id</td>
			<td>必填</td>
			<td>填写对应的资源位奇谱id</td>
		</tr>
		<tr align=center>
			<td colspan="4">不同端专用</td>
		</tr>
	</table>
	
</body>
</html>
