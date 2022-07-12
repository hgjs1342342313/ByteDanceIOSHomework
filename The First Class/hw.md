### 作业1：按顺序打印出App、ViewController 生命周期的各个事件

应用程序的生命周期：点击程序图标、执行main函数、通过UIApplicationMain函数初始化UIApplication对象并设置代理对象（程序载入后：applicationDidFinishLaunching；将要进入非活动状态：applicationWillResignActive；进入活动状态：applicationDidBecomeActive；程序进入后台：applicationDidEnterBackground；从后台将要进入前台：applicationWillEnterForeground；内存警告程序将要终止：applicationDidReceivememoryWarning；程序将要结束：applicationWillTerminate；等）、UIApplication对象监听系统事件直到程序结束退出。

ViewController的生命周期：alloc/init; loadView; viewDidLoad; viewWillAppear; viewDidAppear; viewWillDisappear; viewDidDisappear; dealloc

### 作业2：写出五种常用的UI控件

UIScrollView、UITableView、UICollectionView、UIWebView、WkWebView





### 作业3：列举三个UITableViewDelegate声明的方法

1.选中某行cell调用此方法

2.自定义每组头部的view需要使用到UITableViewHeaderFooterView

3.自定义每组尾部的View需要使用到UITableViewHeaderFooterView