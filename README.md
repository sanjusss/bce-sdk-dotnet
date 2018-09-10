
[![Supported](https://img.shields.io/badge/Supported-.NET4.6.1%2B%2F.NETCore2.0%2B-brightgreen.svg)](#)

# 安装SDK工具包

**运行环境**


C# SDK工具包可在Microsoft .NET Standard 2.0 环境下运行，即.NET Core 2.0和.NET Framework 4.6.1。

**SDK目录结构**

    BaiduBce
           ├── Auth                                        //BCE签名相关类
           ├── Http                                        //BCE的Http通信相关类
           ├── Internal                                    //SDK内部类
           ├── Model                                       //BCE公用model类
           ├── Services
           │       └── Bos                                 //BOS服务相关类
           │           ├── Model                           //BOS内部model，如Request或Response
           │           ├── BosClient.cs                 //BOS客户端入口类
           │           └── BosConstants.cs              //BOS特有的常量定义，如权限常量等
           ├── Util                                        //BCE公用工具类
           ├── BceClientConfiguration.cs                  //对BCE的HttpClient的配置
           ├── BceClientException.cs                      //BCE客户端的异常类
           ├── BceServiceException.cs                     //与BCE服务端交互后的异常类
           ├── BceConstants.cs                            //BCE的通用常量(区域，请求头，错误码等)
           
           
# 快速入门

请参考[快速入门](http://bce.baidu.com/doc/BOS/Cs-SDK.html#快速入门)。

# SDK使用帮助

请参考[BOS C# SDK文档](http://bce.baidu.com/doc/BOS/Cs-SDK.html)。
  