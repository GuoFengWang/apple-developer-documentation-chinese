#反馈

反馈帮助人们知道一个应用程序正在做什么，发现他们下一步可以做什么，并了解行动的结果。

**悄悄地整合状态和其他类型的反馈到你的接口。**理想情况下，用户不用采取行动或被中断，就可以得到重要信息。邮件，举个例子，当邮箱有信息投递进来时，可以巧妙地在工具栏中显示状态信息。这个信息虽然比不上屏幕上的主要内容，但是在任何时间都可以快速查看。

**避免不必要的警报。**警报是一个强大的反馈机制，但应仅用于传递重要的和理想的可操作的信息。如果人们看到太多不包含必要信息的警报，他们很快学会忽略未来的警报。有关额外的指导，请参见 [警报](https://developer.apple.com/ios/human-interface-guidelines/ui-views/alerts/) 。



![](https://developer.apple.com/ios/human-interface-guidelines/images/Feedback-Bottomhalf.png)



#触觉反馈
在支持的设备上，触觉提供了一种从物理上吸引住用户的方式，通过可以得到关注和加强行动的触觉反馈。一些系统提供的界面元素，如选择器，开关和滑块，当用户与他们交互时会自动提供触觉反馈。你的应用程序也可以要求系统产生不同类型的触觉反馈。iOS 来管理这个反馈的强度和行为。

**通知**
成功
<iframe height=498 width=510 src="https://developer.apple.com/ios/human-interface-guidelines/images/haptics/success.mp4">


<video width="320" height="240" controls>
    <source src="https://developer.apple.com/ios/human-interface-guidelines/images/haptics/success.mp4" type="video/mp4">
    您的浏览器不支持 video 标签。
</video>

警告

失败


**撞击**

轻

中

重


**选择**

选择


<video id="video" controls="" preload="none" poster="https://developer.apple.com/ios/human-interface-guidelines/images/haptics/error.png">
      <source id="mp4" src="https://developer.apple.com/ios/human-interface-guidelines/images/haptics/success.mp4" type="video/mp4">
      <source id="webm" src="http://media.w3.org/2010/05/sintel/trailer.webm" type="video/webm">
      <source id="ogv" src="http://media.w3.org/2010/05/sintel/trailer.ogv" type="video/ogg">
      <p>play</p>
    </video>
    

**成功**。任务或操作指示，如存放支票或解锁车辆，已完成。

**明智地使用触觉。**过度使用会导致混乱，降低反馈的意义

**在一般情况下，提供触觉反馈响应用户发起的动作。**人们很容易就会将触觉与他们发起的动作联系起来。任意的反馈会使人感觉到不连贯和被误解。

**不要重新定义反馈类型。**为了确保一致的体验，合理使用反馈类型。例如，不要使用“影响”反馈来通知用户任务成功了。相反，使用 “成功” 的变化 “通知” 反馈。

**微调您的视觉体验的触觉。**提供视觉和触觉反馈共同创造动作和结果之间的更深层次的联系。确保动画是顺畅的和精确的，视觉上符合用户的感觉。

**不要依赖单一的通讯方式**不是所有的设备支持全方位的触觉反馈，人们可以在设置中禁用全部功能，如果他们选择。此外，触觉反馈只有在设备处于活跃状态并且应用处于最前台的时候才会发生。补充触觉与视觉和听觉线索确保不错过重要信息。

**当视觉反馈被遮挡时可以使用触觉。**某些相互作用被用户的手指隐藏了，如拖动屏幕上的一个对象到一个位置上。考虑到生成反馈，让用户知道当他们到达某个特定的位置或值。

**在反馈开始前准备好系统。**因为在提供触觉反馈时可能会有一些延迟，所以在请求反馈之前最好先让系统准备好。否则，从用户的动作或他们在屏幕上看到的会感觉到触觉来的太晚和不连贯。 

**触觉与声音同步。**触觉与声音同步。触觉不自动同步的声音。如果你想要一个伴随的声音，你需要负责同步它。







