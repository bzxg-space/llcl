# 蓝链处理
> 部分地区蓝奏云文件(夹)分享链接无法访问，可通过改变域名使其可以访问
>
> 通过正则表达式来快速实现链接处理：[传送门1](https://bzxg-space.github.io/llcl)|[传送门2](https://bzxg-space.gitee.io/llcl)

## 处理方式

-  lanzous 中 `s` -> `i`/ `x`，即 lanzoui、lanzoux

```
原始：
	https://www.lanzous.com/b07x4tlyj
	https://bzxg.lanzous.com/b07x4tlyj
处理后：
	https://www.lanzoui.com/b07x4tlyj
	https://www.lanzoux.com/b07x4tlyj
	https://bzxg.lanzoui.com/b07x4tlyj
	https://bzxg.lanzoux.com/b07x4tlyj
```

- `lanzous` -> `lanzou`，`www`/`{个性域名}` -> `pan`

```
原始：
	https://www.lanzous.com/b07x4tlyj
	https://bzxg.lanzous.com/b07x4tlyj
处理后：
	https://pan.lanzou.com/b07x4tlyj
```

