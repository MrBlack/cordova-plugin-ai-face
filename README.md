这是将百度的人脸检测和活体检查demo封装成插件，我没有上传到其余插件库中所以无法通过命令来安装它
该插件支持IOS和Android

引入：declare let  window: any;

活体检测（点头，摇头，张嘴等六个动作随机两个s）:

  window.BaiduAi.faceLiveness([],function(success){
            
	    },function(error){


      });
人脸检测:

  window.BaiduAi.faceDetect([],function(success){

          },function(error){
                 
		 
		 });


正常情况下可以正常调用插件但是会在检测界面提示无法检测人脸，原因是你需要去申请百度人脸检测认证包名之类的，无法在此一一道来


如果有些抓破脑袋都想不明白的问题可以加我Q647836186。也欢迎各位大大提交分支
