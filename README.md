# create-vue-development
このrepositoryはvueの環境構築やvueの基礎について記載しています。

■Vueの開発を行うには
vueで開発を行う方法はスクラッチからVueのアプリケーションを構築する方法とVue CLIを使用する方法が存在する。
Vue CLIを使用すれば開発に必要な前準備をしてくれプロジェクトで利用する機能のインストール(必要な機能のみを選択)も一緒に行うこと
ができる。なので、今回はVue CLIを使用する。

■Vue CLIのインストール
Vue CLIを使用を使用するには、Vue CLIのインストールを行う必要があります。インストールにはnode.js、npmが必要となります。node.jsとnpmがインストールされているかどうかはnode -v, npm -vコマンドで確認することができます。コマンドを実行してバージョンが表示されればインストールは完了しています。
今回はnodebrewを使用してnode.js npmをインストールします。(node.jsをインストールするとnpmも一緒にインストールされる)
nodebrewとは、node.jsのバージョンを管理することができるパッケージツール。
nodebrewのインストールはHomobrewで使用しインストールする。
npmが使える環境でVue CLIのインストールを行います。インストールが終わった後は、vue –versionを実行しバージョン情報が表示されているか確認を行ってください。（コマンドはnpm install -g @vue/cli）


■プロジェクトの作成
Vue CLIのインストールが完了したらプロジェクトの作成を行います。
コマンドはvue create [プロジェクト名]
コマンド実行後、vueのバージョン指定やモジュールの洗濯を行うことができる。
・Babel
・Progressive Web App (PWA) Support・・・Nativeアプリ 同様のUXをユーザーに提供するためのものモジュール
・Router
・Vuex
・CSS Pre-processors・・・sassなどのcssを使用する際にするものモジュール
・Linter / Formatter
・Unit Testing・・・unitテストを行うためのものモジュール
・E2E Testing・・・総合テストのモジュール
以上のモジュールが選択することができる。


