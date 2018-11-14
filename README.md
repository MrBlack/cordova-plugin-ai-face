这是将百度的人脸检测和活体检查演示封装成插件，我没有上传到其余插件库中所以无法通过命令来安装它


引入：declare let  window: any;

活体检测（点头，摇头，张嘴等六个动作随机两个s）

window.BaiduAi.faceLiveness([],function(success){
            
	    },function(error){


      });
人脸检测
window.BaiduAi.faceDetect([],function(success){

          },function(error){
                 
		 
		 });
