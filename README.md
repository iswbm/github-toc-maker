## 1. 主要用途

针对 Sphinx 博客的目录结构而制作的目录生成器。

## 2. 使用方法

下载 `github-toc-maker.py` 到你的本地仓库下面。

执行如下命令

```
$ python3 github-toc-maker-for-sphinx.py
```

就会将目录用 Mardown 的格式打印在终端上。

![](http://image.iswbm.com/20200811220536.png)



## 其他说明

1. 目前仅支持 Sphinx 风格的目录结构

   ```
   $ tree source/c*
   source/c01
   ├── c01_01.md
   ├── c01_02.md
   ├── c01_03.md
   ├── c01_04.md
   └── c01_05.md
   source/c02
   ├── c02_01.md
   ├── c02_02.md
   ├── c02_03.md
   ├── c02_04.md
   └── c02_05.md
   source/c03
   ├── c03_01.md
   ├── c03_02.md
   ├── c03_03.md
   ├── c03_04.md
   └── c03_05.md
   source/chapters
   ├── p01.rst
   ├── p02.rst
   └── p03.rst
   ```

   

