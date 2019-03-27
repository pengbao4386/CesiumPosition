# CesiumPosition
Cesium鼠标移动，显示坐标  
使用方法：  
1.引入ShowPosition文件：<script src="ShowPosition.js"></script>  
2.创建viewer实例，并调用ShowPosition文件里面的方法：  
    var viewer = new Cesium.Viewer('cesiumContainer');  
    ShowPosition(viewer,Cesium,"cesiumContainer");其中"cesiumContainer"为包含viewer实例的DOM要素或id  
3.完成！
