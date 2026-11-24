# Daily Learning
## Morning planning
- [ ] 查看 [GitHub blog](https://github.blog/) 获取选题灵感
- [ ] 学习 [GitHub Pages](https://skills.github.com/#first-day-on-github) 的实用方法
- [ ] 将我的第一篇博客转化为网页
      <img alt="cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" height="85" align="right">
## Review
使用 [ffmpeg](https://www.ffmpeg.org) 将图片或者视频从深色模式转化为浅色模式
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
