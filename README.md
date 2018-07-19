# SlidingMenuBestImplementation
<body spellcheck="0" class="editMode htmledit_views">Android 侧滑菜单栏SlidingMenu优化实现（SlidingMenu + FragmentTabHost），主要功能包括：通过手势左滑（右滑）展示菜单栏、通过点击按钮展示左滑（右滑）菜单栏、FragmentTabHost的切换、侧滑菜单栏的点击事件（切换Fragment）、返回键关闭侧滑菜单栏、侧滑菜单栏的沉浸式效果、侧滑剩余部分的阴影效果等。<br>项目博客地址：https://blog.csdn.net/qq941263013/article/details/81116930<br>个人博客地址：https://blog.csdn.net/qq941263013<br>效果图：<br><img src="https://github.com/wangyang0313/SlidingMenuBestImplementation/blob/master/a6b8386c-3a79-4609-a636-ad63b8f55aa3.gif" _xhe_src="https://github.com/wangyang0313/SlidingMenuBestImplementation/blob/master/a6b8386c-3a79-4609-a636-ad63b8f55aa3.gif"><br><br>简单说明（详细描述见博客、源码）：<br>&nbsp; &nbsp; 1.导入优化后的开源库SlidingMenuLibrary；<br>&nbsp; &nbsp;2.因为侧滑菜单栏需要实现沉浸式效果，所以首先需要SlidingMenu依赖的Activity也实现沉浸式状态栏效果（4.4以上）；<br>&nbsp; &nbsp;3.初始化SlidingMenu实现侧滑菜单栏；<br>&nbsp; &nbsp;4.初始化侧滑菜单栏中按钮的点击事件：<br>&nbsp; &nbsp;5.返回键关闭处于开启状态的菜单栏：<br>&nbsp; &nbsp;6.在Fragment中开启侧滑菜单栏：<br>&nbsp; &nbsp; </body>
