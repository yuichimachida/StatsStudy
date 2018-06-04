#Python
HomebrewでPython3をインストールしたはずだが、IDLEを実行すると2系が実行される。

[参考URL](https://gist.github.com/mignonstyle/083c9e1651d7734f84c99b8cf49d57fa)

```$ python --version``` すると  
``` 2.7.10 ```
と帰ってくるので、デフォルトのPythonが2であるようだ。
so, then I tied   
```$ brew install python3```  
terminal show warning and said 3 is already installed.
It suggested reinstall ```$brew reinstall python```  
it's not Python3; ```python```  

So, I tried reinstall that. But failed, still IDLE work on ```2.7.10```

[memo](https://qiita.com/spyc/items/73d1295f8b3dde3b49ca)

結局Python3をインストーラで入れてIDLE3が通ったって話。
