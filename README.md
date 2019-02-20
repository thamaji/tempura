tempura
====

変数を雑に展開するだけの小さいテンプレートエンジン

指定したファイルの`{{環境変数}}`を展開して表示するだけ

### Install

```
$ sudo curl -o /usr/local/bin/tempra -fSsl https://raw.githubusercontent.com/thamaji/tempura/master/tempura
$ sudo chmod +x /usr/local/bin/tempra
```

### Example

```
$ cat template.txt 
Hello {{value}}!!
$ value=Japan ./tempura template.txt 
Hello Japan!!
```
