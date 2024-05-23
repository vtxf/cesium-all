# Cesium资料大全

最后更新2024年5月

## 前言

Cesium是一个用于显示三维地球和地图的开源js库。它可以用来显示海量三维模型数据、影像数据、地形高程数据、矢量数据等等。三维模型格式支持gltf、三维瓦片模型格式支持3d tiles。矢量数据支持geojson、topojson、kml格式。影像数据支持wms、wmts等。高程支持STK格式。另外支持自有格式czml的加载。

## Cesium官方

- Cesium官网 https://cesium.com/
- Cesium下载 https://cesium.com/downloads/
- CesiumJS的API文档 https://cesium.com/learn/cesiumjs/ref-doc/
- Cesium官方示例 https://sandcastle.cesium.com/
- Cesium官方教程(英文) https://cesium.com/learn/cesiumjs-learn/
- Cesium官方博客(英文) https://cesium.com/blog/
- Cesium官方社区(英文) https://community.cesium.com/
- Cesium Ion(官方数据后台, 收费且服务器在国外) https://ion.cesium.com/
- Cesium for Unreal https://cesium.com/platform/cesium-for-unreal/
- Cesium for Unity  https://cesium.com/platform/cesium-for-unity/
- Cesium for O3DE https://cesium.com/platform/cesium-for-o3de/
- Cesium for omniverse: https://cesium.com/platform/cesium-for-omniverse/

## Cesium源码在github上
- Cesium https://github.com/CesiumGS/cesium
- Cesium for Unreal https://github.com/CesiumGS/cesium-unreal
- Cesium for Unity https://github.com/CesiumGS/cesium-unity-samples
- Cesium for O3DE https://github.com/CesiumGS/cesium-o3de
- Cesium for omniverse https://github.com/CesiumGS/cesium-omniverse

## Cesium在gitee上
- Cesium源码 https://gitee.com/mirrors/CesiumJS

## Cesium开发资料
- Cesium材质文档 https://gitee.com/mirrors/CesiumJS/blob/main/Documentation/FabricGuide/README.md
- Cesium自定义shader文档 https://gitee.com/mirrors/CesiumJS/tree/main/Documentation/CustomShaderGuide
- Cesium离线使用文档 https://gitee.com/mirrors/CesiumJS/tree/main/Documentation/OfflineGuide
- Cesium CZML指南 https://github.com/AnalyticalGraphicsInc/czml-writer/wiki/CZML-Guide

## Cesium教程
- Cesium中文网 http://cesium.xin/
- Cesium快速上手(视频) https://www.bilibili.com/video/BV1B7411G7HP
- 北京西部世界相关Cesium教学视频 https://space.bilibili.com/346212872/channel/seriesdetail?sid=1634802
- Cesium教程系列汇总(法克鸡丝, 超图大牛作品，国内较早的深入研究教程) https://www.cnblogs.com/fuckgiser/p/5706842.html https://pasu.github.io/ExamplesforCesium/examples/examples.html https://github.com/pasu/ExamplesforCesium
- 三维地球开发书籍(Cesium创始人 Patrick Cozzi 早期作品) https://virtualglobebook.com/

## Cesium CDN
如果想直接使用Cesium，而有不下载Cesium的话，可以尝试这种方式，其中的版本号可以更换。
```html
<script src="https://cesium.com/downloads/cesiumjs/releases/1.116/Build/Cesium/Cesium.js"></script>
<link href="https://cesium.com/downloads/cesiumjs/releases/1.116/Build/Cesium/Widgets/widgets.css" rel="stylesheet"> 
```

## Cesium API文档
- 最新版(官方) https://cesium.com/learn/cesiumjs/ref-doc/
- Cesium 1.117(Cesium中文网) http://cesium.xin/cesium/Documentation1.117/index.html
- Cesium 1.95中文 (Cesium中文网) http://cesium.xin/cesium/cn/Documentation1.95/index.html

