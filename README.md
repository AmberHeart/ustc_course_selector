# ustc_course_selector
这是ustc的自动选课和换班程序，可以帮你抢到茶与健康或者把某些课换到你想换的班，同时目录中包含自动登录综合教务系统的程序，登录进去但不做任何操作  
代码的无配置版是指运行以后再输入学号、课程号等信息，无需改代码。这是发行版本release V1.0的源码，仅做为一个开源的展示（当然实在想用这个代码也可，不过正常人显然是要么直接用发行版，要么用自动选课.py）。如果有相应的python环境，不建议用发行版，因为从代码中设置的信息是可撤回的，设置错误可以快速改过来。  
原程序制作的环境是Python 3.6，selenium 3.141.0  
使用前请打开代码，根据注释填写学号、账户密码等信息，需要下载Google Chrome和对应版本的webdriver，下载地址是https://chromedriver.chromium.org/ ，可能需要翻墙，也可搜镜像网站进行下载。下载好后把它放到chrome以及python的安装目录，python需要安装selenium。如果只是想选课或换班，使用选课程序即可，自动登录程序只是便于登录上去做其他用途。  
注意自动选课程序会先换班再选课，如果选课要紧请交换两部分代码（两个for语句直接交换位置就好），此外，列表中的课程号应从前往后按重要性排序，最重要的放前面。注意：要求网速正常，任何页面在20秒内响应。
# 废理兴工，将来的教务系统必是计科人的天下！
