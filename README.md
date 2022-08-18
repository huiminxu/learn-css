# learn-css
css-learning

# css 揭秘

## 前置
### 网站
https://developer.mozilla.org/en-US/docs/Web
https://webplatform.github.io/
https://modernizr.com/
https://caniuse.com/

### css 兼容
1. modernizr
2. 回退机制
``` {
background: rgb(255, 128, 0);   // 普通颜色
background: -moz-linear-gradient (odeg, yellow, red); //前缀
background:-0-linear-gradient(Odeg, yellow, red); //前缀
background:-webkit-linear-gradient (@deg, yellow, red); //前缀
background: linear-gradient (g0deg, yellow, red); 
}

3. js 检测某个样式是否支持
img!['https://user-images.githubusercontent.com/33274229/185279789-52ced9a4-f75a-43d0-a2b6-04e927bdb4ee.png']
<img width="465" alt="image" src="https://user-images.githubusercontent.com/33274229/185279789-52ced9a4-f75a-43d0-a2b6-04e927bdb4ee.png">
