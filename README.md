# summary
about daily question：
angular + ionic 实现彩蛋声音的尝试
起初想用前端代码解决，经尝试可以实现，只是需要用户手动触发才会让audio自动播放，鉴于页面是一个路由跳转，进来必须有声音，所以寻求了原生的建议，原生那边只需要将浏览器关于用户操作和视频音频的属性设置改一下就好了，即
config.allowsInlineMediaPlayback = true;
config.mediaPlaybackRequiresUserAction = false;
版本已上线，问题成功解决
