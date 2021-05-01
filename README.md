# Haskell.md
# 公式サイト
[https://www.haskell.org/](https://www.haskell.org/)  
[https://haskell-jp.slack.com](https://haskell-jp.slack.com)  
[http://learnyouahaskell.com/](http://learnyouahaskell.com/)  
[http://book.realworldhaskell.org/read/](http://book.realworldhaskell.org/read/)  
[https://www.yesodweb.com/](https://www.yesodweb.com/)  
[https://wiki.haskell.org/Haskell](https://wiki.haskell.org/Haskell)  
[https://hackage.haskell.org](https://hackage.haskell.org)  
[https://hoogle.haskell.org](https://hoogle.haskell.org)  
[https://www.haskell.org/tutorial/](https://www.haskell.org/tutorial/)  
[http://www.sampou.org/haskell/tutorial-j/](http://www.sampou.org/haskell/tutorial-j/)  
[http://dev.stephendiehl.com/hask/](http://dev.stephendiehl.com/hask/)  
[https://haskell.jp/](https://haskell.jp/)  
# 参考サイト
[http://www.shido.info/hs/index.html](http://www.shido.info/hs/index.html)  
[http://www.nct9.ne.jp/m_hiroi/](http://www.nct9.ne.jp/m_hiroi/)  
[https://tech.nikkeibp.co.jp/it/article/COLUMN/20060801/244810/?TOC=3](https://tech.nikkeibp.co.jp/it/article/COLUMN/20060801/244810/?TOC=3)  
[https://wiki.haskell.org/Haskell%E5%85%A5%E9%96%80_5%E3%82%B9%E3%83%86%E3%83%83%E3%83%97](https://wiki.haskell.org/Haskell%E5%85%A5%E9%96%80_5%E3%82%B9%E3%83%86%E3%83%83%E3%83%97)  
[https://qiita.com/7shi/items/145f1234f8ec2af923ef](https://qiita.com/7shi/items/145f1234f8ec2af923ef)  
[http://gihyo.jp/dev/feature/01/functional-prog/0001?page=1](http://gihyo.jp/dev/feature/01/functional-prog/0001?page=1)  
[https://qiita.com/waddlaw/items/e47552cb26c1d58ece0b](https://qiita.com/waddlaw/items/e47552cb26c1d58ece0b)  
[http://www.techscore.com/blog/2013/06/11/yesod%E5%85%A5%E9%96%80-1-%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%8B%E3%82%89%E8%B5%B7%E5%8B%95%E3%81%BE%E3%81%A7/](http://www.techscore.com/blog/2013/06/11/yesod%E5%85%A5%E9%96%80-1-%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%8B%E3%82%89%E8%B5%B7%E5%8B%95%E3%81%BE%E3%81%A7/)  
[https://www.haskell.org/definition/haskell2010.pdf](https://www.haskell.org/definition/haskell2010.pdf)  
[http://labs.gree.jp/blog/2013/12/9201/](http://labs.gree.jp/blog/2013/12/9201/)  
[http://walk.northcol.org/](http://walk.northcol.org/)  
[http://www.happylearnhaskelltutorial.com/](http://www.happylearnhaskelltutorial.com/)  
[http://mitsuji.org/?cat=7](http://mitsuji.org/?cat=7)  
[https://qh73xebitbucketorg.readthedocs.io/ja/latest/1.Programmings/haskell/main/](https://qh73xebitbucketorg.readthedocs.io/ja/latest/1.Programmings/haskell/main/)  
[https://www.sampou.org/haskell/a-a-monads/html/index.html](https://www.sampou.org/haskell/a-a-monads/html/index.html)  
[https://qiita.com/hiruberuto/items/26a813ab2b188ca39019](https://qiita.com/hiruberuto/items/26a813ab2b188ca39019)  
[http://d.hatena.ne.jp/wvogel00/?of=60](http://d.hatena.ne.jp/wvogel00/?of=60)  
## Haskell :: Reddit
[https://www.reddit.com/r/haskell/](https://www.reddit.com/r/haskell/)  
# 書籍
## 入門Haskellプログラミング
サンプルコード  
[https://www.manning.com/downloads/1472](https://www.manning.com/downloads/1472)  
# グループへの参加
[http://haskell.g.hatena.ne.jp/about](http://haskell.g.hatena.ne.jp/about)  
# GHC
参考サイト  
[http://www.kotha.net/ghcguide_ja/7.0.4/](http://www.kotha.net/ghcguide_ja/7.0.4/)  
## CentOS7
### 起動の仕方

```
ghci
```
### 終了

```
:quit
```
GHC参考サイト  
[https://ghcguide.haskell.jp/8.2.2/users_guide/index.html](https://ghcguide.haskell.jp/8.2.2/users_guide/index.html)  
# 1から10までの数を表示する

```
[1..10]
```
# Windows32ビットマシンへのインストール

```
http://lambda.haskell.org/platform/download/2013.2.0.0/HaskellPlatform-2013.2.0.0-setup.exe
```
# ltsのバージョンを指定いてプロジェクトの作成（Windows32ビット）

```
stack new プロジェクト名 --resolver lts-9.21
```
またはstack.yamlファイルで指定  
stack.yaml  

```
resolver: lts-9.21
packages:
- .
```
## ltsのバージョン

```
lts-16.2 ghc-8.8.3
lts-15.5 ghc-8.8.3
lts-15.4 ghc-
LTS 15.3 for ghc-8.8.2
lts-14.14 ghc-8.6.5
lts-13.19 ghc-8.6.4
lts-13.11 ghc-8.6.3
lts-12.26 ghc-8.4.4
lts-12.14 ghc-8.4.3
lts-11.22 ghc-8.2.2
lts-9.21 ghc-8.0.2
lts-7.24 ghc-8.0.1
lts-6.35 ghc-7.10.3
lts-3.22 ghc-7.10.2
lts-2.22 ghc-7.8.4
lts-0.7 ghc-7.8.3
```
[https://www.stackage.org/](https://www.stackage.org/)  
### ltsの設定場所
stack.yaml  
# 2つの数値を加算する。

```
let add x y = x + y
add 2 3
```
→ 5 と表示される。  
# stack   
[Home - The Haskell Tool Stack(https://docs.haskellstack.org/en/stable/README/)](https://docs.haskellstack.org/en/stable/README/)  
[Releases · commercialhaskell/stack(https://github.com/commercialhaskell/stack/releases)](https://github.com/commercialhaskell/stack/releases)  
[WindowsでのHaskell開発環境構築(2017年秋版) - モナドとわたしとコモナド](http://fumieval.hatenablog.com/entry/2017/10/11/230117)
### インストール
リリースノート  
[Releases · commercialhaskell/stack](https://github.com/commercialhaskell/stack/releases)  
  
```
curl -sSL https://s3.amazonaws.com/download.fpcomplete.com/centos/6/fpco.repo | sudo tee /etc/yum.repos.d/fpco.repo
sudo yum -y install stack
```
[https://yoheikoga.github.io/2016/08/14/haskell-on-centos/](https://yoheikoga.github.io/2016/08/14/haskell-on-centos/)  
[http://docs.haskellstack.org/en/stable/install_and_upgrade/](http://docs.haskellstack.org/en/stable/install_and_upgrade/)  
  
```
curl -sSL https://get.haskellstack.org/ | sh
```
または  

```
wget -qO- https://get.haskellstack.org/ | sh
```
[https://docs.haskellstack.org/en/stable/README/](https://docs.haskellstack.org/en/stable/README/)  
### stackバージョン
1.9.3 lts-12.24 ghc-8.4.4  
1.9.0.1  Winsows7_32bit_NG  
1.7.1  Winsows7_32bit_NG  CentOS6_NG CentOS7_OK
1.6.5  Winsows7 32bit NG  
1.6.3  
1.6.1  
1.5.1  Winsows7 32bit OK lts-9.21  
1.5.0  
1.4.0  
1.3.2  Winsows7 32bit OK
  
Windows 32Bitではプロジェクトの作成はできるが、コンパイル、実行はできない。  
### stackインストール
#### CentOS7

```
curl -sSL https://get.haskellstack.org/ | sh
```
### バージョンの確認

```
stack --version
```
stackのghcのバージョン確認  

```
stack ghc -- --version
```
[https://qiita.com/usamik26/items/672ed3c4451402bfc275](https://qiita.com/usamik26/items/672ed3c4451402bfc275)  
### バージョン指定でアップデート

```
stack upgrade --binary-version 1.7.1
```
### プロジェクトの作成からビルド、実行　HelloWorld  

```
stack update
stack new my-project
cd my-project
stack setup
stack build
stack exec my-project-exe
```
[https://docs.haskellstack.org/en/stable/README/](https://docs.haskellstack.org/en/stable/README/)  
  
stack exec コマンドは下記のように使用する。  

```
stack exec プロジェクト名-exe
```
「プロジェクト名-exe」の部分は「package.yamal」ファイル内で指定するらしい  
  
設定例  

```
executables:
  hjack-exe:
```
実行結果  

```
someFunc
```
と表示される  
  

### バージョンの確認

```
stack --version
```
### stack templates
テンプレートの種類を表示する  

```
[apo@localhost hs_Mysql4]$ stack templates
Template                    Description
chrisdone
foundation                - Project based on an alternative prelude with batteries and no dependencies.
franklinchen
ghcjs                     - Haskell to JavaScript compiler, based on GHC
ghcjs-old-base
hakyll-template           - a static website compiler library
haskeleton                - a project skeleton for Haskell packages
hspec                     - a testing framework for Haskell inspired by the Ruby library RSpec
new-template
protolude                 - Project using a custom Prelude based on the Protolude library
quickcheck-test-framework - a library for random testing of program properties
readme-lhs                - small scale, quick start, literate haskell projects
rio                       - Application template using the RIO monad. Has logging and options parsing.
rubik
scotty-hello-world
scotty-hspec-wai
servant                   - a set of packages for declaring web APIs at the type-level
servant-docker
simple
simple-hpack
simple-library
spock                     - a lightweight web framework
tasty-discover            - a project with tasty-discover with setup
tasty-travis
unicode-syntax-exe
unicode-syntax-lib
yesod-minimal
yesod-mongo
yesod-mysql
yesod-postgres
yesod-simple
yesod-sqlite
```
### stackでプロジェクトを作成するときの注意
パスに漢字が含まれるとビルドが失敗する。  
パスには漢字を含めないこと。  
### --bare オプション
「--bare」を付けるとフォルダを作成せずにファイルを作成する

```
stack new my-project --bare
```
[https://sharpknock.com/posts/programming/hrr.html](https://sharpknock.com/posts/programming/hrr.html)  
### stack RedownloadFailed Request
現象

```
[apo@arch my-project]$ stack build
Downloading lts-16.20 build plan ...
RedownloadFailed Request {
  host                 = "raw.githubusercontent.com"
  port                 = 443
  secure               = True
  requestHeaders       = []
  path                 = "/fpco/lts-haskell/master//lts-16.20.yaml"
  queryString          = ""
  method               = "GET"
  proxy                = Nothing
  rawBody              = False
  redirectCount        = 10
  responseTimeout      = ResponseTimeoutDefault
  requestVersion       = HTTP/1.1
}
 "/home/apo/.stack/build-plan/lts-16.20.yaml" (Response {responseStatus = Status {statusCode = 404, statusMessage = "Not Found"}, responseVersion = HTTP/1.1, responseHeaders = [("Connection","keep-alive"),("Content-Length","14"),("Content-Type","text/plain; charset=utf-8"),("Content-Security-Policy","default-src 'none'; style-src 'unsafe-inline'; sandbox"),("Strict-Transport-Security","max-age=31536000"),("X-Content-Type-Options","nosniff"),("X-Frame-Options","deny"),("X-XSS-Protection","1; mode=block"),("Via","1.1 varnish (Varnish/6.0), 1.1 varnish"),("X-GitHub-Request-Id","F1D8:6AF6:38BB9C:40F945:5F961FFB"),("Accept-Ranges","bytes"),("Date","Mon, 26 Oct 2020 01:02:21 GMT"),("X-Served-By","cache-itm18821-ITM"),("X-Cache","HIT, HIT"),("X-Cache-Hits","1, 1"),("X-Timer","S1603674142.838377,VS0,VE1"),("Vary","Authorization,Accept-Encoding"),("Access-Control-Allow-Origin","*"),("X-Fastly-Request-ID","84c28ef44c16e05ff518ec96ab4accd2de1a2456"),("Expires","Mon, 26 Oct 2020 01:07:21 GMT"),("Source-Age","33")], responseBody = (), responseCookieJar = CJ {expose = []}, responseClose' = ResponseClose})
```
[https://stackoverflow.com/questions/57516944/stack-new-command-failing-to-download-build-plan-for-lts-14-1](https://stackoverflow.com/questions/57516944/stack-new-command-failing-to-download-build-plan-for-lts-14-1)  
~/.bash_profile  

```
PATH=/usr/local/bin/stack:$PATH
```
## デフォルトファイル

```
stack new my-project
```
./app/Main.hs

```
module Main where

import Lib

main :: IO ()
main = someFunc
```
./src/Lib.hs

```
module Lib(someFunc) where

someFunc :: IO ()
someFunc = putStrLn "someFunc"
```

```
stack build
stack exec my-project-exe
```
# if式
Main.hs  

```
module Main where

main :: IO ()
main = do
    let a = 5
    if a < 10
        then print "under 10"
        else print "over 10"
```
## sample

```
module Main where

import Lib

ifr x = if (x<10)
            then x + 1
            else x - 1


main :: IO ()
main = do
    someFunc

    let a = ifr 8
    print a
```

```
someFunc
9
```
# パッケージのインストール

```
stack ghci --package HUnit
```
### stackの主なコマンド
stack new : プロジェクトをテンプレートから新規作成する。  
stack init : プロジェクトをテンプレートを使わずに新規作成する。  
stack setup : プロジェクトで指定されたバージョンのコンパイラや基本パッケージをインストールする。  
stack build : プロジェクトをビルドする。  
stack install : プロジェクトをビルドして local-bin にインストールする。  
stack upgrade : stackコマンドの更新  
[本気で Haskell したい人向けの Stack チュートリアル - Qiita](https://qiita.com/waddlaw/items/49874f4cf9b680e4b015)  
[Haskell Stack とは何をするツールなのか - Qiita(https://qiita.com/usamik26/items/672ed3c4451402bfc275)](https://qiita.com/usamik26/items/672ed3c4451402bfc275)  
# module
## moduleの設定
例）Network.Socket
Main.hs

```
import Network.Socket
```
package.yaml

```
dependencies:
- base >= 4.7 && < 5
- network
```
パッケージ名の検索方法  
[hoogle](https://www.haskell.org/hoogle/)で検索
![エビフライトライアングル](https://bitbucket.org/ringo-apo/pictures/raw/46dce03410c5c280c125c1518360b8d5d631bf19/20190628_1.png "サンプル")
↓  
![エビフライトライアングル](https://bitbucket.org/ringo-apo/pictures/raw/46dce03410c5c280c125c1518360b8d5d631bf19/20190628_2.png "サンプル")  
  
package.yamlファイルに  
「- network 3.1.0.1」または「- network」とだけ書く。  
  
### moduleのインストール

```
stack install xxx
stack install lens --小文字で書くこと
```
### プログラム中にmodule(Control.Lens)を入れる
package.yaml

```
dependencies:
- lens
```
# Windws 32bitでの実行
## コンパイル

```
ghc hello.hs
```
## 実行

```
hello.exe
```
# キーボードから入力する  

```
name <- getLine
putStrLn ("Hey " ++ name ++ ", you rock!")
```
## キーボードから入力した数値に定数を加える

```
apo@gentoo ~/Documents/project/make/haskell/effect/my-project $ cat ./app/Main.hs
module Main where

main :: IO ()
main = do

    print ("Please input some one number.")
    a <- getLine
    let b = read a :: Int

    let c = 1
    let d = b + c

    putStrLn (show (d))
apo@gentoo ~/Documents/project/make/haskell/effect/my-project $ stack exec my-project-exe
"Please input some one number."
1
2
```
# メインファイル
メインとなるファイルの頭には'Main'といれなければならない。
デフォルトではファイル名が入っている。
そうでなければexeファイルが作成されない

```
module Main where
```
## stackアンインストール
アンインストールは、通常のWindowsアプリケーションと同じように、コントロールパネルから行います。  
処理完了後、下記のフォルダが残っている場合は手動で削除します。  
%HOME%\AppData\Local\Programs\stack  
%HOME%\AppData\Roaming\local\bin  
また、環境変数STACK_ROOTを設定していた場合、該当フォルダ(デフォルトはC:\sr)も削除します。  
[01. 環境構築 - とりあえず雑記帳(https://sites.google.com/site/toriaezuzakki/haskell/environment)](https://sites.google.com/site/toriaezuzakki/haskell/environment)  
  
### 設定ファイル

```
C:\Users\taira_akira.NAGO_ETECH\AppData\Roaming\stack\config.yaml
```
### CentOSでのアンインストール

```
yum remove stack
```
# Haskell Platform
ghc,cabal,stackを扱うプラットフォーム  
[Download Haskell Platform(https://www.haskell.org/platform/)](https://www.haskell.org/platform/)  
[Haskell Platform - Included Packages](https://www.haskell.org/platform/prior.html)  
## インストール
[CentOS7にHaskell Platform最新版をインストール - takafumi blog](http://takafumi-s.hatenablog.com/entry/2015/04/28/005143)  
[CentOSでHaskellプログラミング始め | ぬわーーーーーーー！！！](https://yoheikoga.github.io/2016/08/14/haskell-on-centos/)  

```
sudo yum install haskell-platform
```
## バージョンの確認

```
ghc --version
```
## Haskell Platformをインストール
下記リンクからダウンロード
[https://www.haskell.org/platform/prior.html](https://www.haskell.org/platform/prior.html)  
「Linux,64bit」fullを選ぶこと
tar -xvf xxx.bzで解答

```
./install-haskell-platform.sh
```
を実行  
[http://appdesign.jp/wxhaskell/wxhaskell_linux.php](http://appdesign.jp/wxhaskell/wxhaskell_linux.php)  
# wxHaskell
[http://appdesign.jp/wxhaskell/wxhaskell_linux.php](http://appdesign.jp/wxhaskell/wxhaskell_linux.php)  
# Haskell Platformでプログラムを作成
Windows 32Bitで作成、実行可能  
## IntelliJで新規作成
Build with Cabalを選択する  
こうなる  

```
import Distribution.Simple
main = defaultMain
```
# Stackが使えない環境で実行するには
Main.hsがあるフォルダに移動し、

```
ghc Main.hs ../src/Lib.hs
Main.exe
```
とする。
## cabalのインストール
[Haskell Platform や パッケージ管理システムを使わずに GHC と Cabal をインストールする &#8211; CentOS 7 編 &#8211; mitsuji.org](http://mitsuji.org/?p=45)  
  
```
curl https://gitlab.haskell.org/haskell/ghcup/raw/master/bootstrap-haskell -sSf | sh
```
[https://github.com/haskell/ghcup](https://github.com/haskell/ghcup)  
# Cabal
[The Haskell Cabal(https://www.haskell.org/cabal/)](https://www.haskell.org/cabal/)  
  
```
cabal --version
```

```
cabal update
```

```
cabal install Cabal cabal-install
```
# cabal sandbox
[https://www.haskell.org/cabal/users-guide/installing-packages.html](https://www.haskell.org/cabal/users-guide/installing-packages.html)  
開発対象ごとにパッケージデータベースを分離することができる。

```
cabal sandbox init
```
[Cabal sandboxを使ってHaskellのパッケージをいい感じに管理する - Labo Memo](http://alice345.hatenablog.com/entry/2015/02/05/084723)  
## フォルダを作ってそこでcabalを使う

```
cabal update
mkdir cabal_test
cd cabal_test
cabal sandbox init
cabal init
cabal install --only-dependencies
cabal run
```
[Cabal sandboxを使ってHaskellのパッケージをいい感じに管理する - Labo Memo](http://alice345.hatenablog.com/entry/2015/02/05/084723)  
## moduleのインストール

```
cabal install xxx
cabal install lens --小文字で書くこと
```
# テキストファイルの読み込み

```
module Main where

main :: IO ()
main = do

    str <- readFile "test.txt"
    putStrLn str
```

```
apo@gentoo ~/Documents/project/make/haskell/textRead/my-project $ cat ./test.txt
hello
haskell

apo@gentoo ~/Documents/project/make/haskell/textRead/my-project $ stack exec my-project-exe
hello
haskell
```
例2  

```
main = do
    cs <- getContents
    putStr cs
```
実行の仕方  

```
stack exec my-project-exe < ./test.txt
```
参考「ふつうのHaskellプログラミング」p29  
# テキストファイルの作成
./app/Main.hs

```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    writeFile "./test.txt" "Hello, Haskell!"
```
# openFile
sample.txtの内容に行番号を付与しながら出力する。  

```
apo@gentoo ~/Documents/project/make/haskell/openFile/my-project $ cat ./app/Main.hs
module Main where

import System.IO

main :: IO ()
main = do

    h <- openFile "sample.txt" ReadMode
    loop 0 h
    hClose h
    where
      loop :: Int -> Handle -> IO ()
      loop i h = do
        eof <- hIsEOF h
        if not eof
          then do
            s <- hGetLine h
            putStrLn $ show i ++ " : " ++ s
            loop (i + 1) h
          else return ()
apo@gentoo ~/Documents/project/make/haskell/openFile/my-project $ cat sample.txt
hello
apple
banana
pen
desk
apo@gentoo ~/Documents/project/make/haskell/openFile/my-project $ stack exec my-project-exe
0 : hello
1 : apple
2 : banana
3 : pen
4 : desk
```
Haskell入門 p146  
# 文字→数値　変換

```
read a :: Int
```
使用例  

```
module Main where

main = do
    a <- getLine
    print ((read a :: Int) + 1)
```
文字列→数値、代入  

```
module Main where

main = do

    print ("Please input some one number.")
    a <- getLine
    let b = read a :: Int
    print (b + 1)
```
[Haskell Tips (文字列編) - りんごがでている](http://bicycle1885.hatenablog.com/entry/2012/12/24/234707)  
[1. Haskell](https://sites.google.com/site/toriaezuzakki/haskell?tmpl=%2Fsystem%2Fapp%2Ftemplates%2Fprint%2F&showPrintDialog=1)  
# 数値→文字列の変換

```
let score = 100
print("score is " ++ (show score))
```
## 数値 -> Text
package.yaml

```
dependencies:
- text
```
Main.hs

```
import Data.Text

Data.Text.pack (show int)
```
# 関数の定義

```
abc a b c d e = a + b + c + d + e

abc 1 2 3 4 5
15
```
# 再帰(Recursion)
n回繰り返す
キーボードに入力した数字から1までカウントダウンしながら繰り返し、数字を表示する  

```
module Main where

kansu x = do
    print x
    if x == 1
        then print "end"
        else kansu (x-1)

main :: IO ()
main = do
    a <- getLine
    let b = read a :: Int
    print ""
    kansu $ b
```
[https://github.com/ringo-apo/20180330_hs_recursion](https://github.com/ringo-apo/20180330_hs_recursion)  
## repeat
無限リストを作る  

```
module Main where

repeat' :: a -> [a]
repeat' x = x : repeat' x

main :: IO ()
main = do
     let a = 5
     let b = take 10 ( repeat' a )
     print b

```
## 階乗

```
module Main where

main :: IO ()
main = do
     let a = fact 10
     print a

fact n | n <=1 = n
       | otherwise = n * fact ( n - 1 )
```
## 10個の乱数リストを作成し、再帰を使って1個づつ表示する

```
module Main where

import Lib
import System.Random.MWC
import Data.List
import System.Random

loop x = do
     if x == []
     	  then print "end"
	  else do
	       print (head x)
	       loop (tail x)

main :: IO ()
main = do
     someFunc
     let a = take 10 ( randomRs (1,6) (mkStdGen 7) :: [Int] )
     print a

     loop a      
```
# 文字を表示する
## print  

```
print("hello")
```

```
"hello"
```
※日本語を表示させるのはむずかしい。  
## putStrLn

```
putStrLn("hello")
```

```
hello
```

```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    let a = [5 ,2 ,5 ,3 ,6 ,4]

    let b = map (+3) [1,2,3]::[Int]

    putStrLn (show b)
```

```
someFunc
[4,5,6]
```
# 現在時刻を表示する
package.yaml

```
dependencies:
- time
```
Main.hs

```
import Data.Time

main :: IO ()
main = do
    zonedTime <- getZonedTime
    print zonedTime
```
# 関数の使い方  

```
module Main where

add :: Int -> Int -> Int
add x y = x + y

main = do
    print ("Please input some two numbers.")
    a <- getLine
    b <- getLine
    let c = read a :: Int
    let d = read b :: Int
    let e = add c d
    print (e)
```
# Mainプログラム内でループさせる

```
module Main where

import System.Random

randAlpha = getStdRandom $ randomR ('a', 'z')

main = do
    r <- randAlpha
    print r
    if r == 'z' then print "END" else main
```
# up,downを入力するたびに数値がインクリメント、デクリメントする

```
module Main where

import Control.Monad.State
import System.Environment
import Data.Char

main :: IO ()
main = do
    xs <- getContents >>= return . lines
    counter 0 xs

counter :: Int -> [String] -> IO ()
counter _ [] = return ()
counter i ("up":xs) = print (i + 1) >> counter (i + 1) xs
counter i ("down":xs) = print (i - 1) >> counter (i - 1) xs
counter i (_:xs) = counter i xs
```
Haskell入門ｐ143  
# データベースを使う  
[Haskell から MySQL を使う - Qiita(https://qiita.com/lotz/items/a24c98dde8bd7e9ae089)](https://qiita.com/lotz/items/a24c98dde8bd7e9ae089)  
[Haskellで実装された MySQL ドライバ mysql-haskell を試してみた - Qiita(https://qiita.com/lotz/items/1d9c7b4333fd4d29a150)](https://qiita.com/lotz/items/1d9c7b4333fd4d29a150)  
[Haskell(wai) による Webアプリケーション開発の実際（DB編） &#8211; mitsuji.org(http://mitsuji.org/?p=300)](http://mitsuji.org/?p=300)  
## mysql-simple
[mysql-simple: A mid-level MySQL client library.(http://hackage.haskell.org/package/mysql-simple)](http://hackage.haskell.org/package/mysql-simple)  
[Haskell から MySQL を使う - Qiita(https://qiita.com/lotz/items/a24c98dde8bd7e9ae089)](https://qiita.com/lotz/items/a24c98dde8bd7e9ae089)  
  
package.yaml  

```
dependencies:
- base >= 4.7 && < 5
- mysql-simple
- time
```
### Read  
./app/Main.hs  

```
{-# LANGUAGE OverloadedStrings #-}

import Database.MySQL.Simple
import Data.Time
import Data.Time.Clock.POSIX

main :: IO ()
main = do
  conn <- connect defaultConnectInfo { connectHost = "localhost", connectPort = 3306, connectUser = "root", connectPassword = "password", connectDatabase = "test" }
  rs <- query_ conn "SELECT * FROM memos"
  mapM_ putStrLn $ map show (rs :: [(Int, String, String, UTCTime)])
```
[https://qiita.com/lotz/items/a24c98dde8bd7e9ae089](https://qiita.com/lotz/items/a24c98dde8bd7e9ae089)  
### それぞれの値を取り出す

```
MariaDB [test]> select * from memos;
+----+------+---------+---------------------+
| id | name | comment | time                |
+----+------+---------+---------------------+
|  1 | name | comment | 2020-08-21 17:50:06 |
|  2 | Mike | hello   | 2020-10-13 08:46:33 |
+----+------+---------+---------------------+
2 rows in set (0.000 sec)

MariaDB [test]>
qqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqq
apo@gentoo ~/Documents/project/make/haskell/mysql-simple/my-project $ cat ./app/Main.hs
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Database.MySQL.Simple
import Data.Time
import Data.Time.Clock.POSIX

main :: IO ()
main = do
    conn <- connect defaultConnectInfo { connectHost = "localhost",
                                         connectPort = 3306,
                                         connectUser = "root",
                                         connectPassword = "password",
                                         connectDatabase = "test" }
    rs <- query_ conn "SELECT * FROM memos"

    let a = rs :: [(Int, String, String, UTCTime)]
    putStrLn (show a)

    let b = a !! 1
    putStrLn (show b)

    let (id, name, comment, time) = b
    putStrLn ("id=" ++ show id)
    putStrLn ("name=" ++ show name)
    putStrLn ("comment=" ++ show comment)
    putStrLn ("time=" ++ show time)
apo@gentoo ~/Documents/project/make/haskell/mysql-simple/my-project $ stack exec my-project-exe
[(1,"name","comment",2020-08-21 17:50:06 UTC),(2,"Mike","hello",2020-10-13 08:46:33 UTC)]
(2,"Mike","hello",2020-10-13 08:46:33 UTC)
id=2
name="Mike"
comment="hello"
time=2020-10-13 08:46:33 UTC
apo@gentoo ~/Documents/project/make/haskell/mysql-simple/my-project $
```
## mysql-haskell
[mysql-haskell: pure haskell MySQL driver(http://hackage.haskell.org/package/mysql-haskell)](http://hackage.haskell.org/package/mysql-haskell)  
[Haskellで実装された MySQL ドライバ mysql-haskell を試してみた - Qiita(https://qiita.com/lotz/items/1d9c7b4333fd4d29a150)](https://qiita.com/lotz/items/1d9c7b4333fd4d29a150)    
  
package.yamlにmysql-haskellを追記する  

```
dependencies:
- base >= 4.7 && < 5
- io-streams
- mysql-haskell
```
  
xxx.cabalを削除する  

```
mv xxx.cabal xxx.cabal.bak
```
### lts
lts-15.3は動かなかった。2020年3月現在。  
lts-11.22, lts-9.21で動作確認済み。  
  
stack.yaml  

```
resolver: lts-11.22
```
Main.hs  

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

main :: IO ()
main = do
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "Akira1625@", ciDatabase = "test"}
     (defs, is) <- query_ conn "SELECT * FROM memos"
     print =<< Streams.toList is
```
### errMsg = "Client does not support authentication protocol requested by server; consider upgrading MySQL client"

```
use mysql;
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'Password1234!';
```
[https://qiita.com/monga3/items/6583c07a9b275b469608](https://qiita.com/monga3/items/6583c07a9b275b469608)  
## 個々のデータを取り出す
[https://github.com/ringo-apo/mysql-haskell_20200406](https://github.com/ringo-apo/mysql-haskell_20200406)  
[https://qiita.com/lotz/items/1d9c7b4333fd4d29a150](https://qiita.com/lotz/items/1d9c7b4333fd4d29a150)  
### Select

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import qualified Data.Text.IO as T
import Data.Text

main :: IO ()
main = do
     print "id name comment time"
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "Password1234!", ciDatabase = "test"}
     (defs, is) <- query_ conn "SELECT * FROM memos"
     --print =<< Streams.toList is

     mapM_ (mapM f) =<< Streams.toList is
        where
        -- 受け取った引数が MySQLText の場合だけ、取り出した文字列をputStrLnする関数
        f :: MySQLValue -> IO ()

        f (MySQLText text) = do
            T.putStr text
            T.putStr " "

        f (MySQLInt32 int) = do
            T.putStr (Data.Text.pack (show int))
            T.putStr " "

        f (MySQLDateTime text) = do
            T.putStr (Data.Text.pack (show text))
            T.putStrLn ""

        f _other = return ()

        --f _other = T.putStrLn ""
```

```
"id name comment time"
1 John Hello 2021-04-12 11:30:56
2 Mike apple 2021-04-12 12:25:00
```
#### Select sample2

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import qualified Data.Text.IO as T
import Data.Text

main :: IO ()
main = do
    print "id name comment time"
    conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "Password1234!", ciDatabase = "test"}
    (defs, is) <- query_ conn "SELECT * FROM memos"
    --print =<< Streams.toList is

    let f :: MySQLValue -> IO ()
        f (MySQLText text) = do
            T.putStr text
            T.putStr " "

        f (MySQLInt32 int) = do
            T.putStr (Data.Text.pack (show int))
            T.putStr " "

        f (MySQLDateTime text) = do
            T.putStr (Data.Text.pack (show text))
            T.putStrLn ""

        f _other = return ()
        in mapM_ (mapM f) =<< Streams.toList is

    print "hello"
```
### Insert
Main.hs  

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a

main :: IO ()
main = do
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "testMySQLHaskell"}
     stmt <- prepareStmt conn "INSERT INTO person VALUES (NULL, ?, ?)"
     transactional conn $ do
       executeStmt conn stmt [MySQLText "chris", MySQLInt32 18]
       executeStmt conn stmt [MySQLText "Steeve", MySQLInt32 6]
       executeStmt conn stmt [MySQLText "Mikele", MySQLInt32 19]
       (defs, is) <- query_ conn "SELECT * FROM person"
       mapM_ print =<< Streams.toList is
```
Insert 例2  

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a


main :: IO ()
main = do
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}
     transactional conn $ do
       execute_ conn "INSERT INTO memos (comment) VALUES ('hello')"
       (defs, is) <- query_ conn "SELECT * FROM memos"
       mapM_ print =<< Streams.toList is
```
  
Insert 例3  
変数を使ったInsert  

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a

main :: IO ()
main = do
     let comment = "apple"
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}
     stmt <- prepareStmt conn "INSERT INTO memos (comment) VALUES (?)"
     transactional conn $ do
       executeStmt conn stmt [MySQLText comment]
       (defs, is) <- query_ conn "SELECT * FROM memos"
       mapM_ print =<< Streams.toList is
```
Insert 例4  
キー入力でInsert  
package.yaml  

```
dependencies:
- base >= 4.7 && < 5
- text
- mysql-simple
- mysql
- io-streams
```
Main.hs  

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import Data.Text.Internal (Text(..), safe, text)

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a


main :: IO ()
main = do
     -- let comment = "apple"
     a <- getLine
     let b = "\"" ++ a ++ "\""
     let comment = read b :: Data.Text.Internal.Text
     let id = 3
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "Akira1625@", ciDatabase = "test"}
     stmt <- prepareStmt conn "INSERT INTO memos (comment) VALUES (?)"
     transactional conn $ do
       executeStmt conn stmt [MySQLText comment]
       (defs, is) <- query_ conn "SELECT * FROM memos"
       mapM_ print =<< Streams.toList is
```
Insert 例5  
日付にInsert  

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a

main :: IO ()
main = do
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}
     stmt <- prepareStmt conn "INSERT INTO memos (name, comment, time) VALUES (?, ?, ?)"
     transactional conn $ do
        executeStmt conn stmt [MySQLText "chris", MySQLText "comment", MySQLText "2020/10/01 00:00:00"]
        (defs, is) <- query_ conn "SELECT * FROM memos"
        mapM_ print =<< Streams.toList is
```
## Delete

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a

main :: IO ()
main = do
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "testMySQLHaskell"}
     transactional conn $ do
       execute_ conn "delete from person order by id limit 1"
       (defs, is) <- query_ conn "SELECT * FROM person"
       mapM_ print =<< Streams.toList is
```
## Delete sample2
./app/Main.hs  

```
apo@gentoo ~/Documents/project/make/haskell/mysql_delete/my-project $ cat ./app/Main.hs
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a


main :: IO ()
main = do
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "Password1234!", ciDatabase = "test"}
     transactional conn $ do
       execute_ conn "delete from memos where id=1"

       (defs, is) <- query_ conn "SELECT * FROM memos"
       mapM_ print =<< Streams.toList is
```
## Update

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a


main :: IO ()
main = do
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "testMySQLHaskell"}
     transactional conn $ do
       execute_ conn "update person set age=90 order by id limit 1"
       (defs, is) <- query_ conn "SELECT * FROM person"
       mapM_ print =<< Streams.toList is
```
## CRUDツール
./app/Main.hs  

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import qualified Data.Text.IO as T
import Data.Text

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a

main :: IO ()
main = do
    someFunc
```
./src/Lib.hs

```
{-# LANGUAGE OverloadedStrings #-}

module Lib
    ( someFunc
    ) where

import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import Data.Text
import qualified Data.Text.IO as T
import Data.Text.Internal (Text(..), safe, text)

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
    execute_ conn "BEGIN"
    a <- restore procedure `onException` (execute_ conn "ROLLBACK")
    execute_ conn "COMMIT"
    pure a

someFunc :: IO ()
someFunc = do
    print "Please input menu key."
    print "1:Select 2:Insert 3:Delete 4:Update 5:End"

    menun <- getLine

    case menun of
        "1" -> do
            print "id name comment time"
            conn <- connect
                defaultConnectInfo {ciUser = "root", ciPassword = "Password1234!", ciDatabase = "test"}
            (defs, is) <- query_ conn "SELECT * FROM memos"

            let f :: MySQLValue -> IO ()

                f (MySQLText text) = do
                    T.putStr text
                    T.putStr " "

                f (MySQLInt32 int) = do
                    T.putStr (Data.Text.pack (show int))
                    T.putStr " "

                f (MySQLDateTime text) = do
                    T.putStr (Data.Text.pack (show text))
                    T.putStrLn ""

                f _other = return ()

                in mapM_ (mapM f) =<< Streams.toList is

            someFunc

        "2" -> do
            -- let comment = "apple"
            print "Input name"
            name <- getLine
            let nameb = "\"" ++ name ++ "\""
            let namec = read nameb :: Data.Text.Internal.Text

            print "Input comment"
            a <- getLine
            let b = "\"" ++ a ++ "\""
            let comment = read b :: Data.Text.Internal.Text
            let id = 3
            conn <- connect
                defaultConnectInfo {ciUser = "root", ciPassword = "Password1234!", ciDatabase = "test"}
            stmt <- prepareStmt conn "INSERT INTO memos (name, comment, time) VALUES (?, ?, NOW())"
            transactional conn $ do
                executeStmt conn stmt [MySQLText namec, MySQLText comment]
                (defs, is) <- query_ conn "SELECT * FROM memos"
                mapM_ print =<< Streams.toList is

            someFunc

        "3" -> do
            print "Input id number"
            id <- getLine
            let idb = "\"" ++ id ++ "\""
            let idc = read idb :: Data.Text.Internal.Text

            conn <- connect
                defaultConnectInfo {ciUser = "root", ciPassword = "Password1234!", ciDatabase = "test"}
            stmt <- prepareStmt conn "delete from memos where id=?"
            transactional conn $ do
                executeStmt conn stmt [MySQLText idc]

                (defs, is) <- query_ conn "SELECT * FROM memos"
                mapM_ print =<< Streams.toList is

            someFunc

        "4" -> do
            print "Input id number"
            id <- getLine
            let idb = "\"" ++ id ++ "\""
            let idc = read idb :: Data.Text.Internal.Text

            print "Input comment"
            comment <- getLine
            let commentb = "\"" ++ comment ++ "\""
            let commentc = read commentb :: Data.Text.Internal.Text

            conn <- connect
                defaultConnectInfo {ciUser = "root", ciPassword = "Password1234!", ciDatabase = "test"}
            stmt <- prepareStmt conn "update memos set comment=? , time=NOW() where id=?"
            transactional conn $ do
                executeStmt conn stmt [MySQLText commentc, MySQLText idc]
                (defs, is) <- query_ conn "SELECT * FROM memos"
                mapM_ print =<< Streams.toList is
            someFunc

        _ -> do
          print "End"
```
[https://github.com/ringo-apo/haskell_mysql_crud](https://github.com/ringo-apo/haskell_mysql_crud)  
# ポートを指定する

```
ConnectInfo {connectHost = "connectPort = 3306"}
```

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a


main :: IO ()
main = do
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "testMySQLHaskell", connectPort = 3306}
     transactional conn $ do
       execute_ conn "update person set age=90 order by id limit 1"
       (defs, is) <- query_ conn "SELECT * FROM person"
       mapM_ print =<< Streams.toList is
```
[https://qiita.com/lotz/items/a24c98dde8bd7e9ae089](https://qiita.com/lotz/items/a24c98dde8bd7e9ae089)  
# GHC
## バージョンの確認

```
ghc --version
```
# WEB
[Haskell(wai) による Webアプリケーション開発の実際 &#8211; mitsuji.org(http://mitsuji.org/?p=17)](http://mitsuji.org/?p=17)  
# キーボードから入力した数値に+5をして表示するプログラム
```
module Main where

main = do
     a <- getLine
     let b = (read a :: Int) + 5 
     print(b)
```
# Stackage
[Stackage(https://www.stackage.org/)](https://www.stackage.org/)  
# Hackage
[Hackage(https://hackage.haskell.org/)](https://hackage.haskell.org/)  
# Hoogle
[Hoogle(https://www.haskell.org/hoogle/)](https://www.haskell.org/hoogle/)  
# 注釈
「-- 」を入れる  

```
Prelude> putStrLn "Guten morgen!" -- コメントです
Guten morgen!
```
# 乱数を使う
## stack
package.yamlに下記を追加  

```
dependencies:
- mwc-random
- random
```
## 使い方
Main.hs  

```
module Main where

import System.Random.MWC

main :: IO ()
main = do
    gen <- createSystemRandom
    randValue <- uniform gen :: IO Int
    print randValue
```
[Haskell System.Random.MWCの使い方を随分と詳細にまとめた（初心者向け）](http://blog.livedoor.jp/rtabaladi_58/archives/65158189.html)  
  
1-100内の整数の乱数を発生させる  

```
module Main where

import System.Random.MWC

main :: IO ()
main = do
    gen <- createSystemRandom
    randValue2 <- uniformR(1, 100) gen :: IO Int
    print randValue2     
```
# 並べ替え（sort関数）  

```
module Main where

import Data.List

main :: IO ()
main = do
     print (sort [5,4,3,2,2,1] )
```
## 乱数を使ったソート
```
module Main where

import System.Random.MWC
import Data.List

main :: IO ()
main = do
    gen <- createSystemRandom
    randValue1 <- uniformR(1, 100) gen :: IO Int
    randValue2 <- uniformR(1, 100) gen :: IO Int
    randValue3 <- uniformR(1, 100) gen :: IO Int
    randValue4 <- uniformR(1, 100) gen :: IO Int
    randValue5 <- uniformR(1, 100) gen :: IO Int
    randValue6 <- uniformR(1, 100) gen :: IO Int
    randValue7 <- uniformR(1, 100) gen :: IO Int
    randValue8 <- uniformR(1, 100) gen :: IO Int
    randValue9 <- uniformR(1, 100) gen :: IO Int
    randValue10 <- uniformR(1, 100) gen :: IO Int
    let a = [randValue1, randValue2, randValue3, randValue4, randValue5, randValue6, randValue7, randValue8, randValue9, randValue10 ]
    print a
    let b = sort a
    print b
```
  
package.yaml  
```
name:                project
version:             0.1.0.0
github:              "githubuser/project"
license:             BSD3
author:              "Author name here"
maintainer:          "example@example.com"
copyright:           "2018 Author name here"

extra-source-files:
- README.md
- ChangeLog.md

# Metadata used when publishing your package
# synopsis:            Short description of your package
# category:            Web

# To avoid duplicated efforts in documentation and dealing with the
# complications of embedding Haddock markup inside cabal files, it is
# common to point users to the README.md file.
description:         Please see the README on GitHub at <https://github.com/githubuser/project#readme>

dependencies:
- base >= 4.7 && < 5
- random
- mwc-random

library:
  source-dirs: src

executables:
  project-exe:
    main:                Main.hs
    source-dirs:         app
    ghc-options:
    - -threaded
    - -rtsopts
    - -with-rtsopts=-N
    dependencies:
    - project

tests:
  project-test:
    main:                Spec.hs
    source-dirs:         test
    ghc-options:
    - -threaded
    - -rtsopts
    - -with-rtsopts=-N
    dependencies:
    - project

```
# 乱数のリスト
```
module Main where

import System.Random.MWC
import Data.List
import System.Random

main :: IO ()
main = do
    gen <- createSystemRandom
    r1 <- uniformR(1, 100) gen :: IO Int
    r2 <- uniformR(1, 100) gen :: IO Int
    r3 <- uniformR(1, 100) gen :: IO Int
    r4 <- uniformR(1, 100) gen :: IO Int
    r5 <- uniformR(1, 100) gen :: IO Int
    let a = [r1 , r2 , r3 , r4 , r5]
    print a
    print (mkStdGen 7)
    print ( take 100 ( randomRs (1,6) (mkStdGen 7) :: [Int] )) -- ←これだけでいける
```
# リストに+1する
```
module Main where

import System.Random.MWC
import Data.List
import System.Random

main :: IO ()
main = do
    let a = take 10 ( randomRs (1,100) (mkStdGen 100) :: [Int])
    print a

    let e = map (+ 1) a
    print e
```
# relational-record
データベースフレームワーク  
[khibino/haskell-relational-record: This repository includes a joined query generator based on typefull relational algebra, and mapping tools between SQL values list and Haskell record type.](https://github.com/khibino/haskell-relational-record)  
[relational-record を MySQL で使ってみた - Qiita](https://qiita.com/lotz/items/3aa65852bf75f3538d11)  
# case
```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a


main :: IO ()
main = do
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}
     transactional conn $ do
       (defs, is) <- query_ conn "SELECT * FROM memos"
       mapM_ print =<< Streams.toList is
     putStrLn("Menu 1:Select All  2:Insert  3:Delete  4:Update  5:End")
     menun <- getLine
     case menun of
     	  "1" -> do
	      putStrLn("input 1")
	      main

	  "2" -> do
	      putStrLn("input 2")
	      main
	      
     	  "3" -> do
	      putStrLn("input 3")
	      main
	      
     	  "4" -> do
	      putStrLn("input 4")
	      main
	      
	  _   -> do
	      putStrLn("input other")
```
## Insert
サンプルプログラム  
```
{-# LANGUAGE OverloadedStrings #-}

import Control.Monad
import Database.MySQL.Simple

type User = (Int, String)

getConnection:: IO Connection
getConnection = connect defaultConnectInfo { connectDatabase = "mysql_test" }

mySelect :: IO ()
mySelect = do
  conn <- getConnection
  rs   <- query_ conn "SELECT * FROM user"
  mapM_ putStrLn $ map show (rs :: [User])

myInsert :: IO ()
myInsert = do
  putStrLn "Data: "
  input <- getLine
  let user = (read $ concat ["(", input, ")"]) :: User
  conn <- getConnection
  execute conn "INSERT INTO user VALUES (?, ?)" user
  return ()

myUpdate :: IO ()
myUpdate = do
  putStrLn "Data: "
  input <- getLine
  let (n, name) = (read $ concat ["(", input, ")"]) :: User
  conn <- getConnection
  execute conn "UPDATE user SET name = ? WHERE id = ?" (name, n)
  return ()

myDelete :: IO ()
myDelete = do
  putStrLn "ID: "
  input <- getLine
  let n = read input :: Int
  conn <- getConnection
  execute conn "DELETE FROM user WHERE id = ?" (Only n)
  return ()

main :: IO ()
main = do
  putStrLn "Command: "
  command <- getLine
  case command of
    "show"   -> mySelect >> main
    "insert" -> myInsert >> main
    "update" -> myUpdate >> main
    "delete" -> myDelete >> main
    "exit"   -> putStrLn "Bye." >> return ()
    _        -> putStrLn "Command: show, insert, update, deletem or exit" >> main
```
[Haskell から MySQL を使う - Qiita](https://qiita.com/lotz/items/a24c98dde8bd7e9ae089)  
```
$ mkdir mysql-test && cd mysql-test
$ cabal sandbox init
```
package.yaml
```
dependencies:
- mysql-simple
```
```
{-# LANGUAGE OverloadedStrings #-}

import Database.MySQL.Simple

main :: IO ()
main = do
  conn <- connect defaultConnectInfo
  [Only i] <- query_ conn "select 2 + 2"
  print (i :: Int)
```
```
$ cabal run app
4
```
```
$ mysql -uroot
mysql> CREATE DATABASE mysql_test;
mysql> USE mysql_test;
mysql> CREATE TABLE user (id int unsigned, name varchar(255), PRIMARY KEY (id));
```
CREATE  
```
{-# LANGUAGE OverloadedStrings #-}

import Database.MySQL.Simple

main :: IO ()
main = do
  conn <- connect defaultConnectInfo { connectDatabase = "mysql_test" }
  execute conn "INSERT INTO user VALUES (?, ?)" (1 :: Int, "a" :: String)
  return ()
```
```
mysql> SELECT * FROM user;
+----+------+
| id | name |
+----+------+
|  1 | a    |
+----+------+
```
READ
```
{-# LANGUAGE OverloadedStrings #-}

import Database.MySQL.Simple

main :: IO ()
main = do
  conn <- connect defaultConnectInfo { connectDatabase = "mysql_test" }
  rs <- query_ conn "SELECT * FROM user"
  mapM_ putStrLn $ map show (rs :: [(Int, String)])
```
```
$ cabal run app
(1,"a")
(2,"b")
(3,"c")
(4,"d")
(5,"e")
(6,"f")
(7,"g")
(8,"h")
(9,"i")
(10,"j")
```
```
type User = (Int, String)
```
UPDATE
```
{-# LANGUAGE OverloadedStrings #-}

import Database.MySQL.Simple

main :: IO ()
main = do
  conn <- connect defaultConnectInfo { connectDatabase = "mysql_test" }
  execute_ conn "UPDATE user SET name = 'aa' WHERE id = 1"
  return ()
```
DELETE
```
{-# LANGUAGE OverloadedStrings #-}

import Database.MySQL.Simple

main :: IO ()
main = do
  conn <- connect defaultConnectInfo { connectDatabase = "mysql_test" }
  execute_ conn "DELETE FROM user WHERE id = 10"
  return ()
```
簡単なアプリ
```
{-# LANGUAGE OverloadedStrings #-}

import Control.Monad
import Database.MySQL.Simple

type User = (Int, String)

getConnection:: IO Connection
getConnection = connect defaultConnectInfo { connectDatabase = "mysql_test" }

mySelect :: IO ()
mySelect = do
  conn <- getConnection
  rs   <- query_ conn "SELECT * FROM user"
  mapM_ putStrLn $ map show (rs :: [User])

myInsert :: IO ()
myInsert = do
  putStrLn "Data: "
  input <- getLine
  let user = (read $ concat ["(", input, ")"]) :: User
  conn <- getConnection
  execute conn "INSERT INTO user VALUES (?, ?)" user
  return ()

myUpdate :: IO ()
myUpdate = do
  putStrLn "Data: "
  input <- getLine
  let (n, name) = (read $ concat ["(", input, ")"]) :: User
  conn <- getConnection
  execute conn "UPDATE user SET name = ? WHERE id = ?" (name, n)
  return ()

myDelete :: IO ()
myDelete = do
  putStrLn "ID: "
  input <- getLine
  let n = read input :: Int
  conn <- getConnection
  execute conn "DELETE FROM user WHERE id = ?" (Only n)
  return ()

main :: IO ()
main = do
  putStrLn "Command: "
  command <- getLine
  case command of
    "show"   -> mySelect >> main
    "insert" -> myInsert >> main
    "update" -> myUpdate >> main
    "delete" -> myDelete >> main
    "exit"   -> putStrLn "Bye." >> return ()
    _        -> putStrLn "Command: show, insert, update, deletem or exit" >> main
```
```
$ cabal run app
Command:
show
(1,"aa")
(2,"b")
(3,"c")
(4,"d")
(5,"e")
(6,"f")
(7,"g")
(8,"h")
(9,"i")
Command:
insert
Data:
10, "haskell"
Command:
delete
ID:
8
Command:
show
(1,"aa")
(2,"b")
(3,"c")
(4,"d")
(5,"e")
(6,"f")
(7,"g")
(9,"i")
(10,"haskell")
Command:
exit
Bye.
```
# ByteString
## 文字列の連結
```
let a = "abc" ++ "def"
print a

"abcdef"
```
  
リストの連結  
```
[1,2,3] `mappend` [4,5,6]
[1,2,3,4,5,6]
```
# Couldn't match type
```
    Couldn't match expected type `[Char]' with actual type `Int'
    In the first argument of `(++)', namely `age'
```
意味  
'++'は文字列（[Char]）を期待しています。実際の型は整数です。  
# 型を確認する

```
:t read
read :: Read a => String -> a  -- 出力結果
```
# Emacs
haskell-mode  
[気がついたら Emacs の Haskell を勉強する環境が整っていた話 - Diary over Finite Fields](https://blog.515hikaru.net/entry/2016/09/12/021206)  
# リスト内包表記（List comprehension）

```
[x*2 | x <- [1..10]]

[2,4,6,8,10,12,14,16,18,20]
```
  
```
module Main where

qsort [] = []
qsort (p:xs) = qsort smaller ++ [p] ++ qsort larger
    where smaller = [x | x <- xs, x < p ]
          larger  = [x | x <- xs, x >= p]

main = print $ qsort [3, 2, 4, 1, 5]  -- 出力: [1, 2, 3, 4, 5]
```
## サンプル２

```
module Main where

main :: IO ()
main = do
    print ([ x | x <- [1..10], mod x 3 == 1])
```

```
[1,4,7,10]
```
[https://www.casleyconsulting.co.jp/blog/engineer/219/](https://www.casleyconsulting.co.jp/blog/engineer/219/)  
# リスト内包表記に述語

```
module Main where

main :: IO ()
main = do

    let a = [x*2 | x <- [1..10], x*2 >= 12]
    putStrLn (show a)
```

```
apo@gentoo ~/Documents/project/make/haskell/comprehensions/my-project $ stack exec my-project-exe
[12,14,16,18,20]
```
すごいHな本 p16  
# 「\[0m」が表示される
ANSIカラーのエスケープシーケンス。  
ansiconをインストールする。  
[ANSICON](http://adoxa.altervista.org/ansicon/)  
## PowerShellにAnsiconを使う
コマンドプロンプトで  

```
ansicon powershell
```
と打つとAnsiconでPowerShellが立ち上がる  
  
# リスト内包表記2
1から10の数を2倍して12以上のものだけ書き出す。  

```
module Main where

lt = [x*2 | x <- [1..10], x*2 >= 12]

main :: IO ()
main = print $ lt

```
# map関数
関数とリストを受け取り、その関数をリストのすべての要素に適用して新しいリストを生成する。  

```
map (+3) [1,5,3,1,6]
[4,8,6,4,9]
```
リスト内包表記で書くこともできる  
[map関数 - Qiita](https://qiita.com/knknkn1162/items/92de8dd250ff94cd86f1)  

```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    let a = [5 ,2 ,5 ,3 ,6 ,4]

    let b = map (\x -> x * 2 + 3) a :: [Int]

    putStrLn (show a)
    putStrLn (show b)
```

```
someFunc
[5,2,5,3,6,4]
[13,7,13,9,15,11]
```

```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    let a = [(1,2),(2,3),(3,4)]
    putStrLn (show a)

    let b = map (\ (x,y) -> x + y) a
    putStrLn (show b)
```

```
someFunc
[(1,2),(2,3),(3,4)]
[3,5,7]
```
# mapM 関数

```
main = do
    mapM putStrLn ["hoge", "piyo", "fuga"]
```

```
hoge
piyo
fuga
```
ちなみにmanM_に置き換えても同じ結果になる  

```
main = do
    mapM_ putStrLn ["hoge", "piyo", "fuga"]
```

```
hoge
piyo
fuga
```
ちなみにmapではコンパイルエラーになる  
[http://kawauso7c.hatenablog.com/entry/2016/10/02/main%E3%81%A7putStr%E3%82%92map%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95](http://kawauso7c.hatenablog.com/entry/2016/10/02/main%E3%81%A7putStr%E3%82%92map%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95)  
↓ これはコンパイルエラーになる  

```
main :: IO ()
main = do
    mapM putStrLn ["hoge", "piyo", "fuga"]
```
↓ これはOK  

```
main :: IO [()]
main = do
    mapM putStrLn ["hoge", "piyo", "fuga"]
```
## sample2
```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    print(mapM (\x -> if 0 < x then Just (x * 2) else Nothing) [1,2,3,4])
    print(mapM (\x -> if 0 < x then Just (x * 2) else Nothing) [1,2,-4,3,4])
```
```
someFunc
Just [2,4,6,8]
Nothing
```
「Haskell入門」p174  
# mapM_ 関数

```
main = do
	let list = [1, 2, 3]
	mapM_ print list
```

```
1
2
3
```
[https://www.xmisao.com/2013/11/05/learning-haskell-6.html](https://www.xmisao.com/2013/11/05/learning-haskell-6.html)  

```
main = mapM_ print ["hoge", "piyo", "fuga"]
```

```
"hoge"
"piyo"
"fuga"
```
[https://jutememo.blogspot.com/2010/03/haskell-mapm-foldr.html](https://jutememo.blogspot.com/2010/03/haskell-mapm-foldr.html)  
## sample2
Main.hs  

```
module Main where

import Lib

fb :: Int -> String
fb n
 | n `mod` 15 == 0 = "FizzBuzz"
 | n `mod` 3  == 0 = "Fizz"
 | n `mod` 5  == 0 = "Buzz"
 | otherwise       = show n

main :: IO ()
main = do
    someFunc

    mapM_ (putStrLn . fb) [1..100]
```

```
someFunc
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
```
# filter関数
述語（条件）とリストを受け取り、そのリストの要素のうち、述語を満たすもののみからなるリストを返す。  

```
filter (>3) [1,5,3,2,1,6,4,3,2,1]
[5,6,4]
```
リスト内包表記で書くこともできる  

```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    let a = [1,2,3,4,5]
    let b = filter (\x -> x > 2) a

    putStrLn (show a)
    putStrLn (show b)
```

```
someFunc
[1,2,3,4,5]
[3,4,5]
```
## sample2
./app/Main.hs  

```
module Main where

main :: IO ()
main = do

    let a = [1,2,3,4,5]
    let b = filter (\x -> x > 2) a

    putStrLn (show a)
    putStrLn (show b)
```

```
apo@gentoo ~/Documents/project/make/haskell/filter/my-project $ stack exec my-project-exe
[1,2,3,4,5]
[3,4,5]
```
# フロントエンド
[Miso: A tasty Haskell front-end framework](https://haskell-miso.org/)  
# FizzBuzz
hoge.hs  

```
main = print $ map fizzBuzz [0..40]


-- 3で割り切れる数に対しては"Fizz"
-- 5で割り切れる数に対しては"Buzz"
-- 3でも5でも割り切れる数に対しては"FizzBuzz"
-- 上記以外はその整数を答える

fizzBuzz :: Integer -> String
fizzBuzz 0 = "0"
fizzBuzz x
    | x `mod` 15 == 0 = "FizzBuzz!!"
    | x `mod` 5 == 0 = "Fizz"
    | x `mod` 3 == 0 = "Buzz"
    | otherwise = show(x)
```
# Import
よく使うプログラムをmoduleで作っておけば、importすることで使うことができる。  
ライブラリファイル Geometry.hs  

```
-- ファイル: Geometry.hs

module Geometry where

data Shape = Tri { base, height:: Double }
           | Rect { width, height :: Double }

area :: Shape -> Double
area (Tri x y)  = x * y / 2
area (Rect x y) = x * y
```
Main.hs  

```
-- ファイル: Main.hs

import Geometry

main = do print $ width (Rect 3 4)   -- 出力: 3.0
          print $ height (Rect 3 4)  -- 出力: 4.0
          print $ area (Tri 3 4)     -- 出力: 6.0
          print $ area (Rect 3 4)    -- 出力: 12.0
```
# PCへのstack.yamlファイルの位置
/home/apo/.stack/global-project/stack.yaml  
# バイナリエディタ
[http://simplesandsamples.com/read-bin.hs.html](http://simplesandsamples.com/read-bin.hs.html)  
## バイナリ表示
[https://github.com/ringo-apo/hs_binaryPrint?fbclid=IwAR0b-otxQ4rOUki1aq3eJPcCjGsVOPmfNeZQPdJFKzb9pblsTTfV-Y4PhOw](https://github.com/ringo-apo/hs_binaryPrint?fbclid=IwAR0b-otxQ4rOUki1aq3eJPcCjGsVOPmfNeZQPdJFKzb9pblsTTfV-Y4PhOw)  
./package.yaml

```
dependencies:
- bytestring >= 0.9.1
```
./app/Main.hs

```
module Main where

import Data.ByteString.Lazy
import Data.Word

main :: IO ()
main = do
    contents <- Data.ByteString.Lazy.readFile "hoge.bin"
    print (unpack contents)
```
# Data.ByteString.Lazy
Main.hs  

```
import Data.ByteString.Lazy
```
  
package.yaml  

```
dependencies:
- bytestring >= 0.9.1
```
# For文を使わないプログラミング
[http://gihyo.jp/dev/feature/01/functional-prog/0002?page=1](http://gihyo.jp/dev/feature/01/functional-prog/0002?page=1)  
# Haskellで大富豪を作ろう
[http://myuon-myon.hatenablog.com/entry/2015/07/15/181116](http://myuon-myon.hatenablog.com/entry/2015/07/15/181116)  
# Dependencies
package.yaml  

```
dependencies:
- base >= 4.7 && < 5
- split >=0.2.0.0  && <= 0.2.3.3
- random-shuffle >= 0.0.3 && <= 0.0.4
```
Hackageの名称を記載する  
  
標準に入っていないLensパッケージを使ってみることにしました。
まずこの状態でstack buildとコマンドプロンプトに入力してみましょう。多分コンパイラに「Control.Lensて何？知らないよ？」と怒られるでしょう。なので、stack install lensとしてパッケージlensをインストールしておきます。するとそのプロジェクト内でlensパッケージが使えるようになります。（ここでlensパッケージとしたのはControl.Lensモジュールが所属するパッケージ名がlensであるため（hackage参照））lensパッケージは大きいパッケージなので少し時間がかかるので少し待ちましょう。
インストール終了後、もう一度stack buildしてみましょう。すると先とは違ったエラーが出てきます。そこには「そのControl.lensモジュールが書かれたパッケージ見つかったはいいがtestProject.cabalファイルに記述されていない。 」というようなエラーのようです。ならば記述してやりましょう。今回は著者の環境ではtestProject.cabalが自動生成されて効果を確認できないためpackage.yamlに書きます。今回はsrcフォルダ内でしか使っていないのでlibraryオプションに書き、以下となりました。（dependenciesに- lensを追記しても問題なし。）このとき「-」の後には空白を開けておかないとパースエラーになってしまうので注意してください。

package.yaml

```
library:
  source-dirs: src
  dependencies:
    - lens
```
今回の例の作成時には著者の環境でstack buildしたときにlens-4.15.4がほしいといわれていました。ですが、package.yamlが問題が起きないように自動的にバージョンを指定してくれるのでバージョン指定をしなくても大丈夫です。
そして保存してからもう一度stack buildすると今度は問題なくビルドがとおって実行ファイルができます。
実はstack install lensコマンドを使わなくてもいきなりpackage.yamlに記述するとビルド時にインストールしてからビルドをしてくれます。便利です。  

[https://qiita.com/ogata-k/items/2b21326b2b7351bfc28c](https://qiita.com/ogata-k/items/2b21326b2b7351bfc28c)  
# stackの使い方メモ
[https://23prime.hatenablog.com/entry/2018/11/27/092959](https://23prime.hatenablog.com/entry/2018/11/27/092959)  
# IPアドレス
[https://qiita.com/saltheads/items/1edc0445db1d582cdcad](https://qiita.com/saltheads/items/1edc0445db1d582cdcad)  

```
```
# FFI
[https://tech.nikkeibp.co.jp/it/article/COLUMN/20080805/312151/](https://tech.nikkeibp.co.jp/it/article/COLUMN/20080805/312151/)  
FFIExample.hs  

```
{-# INCLUDE "foreign.h" #-}
{-# LANGUAGE ForeignFunctionInterface #-}
{-# LANGUAGE EmptyDataDecls #-}
module FFIExample where
import Foreign.Ptr

data Point = Point Int Int
data CPoint

newPoint (Point x y) = c_newPoint x y

main = do
    pt <- newPoint (Point 16 34)
    x <- c_getPointX pt
    print x
    y <- c_getPointY pt
    print y

foreign import ccall "newPoint" c_newPoint :: Int -> Int -> IO (Ptr CPoint)
foreign import ccall "getPointX" c_getPointX :: Ptr CPoint -> IO Int
foreign import ccall "getPointY" c_getPointY :: Ptr CPoint -> IO Int
```
foreign.h  

```
struct Point {
    int x;
    int y;
};

struct Point* newPoint (int x, int y);
int getPointX (struct Point *pt);
int getPointY (struct Point *pt);

typedef void (*PointFunc) (struct Point *pt);
void applyPoint (struct Point* pt, PointFunc func);
```
foreign.c  

```
#include <stdlib.h>
#include "foreign.h"

struct Point* newPoint (int x, int y) {
  struct Point *pt;
  pt = (struct Point *)malloc( sizeof(struct Point) );
  pt -> x = x;
  pt -> y = y;
  return pt;
};

int getPointX (struct Point* pt) {
  return (pt -> x) + 1;
};

int getPointY (struct Point* pt) {
  return (pt -> y) - 1;
};

void applyPoint (struct Point* pt, PointFunc func) {
  (*func) (pt);
};
```
コンパイル＆実行  

```
ghc FFIExample.hs foreign.c -main-is FFIExample
./FFIExample

17
33
```
※c言語をコンパイルしておく必要はない  
[https://mgattozzi.github.io/2016/10/01/haskell-rust.html](https://mgattozzi.github.io/2016/10/01/haskell-rust.html)  
  
別の例  
plus.c  

```
int plus(int a)
{
  return a + 1;
}
```
minus.c  

```
int minus(int a)
{
  return a - 1;
}
```
main.hs  

```
module Main where

import Foreign.C.Types

foreign import ccall "plus" c_plus :: CInt -> IO CInt
foreign import ccall "minus" c_minus :: CInt -> IO CInt

plus :: Int -> IO Int
plus = fmap fromIntegral . c_plus . fromIntegral

minus :: Int -> IO Int
minus = fmap fromIntegral . c_minus . fromIntegral

main :: IO ()
main = do
  print =<< plus 5
  print =<< minus 5
```

```
gcc -c plus.c // plus.oが生成される
gcc -c minus.c // minus.oが生成される
ghc main.hs plus.o minus.o // main.exeが生成される
```

```
$ main
6
4
```
[https://qiita.com/masatoko/items/06665400b2ef10a7e2b0](https://qiita.com/masatoko/items/06665400b2ef10a7e2b0)  
## HaskellからRustを呼び出す
[https://qiita.com/yasuyuky/items/45f7333118fa165b670b](https://qiita.com/yasuyuky/items/45f7333118fa165b670b)  
# 高階関数(higher-order function)
関数を変数に代入したり、引数として渡すこと  

```
-- リスト : 整数の和

sum_of_integer :: (Integer, Integer) -> Integer
sum_of_integer (n, m)
  | n > m     = 0
  | otherwise = n + sum_of_integer (n + 1, m)
```
実行結果  

```
*Main> sum_of_integer (1, 10)
55
*Main> sum_of_integer (1, 100)
5050
```
[http://www.nct9.ne.jp/m_hiroi/func/haskell03.html#chap02](http://www.nct9.ne.jp/m_hiroi/func/haskell03.html#chap02)  
## 楽しいHaskell楽しく学ぼう
[http://learnyouahaskell.com/higher-order-functions](http://learnyouahaskell.com/higher-order-functions)  

```
apo@tux ~/doc/project/make/haskell/higher-orderism/my-project $ cat ./app/Main.hs
module Main where

multThree :: (Num a) => a -> a -> a -> a
multThree x y z = x * y * z

applyTwice :: (a -> a) -> a -> a
applyTwice f x = f (f x)

main :: IO ()
main = do
    putStrLn (show (applyTwice (+3) 10))
    putStrLn (show (applyTwice (++ " HAHA") "HEY"))
    putStrLn (show (applyTwice ("HAHA " ++) "HEY"))
    putStrLn (show (applyTwice (multThree 2 2) 9))
    putStrLn (show (applyTwice (3:) [1]))
```

```
apo@tux ~/doc/project/make/haskell/higher-orderism/my-project $ stack exec my-project-exe
16
"HEY HAHA HAHA"
"HAHA HAHA HEY"
144
[3,3,1]
```
# 「10 * 0 + 20 * 1 + 30 * 2 + 40 * 3 + 50 * 4」を式だけで求める
for分を使った求め方（JavaScript）  
calc.js  

```
function calc(ar) {
    var ret = 0;
    for (var i=0; i < ar.length; i++) {
        ret = ret + ar[i]*i;
    }
    return ret;
}
```
Haskell  

```
> let mul (i,x) = x * i
> let calc xs = foldl (+) 0 (map mul (zip [0..] xs))
```

```
> calc [10,20,30,40,50]
400
```
[http://gihyo.jp/dev/feature/01/functional-prog/0002?page=1](http://gihyo.jp/dev/feature/01/functional-prog/0002?page=1)  
[https://github.com/ringo-apo/hs_zipTry_compereJava?fbclid=IwAR2V5mbJSkreNtEPRm-Vzofl4nBXB0Wm9erIFCvnCy6qmYp2qiYxDMDvoYs](https://github.com/ringo-apo/hs_zipTry_compereJava?fbclid=IwAR2V5mbJSkreNtEPRm-Vzofl4nBXB0Wm9erIFCvnCy6qmYp2qiYxDMDvoYs)  
# ラムダ式（Lambda expression）
関数に名前を記述せずに使える。  

```
(\n -> n + 1 :: Int) 10
11

incr = \n -> n + 1 :: Int
incr 10
11
```
## sample2

```
module Main where

main :: IO ()
main = do
    let a = (\x -> x * 2 :: Int) 10
    putStrLn(show a)
```

```
20
```
## 関数を使った方法と使わない方法（ラムダ式利用）

```
apo@gentoo ~/Documents/project/make/haskell/lambda/my-project $ cat ./app/Main.hs
module Main where

tasu :: Int -> Int -> Int
tasu x y = x + y

main :: IO ()
main = do

    let a = tasu 1 2

    putStrLn (show a)
apo@gentoo ~/Documents/project/make/haskell/lambda/my-project $ stack exec my-project-exe
3
apo@gentoo ~/Documents/project/make/haskell/lambda/my-project $


qqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqq

apo@gentoo ~/Documents/project/make/haskell/lambda/my-project2 $ cat ./app/Main.hs
module Main where

main :: IO ()
main = do

    let a = (\x y -> x + y :: Int) 1 2

    putStrLn (show a)
apo@gentoo ~/Documents/project/make/haskell/lambda/my-project2 $ stack exec my-project2-exe
3
apo@gentoo ~/Documents/project/make/haskell/lambda/my-project2 $
```
# 並列・並行処理
[https://qiita.com/satosystems/items/e7fb4295598dc61e4c67](https://qiita.com/satosystems/items/e7fb4295598dc61e4c67)  
# 並列処理(pararell)
処理をCPUごとに振り分け、高速化を行う。CPUが2個以上あることが必須。  
  
参考サイト
[http://tomitake3.hatenablog.com/entry/2019/01/22/205753](http://tomitake3.hatenablog.com/entry/2019/01/22/205753)  
## 初めてのHaskell並列プログラミング
[https://wiki.haskell.org/Haskell%E5%85%A5%E9%96%80_5%E3%82%B9%E3%83%86%E3%83%83%E3%83%97](https://wiki.haskell.org/Haskell%E5%85%A5%E9%96%80_5%E3%82%B9%E3%83%86%E3%83%83%E3%83%97)  
package.yaml  

```
dependencies:
- base >= 4.7 && < 5
- parallel
```
./app/Main.hs  

```
module Main where

import Control.Parallel

main :: IO ()
main = do
    a `par` b `par` c `pseq` print (a + b + c)
        where
            a = ack 3 10
            b = fac 42
            c = fib 34

fac 0 = 1
fac n = n * fac (n-1)

ack 0 n = n+1
ack m 0 = ack (m-1) 1
ack m n = ack (m-1) (ack m (n-1))

fib 0 = 0
fib 1 = 1
fib n = fib (n-1) + fib (n-2)
```

```
apo@tux ~/doc/project/make/haskell/parallel/my-project $ stack exec my-project-exe
1405006117752879898543142606244511569936384005711076
```
# 並行処理(concurrent)
並行計算：OSのマルチタスクのイメージ。同時に複数の処理を時間単位で切り替えて処理。  
[https://qiita.com/eielh/items/64ba5f0164b89c6c284e](https://qiita.com/eielh/items/64ba5f0164b89c6c284e)  
# haskellをどこまで極めるか？
・コマンドラインでできるところまで。  
・ラムダはマスターすべき  
・再帰はマスターすべき  
・再代入を使わないプログラミング方法は学ぶべき  
・モナドはマスターすべき  
・並列処理、並行処理はマスターすべき  
  
・GUIやWEBまでできる必要はない（需要はない）  
・データベース操作は不要  
# HelloWorld!
「stack new」実行時直後の状態  

```
module Main where

import Lib

main :: IO ()
main = someFunc
```
# 数宛てゲーム
Main.hs

```
module Main where

import System.Random

data Game = Continue Int | Clear

mainLoop :: Game -> IO ()
mainLoop (Clear) = putStrLn "Bingo!"
mainLoop (Continue answer) = do
    line <- getLine
    case read line of
        x | x < answer -> do putStrLn "the number is more big"
                             mainLoop (Continue answer)
          | x > answer -> do putStrLn "the number is more small"
                             mainLoop (Continue answer)
          | otherwise  -> do mainLoop (Clear)

main = do
    print "Please apply a random number from 1 to 100."
    randNum <- randomRIO (0,100)
    mainLoop (Continue randNum)
```
package.yaml  

```
dependencies:
- random
```
[https://github.com/ringo-apo/20180401_hs_NumberGame](https://github.com/ringo-apo/20180401_hs_NumberGame)  
# data

```
module Main where

import Lib

data Point = Point Float Float deriving (Show)

data Shape = Circle Point Float | 
             Rectangle Point Point  
    deriving (Show)

area :: Shape -> Float
area (Circle _ r) = pi * r ^ 2
area (Rectangle (Point x1 y1) (Point x2 y2)) = (abs $ x2 -x1) * (abs $ y2 - y1)


main :: IO ()
main = do
    someFunc

    print (area (Rectangle (Point 0 0) (Point 100 100)))
    print (area (Circle (Point 0 0) 24))
```
```
apo@tux ~/doc/project/make/haskell/data/my-project $ stack exec my-project-exe
someFunc
10000.0
1809.5574
```
# 文字の連結

```
print("foo" ++ "bar")

"foobar"
```
# ソースからインストール

```
./boot
./configure
make clean
make
make install
```
[https://qiita.com/takenobu-hs/items/c1309b93ca17b87e5955](https://qiita.com/takenobu-hs/items/c1309b93ca17b87e5955)  
[https://qiita.com/YoshikuniJujo/items/980775598e65fda36d33](https://qiita.com/YoshikuniJujo/items/980775598e65fda36d33)  
# ghcのインストール先
/usr/local/bin  
# stackのghcのインストール先
~/.stack/programs/x86_64-linux/ghc-ncurses6-8.2.2/bin/ghc  
# ghci REPL
起動  

```
ghci
```
終了  

```
:quit
```
# Haskell教養としての関数型プログラミング
github  
[https://github.com/YoshikuniJujo/funpaala](https://github.com/YoshikuniJujo/funpaala)  
# モンテカルロ法
[https://qiita.com/lotz/items/2570ed31bed7be834dcf](https://qiita.com/lotz/items/2570ed31bed7be834dcf)  
# 1 10 100 1000 10000 100000を作る

```
module Main where

main :: IO ()
main = do

    let a = [1 .. 10]
    let b = [10^x | x <- a]

    print (b)
```
# Listから１つずつ値を取り出して処理して返す

```
module Main where

func1 x = do
    if x == []
        then do
            print("end")
        else do
            let b = (head x) + 1
            print (b)
            func1 (tail x)


main :: IO ()
main = do

    let a = [1 .. 10]
    print (a)

    func1(a)
```
# !!
n番目の値を取り出す  

```
"abcde" !! 2
'c'
```
# putStrLn
putStrLnを使うとダブルクォーテーションが付かない。printだとダブルクォーテーションが付いてしまう。  

```
putStrLn "someFunc"

someFunc
```
# MariaDB
## Select
stack.yaml  

```
resolver:lts-14.18
```
package.yaml  
```
dependencies:
- base >= 4.7 && < 5
- io-streams
- mysql-haskell
```
Main.hs
```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Database.MySQL.Base
import qualified System.IO.Streams as Streams

main :: IO ()
main = do
     someFunc
     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}
     (defs, is) <- query_ conn "SELECT * FROM memos"
     --print =<< Streams.toList is
     mapM_ print =<< Streams.toList is
```
```
someFunc
[MySQLInt32 3,MySQLText "name2",MySQLText "comment5",MySQLNull]
[MySQLInt32 4,MySQLText "name3",MySQLText "comment3",MySQLNull]
[MySQLInt32 5,MySQLNull,MySQLText "abc",MySQLNull]
[MySQLInt32 9,MySQLText "name",MySQLText "comment",MySQLNull]
[MySQLInt32 10,MySQLText "name",MySQLText "comment",MySQLNull]
[MySQLInt32 11,MySQLText "name",MySQLText "tempula",MySQLNull]
[MySQLInt32 12,MySQLText "name",MySQLText "happy",MySQLNull]
```
[https://github.com/ringo-apo/hs_mariadb.git](https://github.com/ringo-apo/hs_mariadb.git)  
### Sample2
```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import qualified Data.Text.IO as T
import Data.Text

main :: IO ()
main = do
    someFunc

    conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}
    (defs, is) <- query_ conn "SELECT * FROM memos"
    --print =<< Streams.toList is
    --mapM_ print =<< Streams.toList is

    mapM_ (mapM_ f) =<< Streams.toList is

  where
    -- 受け取った引数が MySQLText の場合だけ、取り出した文字列をputStrLnする関数
    f :: MySQLValue -> IO ()
    f (MySQLText text) = do
        T.putStr text
        T.putStr " "
    f (MySQLInt32 int) = do
        T.putStr (Data.Text.pack (show int))
        T.putStr " "
    --f _other = return ()
    f _other = T.putStrLn ""
```
```
apo@tux ~/doc/project/make/haskell/mariadb_select/my-project $ stack exec my-project-exe
someFunc
3 name2 comment5
4 name3 comment3
5
abc
9 name comment
10 name comment
11 name tempula
12 name happy
```
### sample3 日付が入ったリスト
```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
--import Database.MySQL.Simple
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import qualified Data.Text.IO as T
import Data.Text

main :: IO ()
main = do

--    conn <- connect defaultConnectInfo { connectHost = "localhost", connectPort = 3306, connectUser = "root", connectPassword = "password", connectDatabase = "test" }
    conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}
    (defs, is) <- query_ conn "SELECT id, name, comment, time FROM memos"
    --mapM_ putStrLn $ map show (rs :: [(Int, Maybe String, Maybe String)])
    mapM_ (mapM f) =<< Streams.toList is
        where
            -- 受け取った引数が MySQLText の場合だけ、取り出した文字列をputStrLnする関数
            f :: MySQLValue -> IO ()

            f (MySQLText text) = do
                T.putStr text
                T.putStr " "

            f (MySQLInt32 int) = do
                T.putStr (Data.Text.pack (show int))
                T.putStr " "

            f (MySQLDateTime text) = do
                T.putStr (Data.Text.pack (show text))
                T.putStrLn ""

            f _other = return ()

            --f _other = T.putStrLn ""
```
```
3 name2 comment5 2020-08-03 08:52:00
4 name3 comment3 2020-08-04 07:39:00
5 name abc 2020-08-04 07:39:00
9 name comment 2020-08-04 07:39:00
10 name comment 2020-08-04 07:39:00
11 name tempula 2020-08-04 07:39:00
12 name happy 2020-08-04 07:39:00
```
## Insert
[https://github.com/ringo-apo/hs_mariadb_insert.git](https://github.com/ringo-apo/hs_mariadb_insert.git)  
stack.yaml  
```
resolver:lts-14.18
```
package.yaml  
```
dependencies:
- base >= 4.7 && < 5
- io-streams
- mysql-haskell
- text
```
Main.hs
```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Control.Exception
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import Data.Text.Internal (Text(..), safe, text)

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a

main :: IO ()
main = do
     someFunc

     word <- getLine
     let dtword = read ("\"" ++ word ++ "\"") :: Data.Text.Internal.Text

     conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "Password1234!", ciDatabase = "test"}

     stmt <- prepareStmt conn "insert into test (comment) values (?)"

     transactional conn $ do
       executeStmt conn stmt [MySQLText dtword]

       (defs, is) <- query_ conn "SELECT * FROM test"
       mapM_ print =<< Streams.toList is
```
## Delete
stack.yaml  
```
resolver:lts-14.18
```
package.yaml  
```
dependencies:
- base >= 4.7 && < 5
- io-streams
- mysql-haskell
- text
```
Main.hs
```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import Control.Exception
import Data.Text.Internal (Text(..), safe, text)

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a


main :: IO ()
main = do
    someFunc

    let dtword = "akira"
    let id = 2

    conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}

    --stmt <- prepareStmt conn "delete from memos where name=(?)"
    stmt <- prepareStmt conn "delete from memos where id=(?)"

    transactional conn $ do
        executeStmt conn stmt [MySQLInt8 id]

    (defs, is) <- query_ conn "SELECT * FROM memos"
    mapM_ print =<< Streams.toList is
```
[https://github.com/ringo-apo/Haskell_MariaDB_Delete](https://github.com/ringo-apo/Haskell_MariaDB_Delete)  
## Update
stack.yaml  
```
resolver:lts-14.18
```
package.yaml  
```
dependencies:
- base >= 4.7 && < 5
- io-streams
- mysql-haskell
- text
```
Main.hs
```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import Control.Exception
import Data.Text.Internal (Text(..), safe, text)

transactional :: MySQLConn -> IO a -> IO a
transactional conn procedure = mask $ \restore -> do
  execute_ conn "BEGIN"
  a <- restore procedure `onException` (execute_ conn "ROLLBACK")
  execute_ conn "COMMIT"
  pure a


main :: IO ()
main = do
    someFunc

    let dtword = "akira"
    let id = 3

    conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}

    --stmt <- prepareStmt conn "delete from memos where name=(?)"
    stmt <- prepareStmt conn "update memos set comment='comment5' where id=(?)"

    transactional conn $ do
        executeStmt conn stmt [MySQLInt8 id]

    (defs, is) <- query_ conn "SELECT * FROM memos"
    mapM_ print =<< Streams.toList is
```
[https://github.com/ringo-apo/Haskell_MariaDB_Update](https://github.com/ringo-apo/Haskell_MariaDB_Update)  
# Docker
docker-comose.yml  
```
version: '3'
services:

  haskell:
    build: ./haskell
    container_name: '${COMPOSE_PROJECT_NAME}-haskell'
    tty: true
    volumes:
      - "../src/haskell:/opt/src"
```
Dockerfile
```
FROM centos:centos7

RUN curl -sSL https://get.haskellstack.org/ | sh

# stackインストール
RUN stack upgrade
RUN stack --version

# stack の初期設定
RUN stack setup
```
コンテナ作成
```
cd ./docker
docker-compose build
docker-compose up -d
```
実行
```
docker exec -it haskell-docker-starter-haskell bash

# 以下 Docker の中
cd /opt/src
stack new sample-project
```
[https://qiita.com/dd0125/items/a141000ead36b3823fde](https://qiita.com/dd0125/items/a141000ead36b3823fde)  
# \<stderr>: commitAndReleaseBuffer: invalid argument (invalid character)
Windowsの場合に出てくるエラー。  
```
chcp 65001
```
[https://haskell.jp/blog/posts/2017/windows-gotchas.html](https://haskell.jp/blog/posts/2017/windows-gotchas.html)  
  
# トランプ
[http://tune.hateblo.jp/entry/2015/05/12/023112](http://tune.hateblo.jp/entry/2015/05/12/023112)  
[前記のソースコード](https://github.com/tokiwoousaka/draw-poker)  
※lts-3.22に変更必要  
  
# HDBC-mysql 0.6.6.1
[Haskellからmysqlを実行する - 椿の日記](http://tsubaki.hatenablog.com/entry/20121020/1350734844)  
package.yaml
```
dependencies:
- HDBC
```
stack.yaml
```
resolver: lts-14.27
```
  
# 無料電子ブック「学習 Haskell Language」
[https://riptutorial.com/Download/haskell-language-ja.pdf](https://riptutorial.com/Download/haskell-language-ja.pdf)
  
# 演算子 =<<
[Haskell アクション 超入門 - Qiita](https://qiita.com/7shi/items/85afd7bbd5d6c4115ad6)  

# tuple　タプル
```
module Main where

import Lib

main :: IO ()
main = do
    someFunc
    let a = (1, 2, "test")
    print a
```
  
# list 
```
module Main where

main :: IO ()
main = do
    let a = [1,5,3,4,6,7]
    print a
```
# sample
リストから同じ数値が続いていれば外す。
```
apo@larry ~/doc/project/make/haskell/nub/my-project $ cat ./app/Main.hs
module Main where

nub :: (Eq a) => [a] -> [a]
nub [] = []
nub (x:xs)
 | x `elem` xs = nub xs
 | otherwise    = x : nub xs


main :: IO ()
main = do
   let a = nub [1,5,8,2]
   putStrLn (show a)

   let b = nub [1,1,1,3,3,3,4,5]
   putStrLn (show b)
apo@larry ~/doc/project/make/haskell/nub/my-project $ stack exec my-project-exe
[1,5,8,2]
[1,3,4,5]
```
[https://www.youtube.com/watch?v=Cxkqrg8FCt8](https://www.youtube.com/watch?v=Cxkqrg8FCt8)  
# tuple & list
```
module Main where

main :: IO ()
main = do
    let a = [(1,2,"test"), (3,4,"test2"), (5,6,"test3")]
    print a
```
  
# リストからｎ番目を取り出す
```
module Main where

main :: IO ()
main = do
    let a = [(1,2,"test"), (3,4,"test2"), (5,6,"test3")]
    print a
    print (a !! 1)
```
```
[(1,2,"test"),(3,4,"test2"),(5,6,"test3")]
(3,4,"test2")
```
  
# レコード構文
```
module Main where

data Foo = Foo { id :: Int, price :: Int, name :: String } deriving Show

main :: IO ()
main = do
    let a = Foo 1 100 "ringo"
    print a
```
```
Foo {id = 1, price = 100, name = "ringo"}
```
# record & list
```
module Main where

data Foo = Foo { id :: Int, price :: Int, name :: String } deriving Show

main :: IO ()
main = do
    let a = Foo 1 100 "ringo"
    let b = Foo 2 500 "ichigo"
    let c = Foo 3 300 "banana"

    let d = [a, b, c]

    print d
```
```
[Foo {id = 1, price = 100, name = "ringo"},Foo {id = 2, price = 500, name = "ichigo"},Foo {id = 3, price = 300, name = "banana"}]
```
# pickup n
```
module Main where

data Foo = Foo { id :: Int, price :: Int, name :: String } deriving Show

main :: IO ()
main = do
    let a = Foo 1 100 "ringo"
    let b = Foo 2 500 "ichigo"
    let c = Foo 3 300 "banana"

    let d = [a, b, c]

    print d
    print (d !! 1)
```
```
[Foo {id = 1, price = 100, name = "ringo"},Foo {id = 2, price = 500, name = "ichigo"},Foo {id = 3, price = 300, name = "banana"}]
Foo {id = 2, price = 500, name = "ichigo"}
```
  
# パターンマッチ（pattern match）
```
module Main where

data Foo = Foo { id :: Int, price :: Int, name :: String } deriving Show

main :: IO ()
main = do
    let a = Foo 1 100 "ringo"
    let b = Foo 2 500 "ichigo"
    let c = Foo 3 300 "banana"

    let d = [a, b, c]

    print d
    print (d !! 1)

    let (Foo { name = c }) = b 
    print c
```
```
[Foo {id = 1, price = 100, name = "ringo"},Foo {id = 2, price = 500, name = "ichigo"},Foo {id = 3, price = 300, name = "banana"}]
Foo {id = 2, price = 500, name = "ichigo"}
"ichigo"
```
## sample2
```
module Main where

lucky :: Int -> String
lucky 7 = "LUCKY NUMBER SEVEN!"
lucky x = "Sorry, you're out of luck, pal!"

main :: IO ()
main = do
    putStrLn ("Input any number.")
    nums <- getLine
    let num = read nums :: Int
    let numl = lucky num

    putStrLn (numl)
```
```
Input any number.
5
Sorry, you're out of luck, pal!
```
「すごいHaskellたのしく学ぼう！」p35  
## sample3
```
module Main where

sayMe :: Int -> String
sayMe 1 = "One!"
sayMe 2 = "Two!"
sayMe 3 = "Three!"
sayMe 4 = "Four!"
sayMe 5 = "Five!"
sayMe x = "Not between 1 and 5"

main :: IO ()
main = do
    putStrLn ("Input any number.")
    nums <- getLine
    let num = read nums :: Int
    let _sayMe = sayMe num

    putStrLn (_sayMe)
```
```
apo@tux ~/doc/project/make/haskell/patternMatch_sample2/my-project $ stack exec my-project-exe
Input any number.
3
Three!
apo@tux ~/doc/project/make/haskell/patternMatch_sample2/my-project $ stack exec my-project-exe
Input any number.
6
Not between 1 and 5
```
「すごいHaskellたのしく学ぼう！」p36  
## sample4
```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import Database.MySQL.Base
import qualified System.IO.Streams as Streams
import qualified Data.Text.IO as T
import Data.Text

main :: IO ()
main = do

    conn <- connect
        defaultConnectInfo {ciUser = "root", ciPassword = "password", ciDatabase = "test"}
    (defs, is) <- query_ conn "SELECT id, name, comment, time FROM memos"
    mapM_ (mapM f) =<< Streams.toList is
        where
            f :: MySQLValue -> IO ()

            f (MySQLText text) = do
                T.putStr text
                T.putStr " "

            f (MySQLInt32 int) = do
                T.putStr (Data.Text.pack (show int))
                T.putStr " "

            f (MySQLDateTime text) = do
                T.putStr (Data.Text.pack (show text))
                T.putStrLn ""

            f _other = return ()
```
```
apo@tux ~/doc/project/make/haskell/mariadb_select/my-project $ stack exec my-project-exe
3 name2 comment5 2020-08-03 08:52:00
4 name3 comment3 2020-08-04 07:39:00
5 name abc 2020-08-04 07:39:00
9 name comment 2020-08-04 07:39:00
10 name comment 2020-08-04 07:39:00
11 name tempula 2020-08-04 07:39:00
12 name happy 2020-08-04 07:39:00
```
# レコード構文（Record） & パターンマッチ（pattern match） & pickup n
```
module Main where

data Foo = Foo { id :: Int, price :: Int, name :: String } deriving Show

main :: IO ()
main = do
    let a = Foo 1 100 "ringo"
    let b = Foo 2 500 "ichigo"
    let c = Foo 3 300 "banana"

    let d = [a, b, c]

    print d
    print (d !! 1)

    let (Foo { name = c }) = d !! 2 
    print c
```
```
[Foo {id = 1, price = 100, name = "ringo"},Foo {id = 2, price = 500, name = "ichigo"},Foo {id = 3, price = 300, name = "banana"}]
Foo {id = 2, price = 500, name = "ichigo"}
"banana"
```
# レコード構文サンプル reocrd data
```
apo@larry ~/doc/project/make/haskell/data/my-project $ cat ./app/Main.hs
module Main where

data Syain = Syain { syainId :: Int, name :: String, syainDiv :: String }

syain1 = Syain {syainId = 1, name = "Tanaka", syainDiv = "営業第１部" }
syain2 = Syain {syainId = 2, name = "Yamada", syainDiv = "開発部" }
syain3 = Syain {syainId = 3, name = "Ito", syainDiv = "総務部" }

syains = [syain1, syain2, syain3]

main :: IO ()
main = do

    let serchId = 1

    let getSyain = syains !! serchId

    let getSyainId = syainId getSyain
    let getName = name getSyain
    let getSyainDiv = syainDiv getSyain

    putStrLn ("id = " ++ show (getSyainId))
    putStrLn ("name = " ++ getName)
    putStrLn ("syainDiv = " ++ getSyainDiv)

apo@larry ~/doc/project/make/haskell/data/my-project $ stack exec my-project-exe
id = 2
name = Yamada
syainDiv = 開発部
```
[http://walk.northcol.org/haskell/adts/](http://walk.northcol.org/haskell/adts/)  
# Excel
[https://hackage.haskell.org/package/xlsx](https://hackage.haskell.org/package/xlsx)  
[https://sirocco.hatenadiary.org/entry/20101014/1287038347](https://sirocco.hatenadiary.org/entry/20101014/1287038347)  
## xlsx
[https://hackage.haskell.org/package/xlsx](https://hackage.haskell.org/package/xlsx)  
### sample
[https://hackage.haskell.org/package/xlsx-0.8.2/docs/Codec-Xlsx.html](https://hackage.haskell.org/package/xlsx-0.8.2/docs/Codec-Xlsx.html)  
stack.yaml
```
E:\300GB_HDD\data\Project\make\haskell\xlsx\my-project>type stack.yaml

resolver: lts-16.20

packages:
- .
```
package.yaml
```
E:\300GB_HDD\data\Project\make\haskell\xlsx\my-project>type package.yaml

dependencies:
- base >= 4.7 && < 5
- xlsx
- bytestring
- lens
```
app\Main.hs
```
E:\300GB_HDD\data\Project\make\haskell\xlsx\my-project>type app\Main.hs

{-# LANGUAGE OverloadedStrings #-}

--module Read where
module Main where

import Codec.Xlsx
import qualified Data.ByteString.Lazy as L
import Control.Lens

main :: IO ()
main = do
  bs <- L.readFile "report.xlsx"
  let value = toXlsx bs ^? ixSheet "Sheet1" .
              ixCell (3,2) . cellValue . _Just
  putStrLn $ "Cell B3 contains " ++ show value
```
my-projectフォルダ配下に「report.xlsx」ファイルを作成。  
B3セルに「hello」と記載  
  
実行結果  
```
E:\300GB_HDD\data\Project\make\haskell\xlsx\my-project>stack exec my-project-exe.exe

Stack has not been tested with GHC versions above 8.6, and using 8.8.4, this may fail
Stack has not been tested with Cabal versions above 2.4, but version 3.0.1.0 was found, this may fail

Cell B3 contains Just (CellText "hello")
```
# ブラックジャック
[https://employment.en-japan.com/engineerhub/entry/2017/09/11/110000](https://employment.en-japan.com/engineerhub/entry/2017/09/11/110000)  
```
git clone https://gitlab.com/igrep/haskell-as-second-language-blackjack.git
cd haskell-as-second-language-blackjack
stack test
```
[https://gitlab.com/igrep/haskell-as-second-language-blackjack](https://gitlab.com/igrep/haskell-as-second-language-blackjack)  
  
# MySQLでT.putStrLnを使用する
Main.hs
```
import qualified Data.Text as T (pack)
import qualified Data.Text.IO as T (putStrLn)

main = T.putStrLn (T.pack "こんにちは")
```
package.yaml
```
dependencies:
- text
```
[https://books.google.co.jp/books?id=_4RqDwAAQBAJ&pg=PT19&lpg=PT19&dq=T.putStrLn&source=bl&ots=c8h9XUH7M6&sig=ACfU3U1YvmQa1SOIx_6THNAoQhwCIF39fg&hl=ja&sa=X&ved=2ahUKEwiC9-CrtOHoAhUBL6YKHVNNDx4Q6AEwBnoECAsQLA#v=onepage&q=T.putStrLn&f=false](https://books.google.co.jp/books?id=_4RqDwAAQBAJ&pg=PT19&lpg=PT19&dq=T.putStrLn&source=bl&ots=c8h9XUH7M6&sig=ACfU3U1YvmQa1SOIx_6THNAoQhwCIF39fg&hl=ja&sa=X&ved=2ahUKEwiC9-CrtOHoAhUBL6YKHVNNDx4Q6AEwBnoECAsQLA#v=onepage&q=T.putStrLn&f=false)  
[http://bicycle1885.hatenablog.com/entry/2012/12/24/234707](http://bicycle1885.hatenablog.com/entry/2012/12/24/234707)  
[https://github.com/ringo-apo/mysql-haskell_20200406](https://github.com/ringo-apo/mysql-haskell_20200406)  
  
# forM
C#などにあるforeachに似た処理を行う関数です。  
```
import Control.Monad

main = do
    a <- forM [1..3] $ \i -> do
        print i
        return i
    print a
```
```
1
2
3
[1,2,3]
```
[https://qiita.com/7shi/items/4a8a2807bb5186576c61](https://qiita.com/7shi/items/4a8a2807bb5186576c61)  
  
# forM_
forMの戻り値を捨てる版です。  
```
import Control.Monad

main = do
    forM_ [1..3] $ \i -> do
        print i
```
```
1
2
3
```
[https://qiita.com/7shi/items/4a8a2807bb5186576c61](https://qiita.com/7shi/items/4a8a2807bb5186576c61)  
  
# when
ifではelseを省略できませんが、それに相当する関数がwhenです。  
```
import Control.Monad
import System.Random

dice :: IO Int
dice = getStdRandom $ randomR (1, 6)

main = do
    r <- dice
    print r
    when (r /= 3) main
```
```
1
5
3
```
[https://qiita.com/7shi/items/4a8a2807bb5186576c61](https://qiita.com/7shi/items/4a8a2807bb5186576c61)  
  
# 文字列、テキスト型　String型
```
import Data.Text    as DT 
import Data.Text.IO as DTI 
 
-- 先頭のn行を得る 
headNLines :: Int -> Text -> Text 
headNLines n cs =   
    DT.unlines $ Prelude.take n $ DT.lines cs  
 
main :: IO () 
main = do  
    cs <- DTI.readFile "str1.hs"  
    DTI.putStr $ headNLines 5 cs
```
[https://www.nslabs.jp/haskell-string.rhtml](https://www.nslabs.jp/haskell-string.rhtml)  
  
# 文字列、テキスト型　ByteString型
```
{-# LANGUAGE OverloadedStrings #-} 
 
import Data.ByteString       as BS 
import Data.ByteString.Char8 as BSC 
import System.IO 
 
main :: IO () 
main = do 
    Prelude.putStr "何か入力> " 
    hFlush stdout 
    str <- BS.getLine 
    BSC.putStrLn $ "str = " `BS.append` str 
    Prelude.putStrLn $ (show $ BS.length str) ++ " bytes"
```
[https://www.nslabs.jp/haskell-string.rhtml](https://www.nslabs.jp/haskell-string.rhtml)  
  
# 文字列、テキスト型　Text型
```
import Data.Text 
import Data.Text.Encoding 
import qualified Data.ByteString 
 
countChars :: Data.ByteString.ByteString -> Int 
countChars s = Data.Text.length $ Data.Text.Encoding.decodeUtf8 s 
 
main = do 
  cs <- Data.ByteString.readFile "str2.txt" 
  print $ countChars cs
```
[https://www.nslabs.jp/haskell-string.rhtml](https://www.nslabs.jp/haskell-string.rhtml)  
  
# 文字列の長さ
```
{-# LANGUAGE OverloadedStrings #-} 
 
import Data.ByteString       as BS 
import Data.ByteString.Char8 as BSC 
import System.IO 
 
main :: IO () 
main = do 
    Prelude.putStr "何か入力> " 
    hFlush stdout 
    str <- BS.getLine 
    BSC.putStrLn $ "str = " `BS.append` str 
    Prelude.putStrLn $ (show $ BS.length str) ++ " bytes"
```
[https://www.nslabs.jp/haskell-string.rhtml](https://www.nslabs.jp/haskell-string.rhtml)  
  
# OpenGL
インストール  
```
cabal install OpenGL
```
[https://sites.google.com/site/toriaezuzakki/haskell/opengl](https://sites.google.com/site/toriaezuzakki/haskell/opengl)  
```
stack install OpenGL
```
# Webフレームワーク
・Yesod
[https://www.yesodweb.com/](https://www.yesodweb.com/)  
・Scotty
[https://github.com/scotty-web/scotty](https://github.com/scotty-web/scotty)  
・Miso
[https://github.com/dmjio/miso](https://github.com/dmjio/miso)  
・Servant
[https://www.servant.dev/](https://www.servant.dev/)  
・Happstrack
[http://happstack.com/page/view-page-slug/1/happstack](http://happstack.com/page/view-page-slug/1/happstack)  
・Snap
[http://snapframework.com/](http://snapframework.com/)  
・Spock
[https://github.com/agrafix/Spock](https://github.com/agrafix/Spock)  
# Scotty
「package.yaml」ファイルに追加  
```
- http-types
- aeson
- scotty
```
Sample.hs  
```
{-# LANGUAGE OverloadedStrings #-}
module Sample where
import Web.Scotty
main :: IO ()
main = scotty 3000 $ get "/" $ html "<h1>Hello</h1>"
```
```
http://localhost:3000/
```
[https://qiita.com/toru0408/items/db417dc7f761d00839eb](https://qiita.com/toru0408/items/db417dc7f761d00839eb)  
[https://qiita.com/ryota-ka/items/b0883ce87d60b9f573e7](https://qiita.com/ryota-ka/items/b0883ce87d60b9f573e7)  
# datetime - 日付の一部を文字列として取得するHaskell関数
[https://ja.coder.work/so/datetime/949401](https://ja.coder.work/so/datetime/949401)  
# add'
```
module Main where

import Lib

add' :: Int -> (Int -> Int)
add' x y = x+y


main :: IO ()
main = do
    someFunc

    print(add' 1 2)
```
# 大富豪
[http://myuon-myon.hatenablog.com/entry/2015/07/15/181652](http://myuon-myon.hatenablog.com/entry/2015/07/15/181652)  
[https://github.com/ringo-apo/daifugo](https://github.com/ringo-apo/daifugo)  
# 各桁の合計が40になる最初の自然数
「すごいHな本」p98  
Main.hs  
```
module Main where

import Data.Char
import Data.List

digitSum :: Int -> Int
digitSum = sum . map digitToInt . show

firstTo40 :: Maybe Int
firstTo40 = find (\x -> digitSum x == 40) [1..]

main :: IO ()
main = do

    print(firstTo40)
```
# 素数
[https://qiita.com/ttatsf/items/510ec0cd4ad99fef9424](https://qiita.com/ttatsf/items/510ec0cd4ad99fef9424)  
```
module Main where

import Lib

primes :: Int -> [Int]
primes 2 = [ 2 ]
primes n =   primes (n - 1) ++ isPrime n
  where

    isPrime :: Int -> [Int]
    isPrime 3 = [ 3 ]
    isPrime n
      | even n      = [ ]
      | notPrime n  = [ ]
      | otherwise   = [ n ]

    notPrime :: Int -> Bool
    notPrime n =
      elem 0 . map (mod n ) . tail .  primes . floor . sqrt . fromIntegral $ n

main :: IO ()
main = do
    someFunc

    print $ primes 100
```
# メール送信
[https://n314.hatenablog.com/entry/20100623/1277261679](https://n314.hatenablog.com/entry/20100623/1277261679)  
# リストを加工して新しいリストを作るサンプル
./app/Main.hs  
```
module Main where

import Lib

fmapIntList = fmap :: (Int -> Int) -> [Int] -> [Int]

main :: IO ()
main = do
    someFunc

    let a = fmapIntList (* 10) [1,3,5]
    print (a)
```
```
apo@tux ~/doc/project/make/haskell/hello/my-project $ stack exec my-project-exe
someFunc
[10,30,50]
```
# 16進数表示
```
module Main where

import Numeric(showHex)

ph x = do
    if x == []
        then print "end"
        else print $ (show (head x)) ++ " " ++ (showHex (head x) "")
    ph (tail x)


main :: IO ()
main = do
    let a = [0..16]
    ph a
```
# take リストの最初からn番目までのリストを取り出す
```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    let a = [1,2,3,4,5]
    print a

    let b = take 3 a
    print b
```
```
someFunc
[1,2,3,4,5]
[1,2,3]
```
# タプル
```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    let a = [(1,3,"abc"),(1,10,"apple"),(2,100,"banana"),(3,0,"ichigo")]
    print a
    print (a !! 2)

    let (data1, data2, data3) = (a !! 2)
    print data3
```
```
someFunc
[(1,3,"abc"),(1,10,"apple"),(2,100,"banana"),(3,0,"ichigo")]
(2,100,"banana")
"banana"
```
[https://qiita.com/7shi/items/145f1234f8ec2af923ef](https://qiita.com/7shi/items/145f1234f8ec2af923ef)  
# lens
package.yaml  
```
dependencies:
- lens
```
Main.hs  
```
module Main where

import Control.Lens

main :: IO ()
main = do
    let value = (1, (2, 3, (999, 4, 5)), 6)

    print value
    print (value ^. _2 . _3 . _1)
```
```
(1,(2,3,(999,4,5)),6)
999
```
# MySQL HDBC-mysql
[http://tsubaki.hatenablog.com/entry/20121020/1350734844](http://tsubaki.hatenablog.com/entry/20121020/1350734844)  
```
test.hs
----------
import Control.Monad
import Database.HDBC
import Database.HDBC.MySQL
main = do conn <- connectMySQL defaultMySQLConnectInfo {
                     mysqlHost     = "127.0.0.1",
                     mysqlUser     = "testuser",
                     mysqlPassword = "password",
                     mysqlDatabase = "testdb"
                  }

          rows <- quickQuery' conn "SELECT 1 + 1" []
          forM_ rows $ \row -> putStrLn $ show row
```
```
c:\usr\work> test
[SqlInt64 2]
```
# stackでghci
```
stack ghci

*Main.Lib>

*Main.Lib>:quit  --終了
```
## 型を調べる
```
*Main Lib> :t foldl
foldl :: Foldable t => (b -> a -> b) -> b -> t a -> b
```
```
*Main Lib> :t foldr
foldr :: Foldable t => (a -> b -> b) -> b -> t a -> b
```
# foldl, foldr
```
module Main where

main :: IO ()
main = do
    print ("foldl (-) 0 [1,2,3,4] = " ++ (show (foldl (-) 0 [1,2,3,4])))
    print ("foldr (-) 0 [1,2,3,4] = " ++ (show (foldr (-) 0 [1,2,3,4])))
```
```
"foldl (-) 0 [1,2,3,4] = -10"  -- ((((0-1)-2)-3)-4) = -10
"foldr (-) 0 [1,2,3,4] = -2"   -- 4-(3-(2-(1-0))) = -2
```
## sample2
```
module Main where

main :: IO ()
main = do
    print ("foldl (-) 10 [1,2,3] = " ++ (show (foldl (-) 10 [1,2,3])))
    print ("foldr (-) 10 [1,2,3] = " ++ (show (foldr (-) 10 [1,2,3])))
```
```
"foldl (-) 10 [1,2,3] = 4"  -- (((10-1)-2)-3 = 4
"foldr (-) 10 [1,2,3] = -8"  -- 1-(2-(3-10)) = -8
```
# let

```
module Main where

main :: IO ()
main = do

    let a = 5
    putStrLn ("a = " ++ (show a))

    let b = a
    putStrLn ("b = " ++ (show b))

    let a = b + 7
    putStrLn ("a = " ++ (show a))
```

```
a = 5
b = 5
a = 12
```
# Function -- 関数

```
module Main where

import Lib

in_range min max x =
    x >= min && x <= max

main :: IO ()
main = do
    someFunc

    let a = in_range 0 5 3
    let b = in_range 4 5 3

    print a
    print b
```

```
someFunc
True
False
```
# 代数的データ型
以下の3つを合わせて代数的データ型と呼びます。  
  
列挙型（他言語のenumに相当）  
直積型（他言語のstructに相当）  
直和型（他言語のunionに相当）  
[https://qiita.com/7shi/items/1ce76bde464b4a55c143](https://qiita.com/7shi/items/1ce76bde464b4a55c143)  
## 列挙型

```
data Color = Blue | Red | Green | White deriving Show
```
型とコンストラクタは大文字で始める必要があります。  
小文字で始めるとエラーになります。  
## 直積型

```
data Point = Point Int Int deriving Show

offset (Point x1 y1) (Point x2 y2) =
    Point (x1 + x2) (y1 + y2)

main = do
    let a = Point 2 3
        b = Point 1 1
        c = offset a b
    print c
```

```
Point 3 4
```
## 直和型 Direct sum type

```
module Main where

import Lib

data Test = TestInt Int
          | TestStr String
          deriving Show

foo (TestInt  1 ) = "bar"
foo (TestStr "1") = "baz"
foo _             = "?"

main :: IO ()
main = do
    someFunc

    print $ foo $ TestInt  0
    print $ foo $ TestInt  1
    print $ foo $ TestStr "0"
    print $ foo $ TestStr "1"
```

```
someFunc
"?"
"bar"
"?"
"baz"
```
[https://qiita.com/7shi/items/1ce76bde464b4a55c143](https://qiita.com/7shi/items/1ce76bde464b4a55c143)  
# Listから値の取り出し

```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    let a = [[1,2],[3,4],[5,6]]

    putStrLn (show a)

    let a1 = (a !! 0) !! 0
    let a2 = (a !! 0) !! 1

    let a3 = (a !! 1) !! 0
    let a4 = (a !! 1) !! 1

    let a5 = (a !! 2) !! 0
    let a6 = (a !! 2) !! 1

    putStrLn (show a1)
    putStrLn (show a2)
    putStrLn (show a3)
    putStrLn (show a4)
    putStrLn (show a5)
    putStrLn (show a6)

    putStrLn (show a1 ++ ":" ++ show a2)
    putStrLn (show a3 ++ ":" ++ show a4)
    putStrLn (show a5 ++ ":" ++ show a6)
```

```
someFunc
[[1,2],[3,4],[5,6]]
1
2
3
4
5
6
1:2
3:4
5:6
```
# Int -> Double  fromIntegral

```
module Main where

import Lib

half :: Int -> Double
half n = (fromIntegral n)/2

main :: IO ()
main = do
    someFunc

    let a = 5
    let b = half a
    putStrLn (show b)
```

```
[apo@localhost my-project]$ stack exec my-project-exe
someFunc
2.5
```
# 書籍『入門Haskellプログラミング』
## Lesson 15
List 15-10

```
module Main where

import Lib

data FourLetterAlphabet = L1 | L2 | L3 | L4 deriving (Show, Enum, Bounded)

data TreeLetterAlphabet = Alpha
                        | Beta
                        | Kappa deriving (Show, Enum, Bounded)

threeLetterMessage :: [ThreeLetterAlphabet]
threeLetterMessage = [Alpha, Alpha, Beta, Alpha, Kappa]

rotN :: (Bounded a, Enum a) => Int -> a -> a
rotN alphabetSize c = toEnum rotation
    where halfAlphabet = alphabetSize `div` 2
        offset = fromEnum c + halfAlphabet
        rotation = offset 'mod' alphabetSize

rotNdecoder :: (Bounded a, Enum a) => Int -> a -> a
rotNdecoder n c = toEnum rotation
    where halfN = n 'div' 2
        offset = if even n
                 then fromEnum c + halfN
                 else 1 + fromEnum c + halfN
        rotation = offset 'mod' n

largestCharNumber :: Int
largestCharNumber = fromEnum (maxBound :: Char)

rotChar :: Char -> Char
rotChar charToEncrypt = rotN sizeOfAlphabet charToEncrypt
    where sizeOfAlphabet = 1 + fromEnum (maxBound :: Char)

fourLetterMessage :: [FourLetterAlphabet]
fourLetterMessage = [L1, L3, L4, L1, L1, L2]

rotEncoder :: String -> String
rotEncoder test = map rotChar text
    where alphaSize = 1 + fromEnum (maxBound :: Char)
        rotChar = rotN alphaSize

rotDecoder :: String -> String
rotDecoder test = map rotCharDecoder text
    where alphaSize = 1 + fromEnum (maxBound :: Char)
        rotCharDecoder = rotNdecoder alphaSize

threeLetterEncoder :: [ThreeLetterAlphabet] -> [ThreeLetterAlphabet]
threeLetterEncoder vals = map rot3l vals
    where alphaSize = 1 + fromEnum (maxBound :: ThreeLetterAlphabet)
        rot3l = rotN alphaSize

threeLetterDecoder :: [ThreeLetterAlphabet] -> [ThreeLetterAlphabet]
threeLetterDecoder vals = map rot3ldecoder vals
    where alphaSize = 1 + fromEnum (maxBound :: ThreeLetterAlphabet)
        rot3ldecoder = rotNdecoder alphaSize

fourLetterEncoder :: [FourLetterAlphabet] -> [FourLetterAlphabet]
fourLetterEncoder vals = map rot4l vals
    where alphaSize = 1 + fromEnum (maxBound :: FourLetterAlphabet)
        rot4l = rotN alphaSize

fourLetterDecoder :: [FourLetterAlphabet] -> [FourLetterAlphabet]
fourLetterDecoder vals = map rot4ldecoder vals
    where alphaSize = 1 + fromEnum (maxBound :: FourLetterAlphabet)
        rot4ldecoder = rotNdecoder alphaSize

main :: IO ()
main = do
    someFunc
```
# 遅延評価 Lazy evaluation
『Haskell入門』p7  

```
apo@gentoo ~/Documents/project/make/haskell/lazy/my-project $ cat ./app/Main.hs
module Main where

import Lib
import Debug.Trace(trace)
f x = trace "f" $ x ^ 2
g x = trace "g" $ x - 1

main :: IO ()
main = do
    someFunc

    let x = f 10
        y = g x
     in print y
apo@gentoo ~/Documents/project/make/haskell/lazy/my-project $ stack exec my-project-exe
someFunc
g
f
99
```
# Functor

```
module Main where

data Haskell a= Shit a | Easy a | Difficult a | Demon a

instance Functor Haskell where
    fmap func (Shit n) = Shit (func n)
    fmap func (Easy n) = Easy (func n)
    fmap func (Difficult n) = Difficult (func n)
    fmap func (Demon n) = Demon (func n)

main :: IO()
main = do
    let haskell_programing = Difficult 100

    let haskell = fmap ((-) 50) haskell_programing

    let a = (\(Difficult n) -> n) haskell

    print a
```

```
apo@larry ~/doc/project/make/haskell/functor/my-project $ stack exec my-project-exe
-50
```
[https://qiita.com/oskats1987/items/30f9078c5096372c232b](https://qiita.com/oskats1987/items/30f9078c5096372c232b)  
# Text型 LANGUAGE OverloadedStrings
Textを定義するためにリテラル文字列を使用するとエラーになる

```
apo@gentoo ~/Documents/project/make/haskell/OverloadedStrings/my-project $ cat ./package.yaml
dependencies:
- base >= 4.7 && < 5
- text

apo@gentoo ~/Documents/project/make/haskell/OverloadedStrings/my-project $ cat ./app/Main.hs
-- {-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import qualified Data.Text as T

myWord :: T.Text
myWord = "dog"

main :: IO ()
main = someFunc

apo@gentoo ~/Documents/project/make/haskell/OverloadedStrings/my-project $ stack build
my-project> configure (lib + exe)
Configuring my-project-0.1.0.0...
my-project> build (lib + exe)
Preprocessing library for my-project-0.1.0.0..
Building library for my-project-0.1.0.0..
Preprocessing executable 'my-project-exe' for my-project-0.1.0.0..
Building executable 'my-project-exe' for my-project-0.1.0.0..
[2 of 2] Compiling Main

/home/apo/Documents/project/make/haskell/OverloadedStrings/my-project/app/Main.hs:9:10: error:
    ~ Couldn't match expected type ‘T.Text’ with actual type ‘[Char]’
    ~ In the expression: "dog"
      In an equation for ‘myWord’: myWord = "dog"
  |
9 | myWord = "dog"
  |          ^^^^^


--  While building package my-project-0.1.0.0 using:
      /home/apo/.stack/setup-exe-cache/x86_64-linux-tinfo6/Cabal-simple_mPHDZzAJ_3.0.1.0_ghc-8.8.4 --builddir=.stack-work/dist/x86_64-linux-tinfo6/Cabal-3.0.1.0 build lib:my-project exe:my-project-exe --ghc-options " -fdiagnostics-color=always"
    Process exited with code: ExitFailure 1
```
「{-# LANGUAGE OverloadedStrings #-}」を追記する  

```
apo@gentoo ~/Documents/project/make/haskell/OverloadedStrings/my-project $ cat ./app/Main.hs
{-# LANGUAGE OverloadedStrings #-}

module Main where

import Lib
import qualified Data.Text as T

myWord :: T.Text
myWord = "dog"

main :: IO ()
main = someFunc

apo@gentoo ~/Documents/project/make/haskell/OverloadedStrings/my-project $ stack build
my-project> configure (lib + exe)
Configuring my-project-0.1.0.0...
my-project> build (lib + exe)
Preprocessing library for my-project-0.1.0.0..
Building library for my-project-0.1.0.0..
Preprocessing executable 'my-project-exe' for my-project-0.1.0.0..
Building executable 'my-project-exe' for my-project-0.1.0.0..
[2 of 2] Compiling Main
Linking .stack-work/dist/x86_64-linux-tinfo6/Cabal-3.0.1.0/build/my-project-exe/my-project-exe ...
my-project> copy/register
Installing library in /home/apo/Documents/project/make/haskell/OverloadedStrings/my-project/.stack-work/install/x86_64-linux-tinfo6/867323a3fef697852b1a41ad6a798b863ebce19620981449264bfe63d8593aa5/8.8.4/lib/x86_64-linux-ghc-8.8.4/my-project-0.1.0.0-ID1TW6SUq47nGxCS2NhH
Installing executable my-project-exe in /home/apo/Documents/project/make/haskell/OverloadedStrings/my-project/.stack-work/install/x86_64-linux-tinfo6/867323a3fef697852b1a41ad6a798b863ebce19620981449264bfe63d8593aa5/8.8.4/bin
Registering library for my-project-0.1.0.0..
```
「入門Haskellプログラミング」p278  
「すごいHな本」p384  
## Haskellで作るWebアプリケーション 第3章文字列はString型？
./package.yaml  

```
dependencies:
- base >= 4.7 && < 5
- text
```
./app/Main.hs  
言語拡張を使わない方法

```
import qualified Data.Text as T (pack)
import qualified Data.Text.IO as T (putStrLn)

main :: IO()
main = T.putStrLn (T.pack "こんにちは")
```
```
apo@gentoo ~/Documents/project/make/haskell/text/my-project $ stack exec my-project-exe
こんにちは
```
言語拡張を使う方法  

```
{-# LANGUAGE OverloadedStrings #-}

module Main where

import qualified Data.Text as T (pack)
import qualified Data.Text.IO as T (putStrLn)

main :: IO ()
main = do

    T.putStrLn "こんにちは"
```

```
apo@gentoo ~/Documents/project/make/haskell/text2/my-project $ stack exec my-project-exe
こんにちは
```
# シーザー暗号サラダ

```
apo@gentoo ~/Documents/project/make/haskell/encode/my-project $ cat ./app/Main.hs
module Main where

import Data.Char

encode :: Int -> String -> String
encode shift msg =
    let ords = map ord msg
        shifted = map (+ shift) ords
    in  map chr shifted

decode :: Int -> String -> String
decode shift msg = encode (negate shift) msg

main :: IO ()
main = do
    putStrLn(show (encode 3 "Heeeeey"))
    putStrLn(show (encode 4 "Heeeeey"))
    putStrLn(show (encode 1 "abcd"))
    putStrLn(show (encode 5 "Marry Christmas! Ho ho ho!"))

    putStrLn(show (encode 3 "Im a little teapot"))
    putStrLn(show (decode 3 "Lp#d#olwwoh#whdsrw"))
    putStrLn(show (decode 5 . encode 5 $ "This is a sentence"))
apo@gentoo ~/Documents/project/make/haskell/encode/my-project $ stack exec my-project-exe
"Khhhhh|"
"Liiiii}"
"bcde"
"Rfww~%Hmwnxyrfx&%Mt%mt%mt&"
"Lp#d#olwwoh#whdsrw"
"Im a little teapot"
"This is a sentence"
```
すごいHな本 p95  
[http://learnyouahaskell.com/modules](http://learnyouahaskell.com/modules)  
# I/O
getLineを２回繋げようとするとreturnが必要。  
  
参考  
Haskell入門  

```
*Main Lib> let joinLines = getLine >>= \s -> getLine >>= \t -> s ++ " : " ++ t

<interactive>:13:53: error:
    ~ Couldn't match type ‘[]’ with ‘IO’
      Expected type: IO Char
        Actual type: [Char]
    ~ In the expression: s ++ " : " ++ t
      In the second argument of ‘(>>=)’, namely ‘\ t -> s ++ " : " ++ t’
      In the expression: getLine >>= \ t -> s ++ " : " ++ t
*Main Lib> let joinLines = getLine >>= \s -> getLine >>= \t -> return $ s ++ " : " ++ t
*Main Lib> joinLines >>= putStrLn
hello
world
hello : world
```
# カリー化
２つ以上ある引数は、実は関数を返す関数。  

```
xcrypt 138689 13 4492
↓
((xcrypt 138689) 13) 4492
```
「Haskell教養としての関数型プログラミング」p84  
# Maybe
[https://qiita.com/7shi/items/c7d7eec066af0fe0688d](https://qiita.com/7shi/items/c7d7eec066af0fe0688d)  

```
apo@gentoo ~/Documents/project/make/haskell/mayby/my-project $ cat ./app/Main.hs
module Main where

import Control.Applicative

test (Just x) = x
test Nothing = 0

main :: IO ()
main = do

    print $ test $ Just 1
    print $ test $ Nothing

    let a = test $ Nothing
    let b = a + 1
    print b
apo@gentoo ~/Documents/project/make/haskell/mayby/my-project $ stack exec my-project-exe
1
0
1
```
# Maybeモナド

```
module Main where

div2 :: Int -> Maybe Int
div2 x = if even x then Just (x `div` 2)
                   else Nothing

-- x が 8 で割り切れない場合には失敗する
div8 :: Int -> Maybe Int
div8 x = return x >>= div2 >>= div2 >>= div2

main :: IO ()
main = do

    print $ div8 32  -- 出力: Just 4
    print $ div8 50  -- 出力: Nothing
```
```
apo@larry ~/doc/project/make/haskell/maybe/my-project $ stack exec my-project-exe
Just 4
Nothing
```
[walk.northcol.org/haskell/monads/](walk.northcol.org/haskell/monads/)  
## sample

```
apo@larry ~/doc/project/make/haskell/mayby_safediv/my-project $ cat ./app/Main.hs
module Main where

safediv :: Integral a => a -> a -> Maybe a
safediv a b = if b == 0 then Nothing else Just $ div a b

main :: IO ()
main = do

    let a = safediv 10 0
    putStrLn (show a)
apo@larry ~/doc/project/make/haskell/mayby_safediv/my-project $ stack exec my-project-exe
Nothing
```
[https://www.youtube.com/watch?v=O0iohEXMCsU](https://www.youtube.com/watch?v=O0iohEXMCsU)  
# =<<
[https://qiita.com/7shi/items/85afd7bbd5d6c4115ad6](https://qiita.com/7shi/items/85afd7bbd5d6c4115ad6)  
# コラッツの問題
./app/Main.hs  

```
module Main where

import Data.Bool (bool)

takeTo :: (a -> Bool) -> [a] -> [a]
takeTo p = foldr (\x -> (x :) . bool id (const []) (p x)) []

collatzInf :: Integer -> [Integer]
collatzInf = iterate $ \n -> bool (n * 3 + 1) (n `div` 2) (even n)

collatz :: Integer -> [Integer]
collatz = takeTo (==1) . collatzInf

main :: IO ()
main = do

    putStrLn ("Input any number.")
    numS <- getLine
    let num = read numS :: Integer
    let collatzL = collatz num

    putStrLn (show collatzL)
```
```
apo@gentoo ~/Documents/project/make/haskell/collatz/my-project $ stack exec my-project-exe
Input any number.
24
[24,12,6,3,10,5,16,8,4,2,1]
```
Haskell教養としての関数型プログラミング p252  
# 素因数分解
./app/Main.hs  

```
module Main where

popFactor :: Integer -> Maybe (Integer, Integer)
popFactor n | n < 2 = Nothing
popFactor n = Just (f, n `div` f)
    where f = head $ filter ((== 0) . (n `mod`)) [2..]

factorization :: Integer -> [Integer]
factorization n = case popFactor n of
    Nothing -> []
    Just (f, n') -> f : factorization n'

main :: IO ()
main = do

    putStrLn ("Input any number.")
    numS <- getLine
    let num = read numS :: Integer
    let factorizationL = factorization num

    putStrLn (show factorizationL)
```

```
apo@gentoo ~/Documents/project/make/haskell/factorization/my-project $ stack exec my-project-exe
Input any number.
1001
[7,11,13]
```
Haskell教養としての関数型プログラミング p255  
# IntとIntegerの変換

```
module Main where

a :: Int
a = 1

b :: Integer
b = 2

main :: IO ()
main = do

    let c = a + fromIntegral b
    let d = (fromIntegral a) + b

    putStrLn ("a=" ++ show a)
    putStrLn ("b=" ++ show b)
    putStrLn ("c=" ++ show c)
    putStrLn ("d=" ++ show d)
```

```
apo@larry ~/doc/project/make/haskell/Int_Integer/my-project $ stack exec my-project-exe
a=1
b=2
c=3
d=3
```
[http://www.shido.info/hs/haskell4.html](http://www.shido.info/hs/haskell4.html)  
# Generating a List

```
module Main where

asc :: Int -> Int -> [Int]
asc n m
    | m < n = []
    | m == n = [m]
    | m > n = n : asc (n+1) m

main :: IO ()
main = do

    let a = asc 1 3
    putStrLn(show a)
```

```
apo@larry ~/doc/project/make/haskell/asc/my-project $ stack exec my-project-exe
[1,2,3]
```
[https://www.youtube.com/watch?v=AN-P1-IvsKQ&list=PLe7Ei6viL6jGp1Rfu0dil1JH1SHk9bgDV&index=4](https://www.youtube.com/watch?v=AN-P1-IvsKQ&list=PLe7Ei6viL6jGp1Rfu0dil1JH1SHk9bgDV&index=4)  
# Tuples

```
module Main where

addTuples :: [(Int, Int)] -> [Int]
addTuples xs = [ x+y | (x,y) <- xs ]

main :: IO ()
main = do

    let a = addTuples [(1,2), (2,3), (100,100)]

    putStrLn (show a)
```

```
apo@larry ~/doc/project/make/haskell/tuples/my-project $ stack exec my-project-exe
[3,5,200]
```
[https://www.youtube.com/watch?v=AN-P1-IvsKQ&list=PLe7Ei6viL6jGp1Rfu0dil1JH1SHk9bgDV&index=4](https://www.youtube.com/watch?v=AN-P1-IvsKQ&list=PLe7Ei6viL6jGp1Rfu0dil1JH1SHk9bgDV&index=4)  
# sequence
サイコロ2個を振ったときの組み合わせを、sequence関数と自作関数で表示。  
  
参考  
[https://youtube.com/watch?v=ofUAlkYHFsI](https://youtube.com/watch?v=ofUAlkYHFsI)  
[https://qiita.com/aosho235/items/65fba14703471947bb53](https://qiita.com/aosho235/items/65fba14703471947bb53)  

```
module Main where

main :: IO ()
main = do

    let a = sequence [[1..6], [1..6]]
    putStrLn (show a)

    let b = [(x, y) | x <- [1..6], y <- [1..6]]
    putStrLn (show b)
```

```
apo@larry ~/doc/project/make/haskell/sequence/my-project $ stack exec my-project-exe
[[1,1],[1,2],[1,3],[1,4],[1,5],[1,6],[2,1],[2,2],[2,3],[2,4],[2,5],[2,6],[3,1],[3,2],[3,3],[3,4],[3,5],[3,6],[4,1],[4,2],[4,3],[4,4],[4,5],[4,6],[5,1],[5,2],[5,3],[5,4],[5,5],[5,6],[6,1],[6,2],[6,3],[6,4],[6,5],[6,6]]
[(1,1),(1,2),(1,3),(1,4),(1,5),(1,6),(2,1),(2,2),(2,3),(2,4),(2,5),(2,6),(3,1),(3,2),(3,3),(3,4),(3,5),(3,6),(4,1),(4,2),(4,3),(4,4),(4,5),(4,6),(5,1),(5,2),(5,3),(5,4),(5,5),(5,6),(6,1),(6,2),(6,3),(6,4),(6,5),(6,6)]
```
# zipWith

```
module Main where

import Lib

main :: IO ()
main = do
    someFunc

    let a = zipWith max [1,5,3,7] [4,2,8,0]

    putStrLn ("let a = zipWith max [1,5,3,7] [4,2,8,0] = " ++ show a)
```
```
apo@gentoo ~/Documents/project/make/haskell/zipWith/my-project $ stack exec my-project-exe
someFunc
let a = zipWith max [1,5,3,7] [4,2,8,0] = [4,5,8,7]
```
[https://53ningen.com/learning-haskell/](https://53ningen.com/learning-haskell/)  
# elem
リストに値が含まれていればtrue
リストに値が含まれていなければfalseを返す。

```
apo@larry ~/doc/project/make/haskell/elem/my-project $ cat ./app/Main.hs
module Main where

main :: IO ()
main = do

    let a = [3,6,2,7,5,8]

    let b = 5 `elem` a
    putStrLn (show b)

    let c = 9 `elem` a
    putStrLn (show c)
apo@larry ~/doc/project/make/haskell/elem/my-project $ stack exec my-project-exe
True
False
```
[https://qiita.com/androhi/items/a94ab53e158bbe4cbc54](https://qiita.com/androhi/items/a94ab53e158bbe4cbc54)  
# stack.yaml
## extra-deps
moduleのバージョン指定
stack.yaml

```
extra-deps: 
- wx-0.92.2.0
- wxc-0.92.2.0
- wxcore-0.92.2.0
- wxdirect-0.92.2.0
```
[https://qiita.com/sky_y/items/6712c3609a8e690e0dd3](https://qiita.com/sky_y/items/6712c3609a8e690e0dd3)  
[https://23prime.hatenablog.com/entry/2018/11/27/092959](https://23prime.hatenablog.com/entry/2018/11/27/092959)  
[https://haskell.e-bigmoon.com/stack/intro/extra-deps.html](https://haskell.e-bigmoon.com/stack/intro/extra-deps.html)  
  
リゾルバーは、特定のバージョンのパッケージのキュレートされたセットを指定します（標準のものはstackage.orgにリストされています）。選択したリゾルバーにパッケージの依存関係がない場合は、 stack.yaml の extra-deps フィールドにリストする必要があります。  
[https://www.366service.com/jp/qa/a60ca9d10ee75253bc4b16751b7377a1](https://www.366service.com/jp/qa/a60ca9d10ee75253bc4b16751b7377a1)  
# バージョンが近いパッケージをインストールする
/home/apo/.stack/config.yaml  

```
[apo@arch my-project]$ cat /home/apo/.stack/config.yaml

templates:
  params:

allow-newer: true
```
# 直角三角形を見つける
「すごいHaskellたのしく学ぼう!」p21  
Main.hs  

```
module Main where

main :: IO ()
main = do
    let rightTriangles' = [(a,b,c) | c <- [1..10], a <- [1..c], b <- [1..a], 
                                     a^2 + b^2 == c^2, a+b+c == 24]
    print rightTriangles'
```
# GUI
別リポジトリに記載  
[Haskell_GUI](https://bitbucket.org/ringo-apo/memo_programming/src/master/Haskell_GUI.md)  
# オセロ
[https://suzuki-shin.github.io/reversi-haskell/](https://suzuki-shin.github.io/reversi-haskell/)  
[https://github.com/ringo-apo/reversi-haskell](https://github.com/ringo-apo/reversi-haskell)  
# テトリス
[https://qiita.com/chupaaaaaaan/items/0a72dd207e379f468303](https://qiita.com/chupaaaaaaan/items/0a72dd207e379f468303)  
[https://github.com/chupaaaaaaan/tetris-with-haskell](https://github.com/chupaaaaaaan/tetris-with-haskell)  
# do記法の中でletやlet ... inを使ったサンプル

```
main = do
  -- let ... in を使った場合
  let f :: String -> IO ()
      f = putStrLn
   in f "f"
  -- ただの let を使った場合（こっちの方が大抵おすすめ！）
  let g :: String -> IO ()
      g = putStrLn
  g "g"
```
# すごいHな本　Heathrow to London
[https://github.com/ringo-apo/hs_london](https://github.com/ringo-apo/hs_london)  
./app/Main.hs  

```
module Main where

import Lib
import Data.List

data Node = Node Road (Maybe Road)  
data Road = Road Int Node  

data Section = Section { getA :: Int, getB :: Int, getC :: Int } deriving (Show)  
type RoadSystem = [Section]  

--heathrowToLondon :: RoadSystem  
--heathrowToLondon = [Section 50 10 30, Section 5 90 20, Section 40 2 25, Section 10 8 0]  

data Label = A | B | C deriving (Show)  
type Path = [(Label, Int)]  

roadStep :: (Path, Path) -> Section -> (Path, Path)
roadStep (pathA, pathB) (Section a b c) =
    let timeA = sum (map snd pathA)
        timeB = sum (map snd pathB)
        forwardTimeToA = timeA + a
        crossTimeToA = timeB + b + c
        forwardTimeToB = timeB + b
        crossTimeToB = timeA + a + c
        newPathToA = if forwardTimeToA <= crossTimeToA
                         then (A, a):pathA
                         else (C, c):(B, b):pathB
        newPathToB = if forwardTimeToB <= crossTimeToB
                         then (B, b):pathB
                         else (C, c):(A, a):pathA
    in (newPathToA, newPathToB)

optimalPath :: RoadSystem -> Path
optimalPath roadSystem =
    let (bestAPath, bestBPath) = foldl roadStep ([], []) roadSystem
    in if sum (map snd bestAPath) <= sum (map snd bestBPath)
           then reverse bestAPath
           else reverse bestBPath

groupsOf :: Int -> [a] -> [[a]]
groupsOf 0 _ = undefined
groupsOf _ [] = []
groupsOf n xs = take n xs : groupsOf n (drop n xs)

main :: IO ()
main = do
    contents <- getContents
    let threes = groupsOf 3 (map read $ lines contents)
        roadSystem = map (\[a,b,c] -> Section a b c) threes
        path = optimalPath roadSystem
        pathString = concat $ map (show . fst) path
        pathTime = sum $ map snd path
    putStrLn $ "The best path to take is: " ++ pathString
    putStrLn $ "Time taken: " ++ show pathTime
```
./paths.txt  

```
50
10
30
5
90
20
40
2
25
10
8
0
```
実行  

```
stack exec my-project-exe < paths.txt
```
