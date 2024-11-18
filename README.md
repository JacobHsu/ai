# ai


## MkDocs

使用 MkDocs 部署到 GitHub Pages  
`$ mkdocs gh-deploy`

[Installation Guide](https://www.mkdocs.org/user-guide/installation/)  

```bash
$  python3 --version
Python 3.13.0
$  pip3 --version
pip 24.2 from /Library/Frameworks/Python.framework/Versions/3.13/lib/python3.13/site-packages/pip (python 3.13)
 ```

 ```bash
$ pip3 install mkdocs
Collecting mkdocs
  Downloading mkdocs-1.6.1-py3-none-any.whl.metadata (6.0 kB)
Collecting click>=7.0 (from mkdocs)
...
 ```

```bash
$ mkdocs new books 
$ cd books 
 ```

 ```bash
 $ mkdocs serve
 ```
 Serving on http://127.0.0.1:8000/

 ### theme

`$ pip3 install mkdocs-material`

yml

```js
theme:
  name: material
  custom_dir: overrides
  palette:
    primary: indigo
    accent: pink
  font:
    text: Roboto
    code: Roboto Mono
```

在專案根目錄下建立overrides資料夾，並在其中新增自訂的HTML/CSS/JS 檔案。例如：

`overrides/main.html`用於自訂模板。  
`overrides/extra.css`用於自訂樣式。  