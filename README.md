# slidingMenu
在Android Studio项目中，使用ViewPager + Fragment实现滑动菜单Tab效果 --简易版

***
Author  | AnneHan
--      | --
E-mail  | lilyhyl@163.com
***

# 效果图
可以手动滑动菜单

也可以通过点击头部菜单进行切换

<img src="https://github.com/AnneHan/slidingMenu/blob/master/app/src/main/res/mipmap-hdpi/effectpic/p1.jpg" width="35%" height="400" alt="图片"/>
<img src="https://github.com/AnneHan/slidingMenu/blob/master/app/src/main/res/mipmap-hdpi/effectpic/p2.jpg" width="35%" height="400" alt="图片"/>	

# 项目结构图
.  
│  AndroidManifest.xml  
│    
├─java  
│　└─com  
│　　　└─hyl  
│　　　　　└─acccountbookdemo  
│　　　　　　　　　MainActivity.java  
│　　　　　　　　　OneFragment.java  
│　　　　　　　　　TestActivity.java  
│　　　　　　　　　TwoFragment.java  
│                    
└─res  
　　├─drawable  
　　├─layout  
　　│　　　activity_main.xml  
　　│　　　fragment_one.xml  
　　│　　　fragment_two.xml  
　　│        
　　├─menu  
　　│　　　menu_main.xml  
　　│        
　　├─mipmap-hdpi  
　　│　│　ic_launcher.png  
　　│　│    
　　│　└─effectpic  
　　│　　　　　p1.jpg  
　　│　　　　　p2.jpg  
　　│            
　　├─mipmap-mdpi  
　　│　　　ic_launcher.png  
　　│        
　　├─mipmap-xhdpi  
　　│　　　ic_launcher.png  
　　│        
　　├─mipmap-xxhdpi  
　　│　　　ic_launcher.png  
　　│        
　　├─mipmap-xxxhdpi  
　　│　　　ic_launcher.png  
　　│        
　　├─values  
　　│　　　colors.xml  
　　│　　　dimens.xml  
　　│　　　strings.xml  
　　│　　　styles.xml  
　　│        
　　├─values-v21  
　　│　　　styles.xml  
　　│        
　　└─values-w820dp  
　　　　　　dimens.xml 
