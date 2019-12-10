#### 目前已有的css样式动画
- 雪碧图
- 旋转
- 上下浮动
- LOADING
- 趋势图

#### 查看demo
- 直接在html `open in browser`

#### 重复的动画样式可以使用css 预处理器函数处理
```css
/* stylus/ scss / less 定义 */

transX(name = translateX, start, end)
	@keyframes name {
		from {
			transform translateX(start)
		}
		to {
			transform translateX(end)
		}
	}

/* 引用 */
.class {
   transX(demoname, 0%, -100%)
}
```