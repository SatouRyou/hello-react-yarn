# hello-react-yarn

## 環境構築コマンドリスト

### プロジェクト作成
mkdir プロジェクト名  
cd プロジェクト名  

### npmインストール
yarn init  

### プロジェクト配下のフォルダを生成
mkdir src dist  

### プロジェクト配下のファイルを生成
touch ./src/app.js  
touch ./index.html  
touch .babelrc  
touch webpack.config.js

### ライブラリインストール
##### react用ライブラリ
yarn add react react-dom  

##### ビルド用ライブラリ  
yarn add webpack --dev  
yarn add babel-loader babel-core --dev  
yarn add babel-preset-react --dev  
yarn add babel-preset-es2015 --dev  
yarn add babel-preset-stage-0 --dev  
yarn add jsx-loader --dev  
yarn add node-sass --dev  

### 起動用コマンド
yarn run watch  
