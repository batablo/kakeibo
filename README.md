# kakeibo

## 概要
ReactとJavaを組み合わせて簡単な家計簿アプリケーションを作る。

環境が汚染されないようにDockerの中で開発を行う。

リポジトリの管理はGitで行う。

## 開発の簡単な流れ
1. Gitクローン（リポジトリは小畑作成）
1. Dockerで環境構築
1. 画面の設計（外部仕様書の作成）
1. マークアップ（見た目部分はmaterial-uiを使う）
1. APIの作成（サーバーサイドの実装）
1. フロントエンドとサーバーサイドの連携（axiosライブラリで連携させる）
1. テスト
1. 完成


## Gitチュートリアル（ターミナルで触れるようになろう！）
1. **git clone (リポジトリのURL)**  
  リモートリポジトリをローカルにコピーする。  
  URLは「Clone or download」ボタンから取得する。
1. **git log**  
  コミット履歴などを表示する。
1. **git ferch**  
  リモートリポジトリの情報を取得する。
1. **git pull**  
  リモートリポジトリの情報をローカルリポジトリへ反映する。
1. **git add 'ファイル名'**  
  ステージングエリアにファイルを追加する。  
  全ファイル・ディレクトリの選択は「git add .」  
  拡張子の指定は「git add *.'拡張子名'」
1. **git status**  
  ステージングエリアにあるファイルを確認する。
1. **git commit**  
  ステージングエリアのファイルをローカルリポジトリに登録する。  
  コミットメッセージの指定は「git commit -m 'コミットメッセージ'」  
  コミットメッセージの修正は「git commit --amend -m 'コミットメッセージ'」  
  直前のコミットの取り消しは「git commit --amend」
1. **git push**  
  ローカルリポジトリのコミット内容をリモートリポジトリへ反映する。
1. **git branch 'ブランチ名'**  
  ブランチを作成する。  
  ブランチ名の変更は「git branch -m 'ブランチ名'」  
  ブランチの削除は「git branch -d 'ブランチ名'」
1. **git merge 'ブランチ名'**  
  ブランチのコミット内容をマージする。  
  コンフリクトが発生して一旦戻す場合は「git merge --abort」
