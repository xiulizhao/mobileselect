# mobileselect
滚动选择器 元素, 支持是否联动/单选到多选<br>
<img src="http://www.wware.org/img/mo2.jpg?_4893" width="400px"><br>
普通属性<br>
data-relation	每级数据是否联动	<br>
data-selectid	触发器对象选择器,与html页面一至，页面只有一个下拉，使用默认即可	#mobileselect<br>
data-title	弹出框标题	<br>
data-ensure	弹出框确定按钮文字	<br>
data-cancel	弹出框取消按钮文字	<br>
data-position	显示默认选择项，初始化定位 打开时默认选中的哪个 如果不填默认为0，即第一个，多列时，例：0,2,2逗号隔开即可	０,1,2<br>
控制属性<br>
data--datasource	滚动选择源数据	1级联动：[{id: '1', value: '加载中', childs: [{ id: '', value: '加载中' }, ] }] ２级不联动：[['周一','周二'],['12:00','18:00'] ]<br>
输出属性<br>
data-x-source0	确定时，输出第一列的值	几(ｎ)列值，输出属性：data-x-source(n-1)<br>
data-x-source1	确定时，输出第二列的值	<br>
data-x-source2	确定时，输出第三列的值<br>
