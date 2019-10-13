# game-patch
unity小黄油去码
unity h game uncensoreb patch

替换文件即可，请先备份。

原理：
使用dnSpy打开Assembly-CSharp.dll，搜索mosaic，修改mosaic的类即可。
例如：mosaic的数值改为1f，mosaic改成hide()。具体怎么改需要分析mosaic的语句。留意_blocksize，mosaic等关键词。
使用AssetsBundleExtractor把assets中含有mosaic的文件删除。

求助
如何提取unity游戏中的Live2d模型？
参考Perfare/AzurLaneLive2DExtract