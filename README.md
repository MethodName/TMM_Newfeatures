# TMM_Newfeatures
1.0

####使用
```objc
  TMM_NewfeaturesController *welcomeVC = [[TMM_NewfeaturesController alloc]init];
        [welcomeVC.view setFrame:self.window.bounds];
        [welcomeVC setImageNames:@[@"1",@"2",@"3"]];//设置图片数组
        [welcomeVC setCompleteDelegate:self];//设置代理
        //设置新特性页面为rootVC
        [self.window setRootViewController:welcomeVC];

```

###设置代理
```objc
 [welcomeVC setCompleteDelegate:self];//设置代理
 
 -(void)welcomeOK
{
    //切回原来的rootVC
}

 
 
```