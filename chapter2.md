# さあ、新しいチャプターを！

とりあえずチャプター1を自分の文章に編集し、Publishしてみた。
内容は編集した通りで、TOCが次のようにデフォルトのままだ。

- Introduction
    1. First Chapter

むむ、チャプタ−１は`まず俺は間違っていた`でなければならない。どうやらチャプター2ではその変更の仕方を調べていく必要があるな。


## chapter2のファイルを作成する

エディタのファイルツリー部分で**右クリック**すると、コンテキストメニューが登場。ここからファイルの新規作成ができた。

![Add new File](new_chapter.jpg)

内容はこのチャプターだ。方法を調べながら書き進めている。

## SUMMARY.mdを編集する

ファイル一覧を観察すると、`SUMMARY.md`というファイルがある。怪しい。

内容を確認する。

```markdown:SUMMARY.md
# Summary

* [First Chapter](chapter1.md)
```

おそらくGitBook上で公開する場合のTOCはこれが使われるのだと推測、次のように編集した。

```
# Summary

* [まず俺は間違っていた](chapter1.md)
* [チャプターを追加＆TOCのタイトルを変えたい](chapter2.md)
```

よし、更新されたぞ。

![Update TOC](update_toc.jpg)


ツリーに階層をつけたらどうなるんだろうか？

