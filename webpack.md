# 参数：

+ webpack --config XXX.js //使用另一份配置文件（比如webpack.config2.js）来打包
+ webpack -w
    webpack --watch //监听变动并自动打包
+ webpack -p//压缩混淆脚本，这个非常非常重要！
+ webpack -d//生成map映射文件，告知哪些模块被最终打包到哪里了其中的   提供SourceMaps，方便调试
+ webpack --progress //显示进度条
+ webpack --color //添加颜色，比如：会用红色显示耗时较长的步骤
+ webpack  --display-modules  //打包时显示隐藏的模块
+ webpack  --display-chunks   //打包时显示chunks
+ webpack  --display-error-details  //显示详细错误信息
+ webpack --profile //输出性能数据，可以看到每一步的耗时
+ webpack --mode //开发模式
    通过mode选项为webpack指定一些默认的配置。mode分为development/production,默认为production
    development:开发环境
    production:生产环境
