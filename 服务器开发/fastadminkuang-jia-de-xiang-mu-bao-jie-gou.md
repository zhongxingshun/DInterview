# FastAdmin框架的项目包结构

project  应用部署目录  
├── application  
│   ├── admin  //后台管理应用模块
│   │   ├── command            //新增控制台命令  
│   │   ├── controller               
│   │   ├── lang  
│   │   │   ├── zh-cn            //控制器对应语言包,按需加载  
│   │   │   │   ├── general  
│   │   │   │   ├── index.php  
│   │   │   │   └── page.php  
│   │   │   └── zh-cn.php        //后台语言包,默认加载  
│   │   ├── library  
│   │   │   ├── Auth.php        //后台权限验证类  
│   │   │   └── traits  
│   │   │       └── Backend.php //后台控制器的Traits  
│   │   ├── model  
│   │   ├── view  
│   │   ├── common.php  
│   │   └── config.php  
│   ├── api  //API应用模块
│   │   ├── controller  
│   │   ├── model  
│   │   ├── view  
│   │   ├── common.php  
│   │   └── config.php  
│   ├── common  //通用应用模块
│   │   ├── controller  
│   │   │   ├── Api.php            //Api基类  
│   │   │   ├── Backend.php        //后台基类  
│   │   │   ├── Frontend.php           //前台基类  
│   │   │   └── Uc.php            //Ucenter基类  
│   │   ├── library  
│   │   │   ├── Auth.php        //前台权限验证类  
│   │   │   └── Token.php        //前台Token类  
│   │   ├── model  
│   │   └── view  
│   ├── extra  //扩展配置目录
│   │   ├── payment.php            //支付配置  
│   │   ├── service.php            //第三方服务配置  
│   │   ├── site.php            //站点配置  
│   │   ├── third.php            //第三方登录配置  
│   │   ├── upload.php            //上传配置  
│   │   └── wechat.php            //微信配置  
│   ├── index  //前台应用模块
│   │   ├── controller  
│   │   ├── lang  
│   │   ├── model  
│   │   └── view  
│   ├── build.php  
│   ├── command.php  //命令行配置
│   ├── common.php  //通用辅助函数
│   ├── config.php  //基础配置
│   ├── constants.php  //常量配置
│   ├── database.php  //数据库配置
│   ├── route.php  //路由配置
│   ├── tags.php  //行为配置
│   └── uc.php    //UC常量  
├── extend  
│   └── fast  //FastAdmin扩展辅助类目录
│       ├── payment            //微信支付宝类  
│       ├── service            //第三方服务扩展  
│       ├── third            //第三方登录类  
│       ├── ucenter            //Ucenter文件夹  
│       ├── Auth.php            //Auth权限验证类  
│       ├── Date.php            //日期类  
│       ├── Form.php            //表单元素生成类  
│       ├── Http.php            //Http请求类  
│       ├── Menu.php            //后台菜单生成类  
│       ├── Pinyin.php            //中文转拼音转换类  
│       ├── Random.php            //随机数生成类  
│       ├── Rsa.php            //Rsa验证类  
│       └── Tree.php            //Tree类  
├── public  
│   ├── assets  
│   │   ├── build            //打包JS、CSS的资源目录  
│   │   ├── css                //CSS样式目录  
│   │   ├── fonts            //字体目录  
│   │   ├── img  
│   │   ├── js  
│   │   │   ├── backend  
│   │   │   └── frontend  //后台功能模块JS文件存放目录
│   │   ├── libs            //Bower资源包位置  
│   │   └── less            //Less资源目录  
│   └── uploads                //上传文件目录  
│   ├── index.php  
│   ├── robots.txt  
│   └── router.php  
├── runtime  //缓存和运行日志目录
├── thinkphp                //ThinkPHP5框架核心目录  
├── vendor                  //Compposer资源包位置  
├── .bowerrc                //Bower目录配置文件  
├── LICENSE  
├── README.md  
├── bower.json                //Bower前端包配置  
├── build.php  
├── composer.json            //Composer包配置  
└── think

