# Githubにエクスポートして同期してみよう！(chapter5-2)

`gitbook.com` + ローカルアプリが快適で、一人で何かを書くときにはもうこれでいいやとなっている気分を押し殺しながらGithub連携を試していくよ。

このチャプターはGithub連携を作成して、かつオンラインエディタで書き始めています。


## 連携する意味を考える

`gitbook.com`になくてgithubだけにあり、連携したほうが良い場合に使うもの。

- Pull Request
- gitリポジトリのViewer
- リリース
- マイルストーン

※ Issueにあたるものは`gitbook.com`でもdiscussionがある




## Githubにエクスポートする

設定画面からGithubの項目を選ぶと、エクスポートと連携設定ができる。ひとまずエクスポートだ。

Githubのインポーターに遷移するので、項目を埋めてcloneしよう。クローン時には認証を挟むため、`gitbook.com`側のアカウント情報を入力する必要がある。

![](github_impoter.jpg)

するとこのように、見慣れたGithubプロジェクトが完成する。

![](github_repo01.jpg)