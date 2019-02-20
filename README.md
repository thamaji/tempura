tempura
====

変数を雑に展開するだけの小さいテンプレートエンジン

指定したファイルの`{{環境変数}}`を展開して表示するだけ

### Example

```
$ cat template.txt 
Hello {{value}}!!
$ value=Japan ./tempura template.txt 
Hello Japan!!
```
