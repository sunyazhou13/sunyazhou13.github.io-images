前言
--
继上一篇[AVAudioPlayer](http://sunyazhou.com/2017/03/17/Learning%20AV%20Foundation(%E4%BA%8C)AVAudioPlayer/)之后本期内容是`AVAudioRecorder`

在`AV Foundation`中使用`AVAudioRecorder`类添加音频录制功能和使用`AVAudioPlayer`一样简单, 都是在`Audio Queue Server`上层构建的.同时支持`macOS`和`iOS`平台.可以从内置麦克风录制音频,也可以支持数字音频接口或USB外接麦克风录制.


创建
