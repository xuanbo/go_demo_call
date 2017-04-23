# go_demo_call

调用[`do_demo`](https://github.com/xuanbo/go_demo)。

## 1 gopath设置

参考[无闻](https://github.com/Unknwon)的单一项目结构，下面是我的gopath设置：

```
--gocode(gopath)

  --bin
  
  --pkg
  
  --src
  
    --github.com
    
      --xuanbo
      
        --go_demo(项目，git目录)
        
          --main.go(package go_demo)
          
        --go_demo_call(项目，调用了go_demo，git目录)
        
          --main.go(package main)
          
        --其他项目
```