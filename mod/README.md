# mod loader
## 430
mod loader  
是个 抽象 的概念，可以是任何“用来加载修改”的东西，比如 magisk xposed riru sandhook forge fabric sponge mixin 等东西  
要求必须 systemless  
一个实现 shml  
323  
另一个关于 噬神者 的实现  
218  
overlay/layer  
279  

早期都需要这些 注入 的方式来实现修改，但在 重写 之后直接内置了 mod api ，这才是真正的 mod loader (而不是抽象的)  
