
# React 開発環境構築
https://qiita.com/rspmharada7645/items/25c496aee87973bcc7a5

1. Node.jsのインストール
https://nodejs.org/ja/

```確認コマンド
node -v
```

2. yarnをインストール
```console
# yarnをインストール
npm install --global yarn

# バージョン確認
yarn --version
```

3. creat-react-appのインストール

```console
yarn global add create-react-app
```

4. App.jsの修正
```javascript
import logo from './logo.svg';
import './App.css';

const App = () => {
  return (
    <div>
      <h1>Hello World</h1>
    </div>
  );
}

export default App;
```

# SpringBoot+gradle REST+JSON形式のAPIを呼び出してみる

Spring（入門コンテンツ）
gs-rest-service-complete

アドレス
http://localhost:8080/greeting

hello
http://localhost:8080/api/sample/hello


実行方法
cd helloworld
yarn start