# fetch&&mergeの仕方

## 1.最新情報をローカルに持ってくる
```rb:ターミナル
git fetch origin main
```

## 全ての情報を取ってくる場合
```rb:ターミナル
git pull origin main
```

# ここからはpushの仕方


## 1.コードをpushする場合
```rb:ターミナル
git add -p
```

## 1.ファイルをpushする場合
```rb:ターミナル
git add ファイル名
```

## 1.全てのファイルをpushする場合
```rb:ターミナル
git add .
```

## 2.commitする
```rb:ターミナル
git commit -m "〇〇"
```

## 3.pushする
```rb:ターミナル
git push origin ブランチ名
```
