# UE5.3 VR Template

## 封装内容：

**1.PC上模拟VR操作**

避免开发VR项目的时候频繁脱戴VR眼镜，调试起来方便太多。

**2.右手射线**

灵活控制右手射线显示，Trigger按钮触发Widget Blueprint控件的点击事件。

**3.字幕框**

可播放声音，播放完声音自动执行下一个节点。

**4.UI**

**5.高亮显示**

两种方式：设置PostProcessVolume和更换材质。使用说明：把BPBaseFunc蓝图类放到场景中即可使用HighlightActor和UnhighlightActor两个方法

https://zhuanlan.zhihu.com/p/455073329

https://zhuanlan.zhihu.com/p/337393342

**6.操作键优化**

含手柄操作说明和场景选项

**7.中文字体**

使用字体：场景中选择中TextRender项，Details中的Text下的TextMaterial和Font选择自定义的字体和材质球。

添加字符集：修改Font里的ImportOptions下的Chars，点击Asset菜单下的ReimportFont以重新导入字体并保存。修改对应的材质球，把FontParam的Font项清空再重新选择刚修改的Font，保存材质。

创建新字体：修改Font里的ImportOptions下的FontName和Height(字号)，下边的操作参照如上“添加字符集”。

**8.用InterfaceBlueprint实现抓取、放开、点击、触碰等事件触发**

**9.事件驱动开发模式**

**10.选择菜单**

**11.模拟JS按钮点击事件**

蓝图通过Event Dispatcher实现

**12.文字版按钮也采用Menu的按钮**

**13.场景内可移动范围显示**

**14.物体抓握**

**……**
