## npm scripts
 - pull  
 紐づけたgasをpullしてくる

 - deploy  
 紐づけたgasにpush gasを開く

 ## 使い方


- claspとgoogleアカウントを紐づける
```
clasp login
```

- gas側でgasプロジェクト作る

- .clasp.jsonをルートに作成し以下を記述
```
{
  "scriptId":{project id},
  "rootDir": "./src/"
}
```
project idはgas側のファイル→プロジェクトのプロパティで表示されます。  
事故防ぎのため.clasp.jsonはignoreがおすすめ
