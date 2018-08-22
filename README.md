# 微信小程序滚动广告组件
微信小程序目前仅提供了一种广告类型banner的Ad组件，一块区域只能显示一个广告。本组件实现的是滚动广告。

## Usage
- 1.[下载本组件](https://github.com/geekeren/mp-slider-ad-component/releases)

- 2.解压上一步下载的压缩包，在微信小程序项目根目录下新建 `components`文件夹
- 3.在需要使用本组件的page的json文件里面添加
```
"usingComponents": {
      "slider-ad": "/components/slider-ad/slider-ad"
}
```
- 4. 引用组件
```
 <slider-ad ads="{{ ['xxxx', 'xxx']}}" />
```

## Preview

