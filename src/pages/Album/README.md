本组件开发者：[daraluv](https://github.com/daraluv)   [任浩策(renhc729805143)](https://github.com/renhc729805143)

1. 如需要公用组件，随时和大家协商开发
2. 私有组件直接放在该目录下，所有私有组件的css样式直接写在style.scss中
3. 接口详情请阅读 `/static/apis/albumList 专辑列表获取.md`
4. 先开发列表功能，具体的播放功能稍后再说
5. 选择功能的实现参考 https://y.qq.com/portal/album_lib.html
6. 分页实现采用无限下滚的方式，希望能使用效率最高的方式，即保持固定的DOM数量但随着滚动修改数据的方式
