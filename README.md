# mdplain
convert markdown string to plain text 转换markdown文本成纯文本
# install
download and run the command:
```
python setup.py install
```
# use 使用
```
from mdplain import plain
md = '''# helloworld
**bord**

*test*
> markdown text
'''
print(plain(md))
```
