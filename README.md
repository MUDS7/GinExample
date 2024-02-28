go 官网上面的server的例子，第一次引用了第三方库，只需要go get .即可自动将该库下下来

## 设置国内的镜像

go env -w GOPROXY=https://goproxy.cn

## 问题

1. 引入第三方库的方法为何不能跳转，不能查看该方法的内容和返回值
2. 类型和命名和java rust是相反的，变量名在前 类型在后， 但是可以使用var来改为和常规的一致 <br/>
   例如: hello := "hello world!"  -> var hello string = "hello world!" <br/>
   这么做的意义是什么