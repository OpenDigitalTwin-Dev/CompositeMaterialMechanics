# CompositeMaterialMechanics
Notes on Composite Material Mechanics

# 编译方法

使用 vscode 作为编辑器，并安装相关扩展，包括

```
Jupyter, MyST-Markdown, Python
```

在根目录安装 python 虚拟环境（推荐）

```
python -m venv .venv
```

激活环境

```
source .venv/bin/activate (Linux)
.\.venv\Scripts\activate (Windows)
```

安装 jupyter-book

```
pip install jupyter-book
```

检查安装是否成功

```
jupyter-book --version
```

生成网页（在 _build/_build/html 中查看）

```
jb build . 
```

清理


```
jb clean . 
```


CompositeMaterialMechanics 采用 CC BY-NC 4.0 国际许可协议授权。访问 https://creativecommons.org/licenses/by-nc/4.0/ 查看协议内容。

CompositeMaterialMechanics is licensed under CC BY-NC 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc/4.0/
