hi there,it's the new pattern file that i fixed,hope can helpful to you

In the file, I adjusted the ballistic parameters,and it's suit for Season 15,but re45 is not working and i don't know how to deal with it

it's not the perfect,but better than the old,i think mgsweet can do better than me


**14赛季就在用这个，感觉效果挺好，但是15赛季作者还没有更新，我就自己就研究并改进了一下，虽然没有以前那种基本上都是打一个点，但是压枪效果还是有的**
>**原理如下**


**pattern文件夹内的TXT文件，压枪数据每一排都有三组**


**第一组代表鼠标X轴方向的位移，与实际位移方向相同**


**第二组代表鼠标Y轴方向的位移，注意这里标注的数据与鼠标移动的方向相反，例如你标注10，鼠标是往下移动的，这个要留意一下**


**第三组是鼠标每次移动的间隔时间，这个我不会研究，默认的是原来的参数，感觉大差不差**


**希望有兴趣的大佬可以帮助我一起改进，我自己做不到mgsweet那种效果，我估计他是有一种方法能计算子弹落点并通过坐标轴的方式描绘出来，我对这方面了解很少，所以不会计算，调试参数时全是凭感觉来，也花了我不少时间一点一点试，每次调试我都需要打完全部子弹来看一下效果，所以过程还是挺枯燥的**



**I used this in the 14th season and felt it had a good effect. However, the author of the 15th season has not been updated yet. I have studied and improved it myself. Although it is not the same as before, it is still effective**


>**The principle is as follows**


**There are three groups of press gun data in each row of TXT files in the pattern folder**




**The first group represents the X axis displacement of the mouse, which is the same as the actual displacement direction**




**The second group represents the displacement of the mouse in the Y axis direction. Note that the data marked here is opposite to the direction of the mouse movement. For example, if you mark 10, the mouse moves downward. Please pay attention to this**




**The third group is the time interval between each mouse movement. I won't study this. The default is the original parameters. I think it's not bad**




**I hope that interested leaders can help me to improve. I can't do the effect of mgsweep myself. I think he has a way to calculate the bullet impact point and describe it by the way of coordinate axis. I know little about this, so I can't calculate it. When debugging parameters, I rely on my feelings. It also takes me a lot of time to try it bit by bit. Every time I debug, I need to shoot all the bullets to see the effect, So the process is boring**


>**如何使用**


**替换AHK/SRC/pattern里面的同名文件**


>**HOW TO USE**


**just replace the same file that in the AHK/SRC/pattern**










>**更新日志**


**2022.11.6**


**我先是上次了压枪参数的第一个版本，但是后来发现还是要一些改进，所以几个小时的调试后上传了新的**


**2022.11.12**


**查看以往发布的帖子发现mgsweet的压枪也是别人的压枪修改了一下做出来的，比原作者Tientie的压枪方式更方便简洁，原作者也对mgsweet的压枪方式给予了肯定并在后续更新中也借用了部分mgsweet的代码，我深入学习了原作者Tientie所阐述的它的压枪原理，简单点来说就是利用AE的图像追踪功能实现枪械弹道坐标点的反导出，也就是说导出的坐标数据是与枪械打出去的弹道相反，再写入脚本，实现压枪，但图像追踪准确性不高，每次导出坐标数据后我又手动修改并不断测试，得到了11.12版本的压枪，这与我之前毫无头绪的调试相比，效果无疑是非常棒的**



>**Update Log**



**2022.11.6**


**First i upload the first version,then i improved some of them and update again hours later**



**2022.11.12**


**After reviewing the previous posts, we found that the press gun of mgsweet was also modified by someone else, which is more convenient and concise than the press gun method of the original author Tientie. The original author also affirmed the press gun method of mgsweet and borrowed some code of mgsweet in the subsequent updates. I deeply learned its press gun principle described by the original author Tientie, To put it simply, the AE image tracking function is used to realize the inverse export of the gun ballistic coordinate points. That is to say, the exported coordinate data is contrary to the trajectory of the gun, and then the script is written to achieve gun pressing. However, the accuracy of image tracking is not high. Every time I export the coordinate data, I manually modify and continuously test, and get the 11.12 gun pressing. Compared with my previous debugging without clue, the effect is undoubtedly very good**


