# bigscreen
大屏地图数据geojson
在官方文档API中，echarts 有一个registerMap(mapName,geoJson,specialAreas)方法，此方法有3个参数：
mapName：地图名称，这里的名称要与地图配置中 option--series--mapType 的值保持一致。
geoJson：geoJson 格式的数据，具体格式见 http://geojson.org/。
specialAreas：可选参数，细节配置，具体参考文档。
现在我们欠缺的就只是 geoJson 文件了，然后我们打开http://geojson.io，这是一个可以在线绘制 geoJson 的网站，就是因为它我们才能随心所欲的绘制我们想要的地图样式和 geoJson 数据。
