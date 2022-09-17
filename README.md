# README

## vscodeファイル展開 手順書

- 【vscode】git clone "githubのファイルデータ"
- 【vscode】git code .

## ファイル作成git 手順書

- githubでrepositoryを作る

```shell
//現在のディレクトリを確認
pwd

//repositoryの複製
git clone 【git@github,com:ooonoo/ファイル名】

//vscodeを開く
code .
```


## branch 手順書

- コード等作成、訂正

```shell
git branch
git checkout -b 【branch名】
git branch
git add .
git comment -m "メッセージ"
git push origin HEAD
```

- githubでpull request
- pullrequestにissue番号を付ける
- githubでmarge

```shell
git branch
git checkout main
git branch
git pull origin main
git br -d  【branch名】
```