## Cesium 插件
- 国产地图加载  https://github.com/CesiumChina/cesium-map
- 指北针: https://github.com/alberto-acevedo/cesium-navigation
- cesium-drawhelper(年久失修)  https://github.com/leforthomas/cesium-drawhelper
- leation/drawhelper-with-cesium-v1.41(李仙伟改版的图形编辑插件，年久失修) https://github.com/leation/drawhelper-with-cesium-v1.41
- GeoserverTerrainProvider https://github.com/kaktus40/Cesium-GeoserverTerrainProvider
cesium-print https://github.com/richard1015/cesium-print
- coordtransform 坐标转换 一个提供了百度坐标（BD09）、国测局坐标（火星坐标，GCJ02）、和WGS84坐标系之间的转换的工具模块 https://github.com/wandergis/coordtransform  

## 国产Cesium SDK和工具
- wish3d(中科图新) http://www.wish3d.com/
- thingjs https://www.thingjs.com/
- EarthSDK(北京西部世界) https://earthsdk.com/
- mars3d(火星): https://gitee.com/marsgis/mars3d
- DC(Digital Visual for Cesium) 一款构建三维WebGis应用的开源开发平台 https://dc.dvgis.cn/
- vue-cesium Vue for Cesium  基于 Vue 3，面向开发者的 CesiumJS 组件库。 https://zouyaoji.top/vue-cesium/#/zh-CN https://gitee.com/zouyaoji/vue-cesium
- vue3-ts-cesium-map-show 前端 vue3.0 + typescript 三维可视化数字城市数字孪生 https://gitee.com/hawk86104/vue3-ts-cesium-map-show
- QuickEarth-Free 一个二三维一体化的Web端矢量和栅格数据渲染引擎 https://gitee.com/mofangbao/quick-earth-free  
- My3dtiles(本地离线3dtiles数据查看，低代码数字孪生工具，北京西部世界) https://www.wolai.com/earthsdk/s5ZX52JqRxzbgrA9XDTRHr

## Cesium相关开源项目
- MikesWei/CesiumMeshVisualizer(国内大牛作品，含物理引擎、BSP、体渲染) https://github.com/MikesWei/CesiumMeshVisualizer
- MikesWei/CesiumVectorTile(shp/geojson转矢量切片) https://github.com/MikesWei/CesiumVectorTile
- cesium-threejs-experiment(结合Cesium和Three.js的示例) https://github.com/AnalyticalGraphicsInc/cesium-threejs-experiment
- ShareQiu1994/cesium-vue(Cesium实验室QQ群中的 乘风破浪 的作品 Cesium+Webpack+Vue的项目样板) https://github.com/ShareQiu1994/cesium-vue
- geo-data/cesium-terrain-server(Cesium地形服务，许久未更新) https://github.com/geo-data/cesium-terrain-server
- mattshax/cesium_pnt_generator(点云数据转3dtiles) https://github.com/mattshax/cesium_pnt_generator
- openlayers/ol-cesium: (OpenLayers + Cesium集成) https://github.com/openlayers/ol-cesium
- NICTA/cesium-vr(Cesium支持Oculus VR headset)  https://github.com/NICTA/cesium-vr

## gltf相关
- KhronosGroup/glTF(gltf格式文档) https://github.com/KhronosGroup/glTF https://registry.khronos.org/glTF/
- AnalyticalGraphicsInc/obj2gltf(Cesium官方出品的obj转gltf工具) https://github.com/CesiumGS/obj2gltf
- AnalyticalGraphicsInc/gltf-vscode(直接在vscode上看gltf的插件) https://github.com/AnalyticalGraphicsInc/gltf-vscode
- AnalyticalGraphicsInc/gltf-pipeline(gltf数据处理优化工具) https://github.com/CesiumGS/gltf-pipeline
- KhronosGroup/glTF-Sample-Models(glTF样例模型) https://github.com/KhronosGroup/glTF-Sample-Models
- sketchfab(gltf模型下载) https://sketchfab.com/
- OpenGL官方的格式转换工具 https://github.com/KhronosGroup/COLLADA2GLTF/
- glTF Viewer(Three.js的gltf模型查看器) https://gltf-viewer.donmccurdy.com/
- BabylonJS Sandbox(Babylon出品gltf查看器) http://sandbox.babylonjs.com/
- Clay Viewer(国内百度大牛出品的gltf查看器，效果惊艳！) https://pissang.github.io/clay-viewer/editor/

