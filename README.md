# Test Github Flow
## Github Flowとは
* [プルリクエスト／レビューを取り込んだ、よりシンプルなGitHub Flowの運用を図解する (1/2)](http://www.atmarkit.co.jp/ait/articles/1401/21/news042.html)

## 使い方
### Githubで新規にリポジトリを作成する
### ローカルにクローンする
    $ git clone git@github.com:fuji3zpg/githubflow.git # 例
    $ cd githubflow
### リポジトリを初期化
    $ git init
    $ git add README.md # README.mdに何か追記する。
    $ git commit -m "first commit"
    $ git push origin master # masterブランチをGithubにプッシュ
### 新ブランチの作成
    $ git checkout -b new1 # 新ブランチを作成して、new1をチェックアウトする
    $ git branch # new1ブランチが新たに作られていることを確認
    README.mdを変更する
    $ git commit -am "add comments to README"
### 新規作成したリポジトリをGithubにプッシュして共有する
    $ git push origin news
### Githubでプルリクエストし、masterブランチにマージする
    新ブランチをプッシュした人がプルリクエストを行う
    適切な人が新ブランチを検証して、問題なければ、masterブランチにマージする
