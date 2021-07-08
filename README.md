# Ys7
萤石云 thinkphp3.2 简易SDK

        $client = new Ys7Client(appKey,appSecret);
        echo "AccessToken=".$client->getAccessToken() . "\n";
        echo "Camera List:\n";
        print_r($client->getCameraList());

        echo "测试设备信息\n";
        print_r($client->getCameraInfo('203751922'));

        echo "测试设备信息\n";
        print_r($client->addCamera('825959238','SWUHXW'));


## 致谢 
 开发参考 [mangdin/Ys7](https://github.com/mangdin/Ys7).