## 3dtiles相关
- AnalyticalGraphicsInc/3d-tiles(3d tiles数据格式说明) https://github.com/CesiumGS/3d-tiles
- AnalyticalGraphicsInc/3d-tiles-tools(Cesium官方出品的3d tiles数据的处理工具) https://github.com/CesiumGS/3d-tiles-validator
- AnalyticalGraphicsInc/3d-tiles-samples(Cesium官方出品的3d tiles样例数据) https://github.com/CesiumGS/3d-tiles-samples
- SuperMap/s3m-spec(和3d tiles同类的超图的s3m格式说明) https://github.com/SuperMap/s3m-spec
- Esri/i3s-spec(和3d tiles格式同类的ArcGIS的i3s格式说明) https://github.com/Esri/i3s-spec
- fanvanzh/3dtiles(Cesium实验室QQ群中的米斯特范的osgb转3dtiles工具) https://github.com/fanvanzh/3dtiles

## 地形相关
- Cesium地形格式说明 https://github.com/CesiumGS/quantized-mesh 
- Cesium地形生成工具 https://github.com/geo-data/cesium-terrain-builder

## WebGL引擎
- threejs https://threejs.org/
- babylonjs https://www.babylonjs.com/
- shadertoy https://www.shadertoy.com/
- luma.gl https://luma.gl/
- claygl.xyz(国内百度大牛pissang的webgl引擎) http://claygl.xyz/
- itowns(基于Three.js的三维地球引擎) https://github.com/iTowns/itowns
- WebGlobe(国内之前在ArcGIS后来去美团的大牛的三维地图引擎) https://github.com/iSpring/WebGlobe
- OpenGlobe(Cesium创始人 Patrick Cozzi 早期作品) https://github.com/virtualglobebook/OpenGlobe
- inmap(一款基于百度地图的大数据可视化库) https://github.com/TalkingData/inmap
- deck.gl(WebGL2 powered visualization framework) https://deck.gl/ https://github.com/visgl/deck.gl

## WebGL教程
- MDN上的webgl教程 https://developer.mozilla.org/zh-CN/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL
- webgl2教程 https://webgl2fundamentals.org/webgl/lessons/zh_cn/
- webgl1教程 https://webglfundamentals.org/webgl/lessons/zh_cn/
- Three.js 入门指南 http://zhangwenli.com/ThreeExample.js/
- shader-school https://github.com/stackgl/shader-school

## web3d相关
- 气象地球(效果很棒) https://earth.nullschool.net/ https://github.com/cambecc/earth
- webgl-blendfunctions https://github.com/mrdoob/webgl-blendfunctions
- earcut(多边形三角化) https://github.com/mapbox/earcut

## 数字孪生相关企业
- 超图(ue&web3d&cesium) https://www.supermap.com/
- 北京飞渡(ue) https://www.freedoonline.com/
- 北京西部世界(cesium&ue) https://www.cesiumlab.com
- 西安恒歌(osg&cesium) https://www.henggetec.com/
- 北京优诺ThingJS https://www.uino.com/
- 苏州wish3D(web3d&cesium) https://www.wish3d.com
- 厦门图扑(web3d) https://www.hightopo.com/
- 合肥火星(cesium) http://mars3d.cn/
- 杭州山海鲸(ue&cesium) https://www.shanhaibi.com/
