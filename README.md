# My Resume

## Basic Infomation

|key|value|
|---|-----|
|Name|k-kurikuri|
|Twitter|[@k_kurikuri2](https://twitter.com/k_kurikuri2)|
|Qiita|[@k-kurikuri](https://qiita.com/k-kurikuri)|
|Speakerdeck|[@k-kurikuri](https://speakerdeck.com/k_kurikuri)|
|Hatena Blog|[@k-kurikuri](http://k-kurikuri.hatenadiary.jp)|

## Skills
### Language
- Programming
  - PHP (v5.3 - v7.1)
  - JavaScript (ES6)
  - TypeScript (v2.6 - v3.4)
  - python (v2.7 - v3.5)
  - Java (v5.0 -   v7.0)
  - C# (v6.0)
  - Go (v1.9 - v1.12)

- Japanese
  - ネイティブ

- English
  - 公式ドキュメントやREADME、技術サイトなど、翻訳ツールを使用しながら読むことができる

### Framework
- Laravel (v4.2 - v5.5)
- Symfony2
- PlayFramework for Java (v2.2)
- Struts (v1.2)
- .NetFramework (v4.6)
- Android (v2.3)
- Revel (v0.17)

### Testing Framework
- PHPUnit
- JUnit
- goconvey

### Package Manager
- Composer
- Homebrew
- yum
- pip, numpy
- npm, yarn
- Bundler
- dep
- glide
- vgo

### OS
- MacOSX
- CentOS
- Ubuntu
- Alpine Linux
- Windows7

### Middleware
- Apache Http Server v2.2
- NGINX v1.8
- MYSQL 5 - 5.7
- Oracle 10g
- Redis v4
- Memcached v1.4
- MongodB
- td-agent (Fluentd)

### Deploy Tool
- Capistrano3.x

### Infrastructure As Code
- Terraform
- Ansible

### Monitoring Tool
- NewRelic
- Cacti
- Munin
- Sumo Logic
- Grafana
- DataDog
- Cloud Watch
- Stackdriver Logging

### Editor
- IntelliJ
- Vim
- Atom
- VSCode

### Task Manager
- JIRA
- Redmine
- Backlog
- Trello
- ZenHub

### VCS
- Github
- Bitbucket
- Gitlab

### Cloud Service
- Amazon Web Service
  - EC2
  - ECS
  - ElasticBeanstalk
  - GameLift
  - Elasticache
  - Elasticsearch
  - ELB
  - Lambda (Node.js, Go)
- Google Cloud Platform
  - Compute Engine
  - App Engine
  - Cloud Storage
  - Cloud SQL
  - Kubernetes Engine
  - Cloud Function
- Heroku

### CI
- Jenkins
- CircleCI

### Chat Tool
- Slack
- ChatWork

### Other Tool
- Docker
- Vagrant (VirtualBox)
- Selenium
- Phantomjs
- Gatling
- JMeter
- Gaurun
- etc...

### Developer License
- Oracle Certified Professional, Java SE 5 Programmer
- Oracle Master Bronze 10g
- ITパスポート
- Excel VBA Expert
- Access VBA Expert

## Job Career

### 2019/02〜2019/06: eKYC案件
#### 職務
バックエンドエンジニア (準委任契約)

#### 開発規模
チーム規模15名
- リードエンジニア1名
- バックエンドエンジニア5名(フロントエンド兼任4名)
- フロントエンドエンジニア2名
- ディレクター2名
- QA2名
- デザイナー1名

#### 開発手法
スクラム開発

#### 役割
Goを使ったAPI開発とVue.js+TypeScriptを使ったフロント開発

#### 使用技術の詳細
バックエンドの技術詳細は次の通り

- Go(v1.12)
  - labstack/echo
  - golang-migrate/migrate
  - golang/dep
  - pkg/errors
  - Masterminds/squirrel
  - stretchr/testify/assert
  - dgrijalva/jwt-go
- MySQL5.7
- Docker
- docker-compose
- Terraform

AWS, 各Saasの用途は次の通りです

- ECR
- ECS fargate
- Cloud Watch
- SQS
- APIGateway
- S3
- CloudFront
- Aurora
- NLB
- CircleCI
  - ユニットテスト実行、ビルド、コードフォーマットチェックのCIとしての使用
- Github

フロントエンド
- TypeScript v3.4
- Vue.js v2.5
- Vuex
- vue-class-component
- vue-property-decorator
- vue-router
- buefy
- yarn

AWSを使用していたがインフラ構築を外注していたのと、案件の特性もあり自分で触る機会はありませんでした。

開発中盤にアサインされたため、すでに技術選定やアーキテクチャの採用は決まっていました。

eKYC導入事業者向けの顧客管理Webシステムというの作成であったため、必要なUIとAPI開発が業務の大半をしめていました。
必要なテーブル設計もほとんど完了しており、カラム追加や一部新規テーブルを設計する形でした。
フロントエンドは凝ったUIは得意ではないため担当はしておらず、比較的シンプルなUIのタスクを担当しました。

新規リリースに向けたタスクやバグチケットをフロント、バックエンド多数消化した。
他のメンバーが実装した箇所もコードリーティング、必要に応じて口頭でヒアリングし柔軟に対応。
バグチケットを担当する事でアプリケーションの機能を理解する事もでき徐々にスピードが出てきたと思います。

#### 負荷テスト
JMeterを使用した負荷テストシナリオを作成しました。業務管理ツールという事で大きな負荷のかかるシナリオではなかったためクライアント・サーバは構築せず、ローカルマシンから実行をおこなった。JMeterも初めての経験だったが枯れたツールであるためドキュメントを見ながら、2,3日で機能の多く理解し設定ができた。
テストデータ作成用のsqlも用意し、GoのCLIから簡単にまとめて作成できるようにし、今後も容易に負荷テストが行える環境作りを意識しました。

#### 実績
- 新規API、フロント開発
- eKYC業務の理解
- JMeterを使用した負荷テストシナリオ作成、テストデータ作成ツール
- リリース前の機能開発、バグチケット消化、負荷テストの準備など柔軟に対応
- SlackにGithubアプリを入れて、プルリクエスト、レビューコメントなど通知されるよう改善
- 開発環境のみGoの自動ビルドが出来るようravityblast/freshを導入

### 2018/11〜2019/01: フリマアプリ案件
#### 職務
バックエンドエンジニア (準委任契約)

#### 開発規模
チーム規模8名
- エンジニアマネージャー1名
- リードエンジニア1名
- バックエンドエンジニア6名

#### 開発手法
スクラム開発

#### 役割
既存PHPシステムのマイクロサービス化に伴い、バックエンドエンジニアのメンバーとしてアサイン(準委任契約)

#### 使用技術の詳細
バックエンドの技術詳細は次の通り

- Go(v1.11)
  - dep
- MySQL5.6, 5.7
- Docker (latest version)
- Kubernetes (latest version)
- Terraform (latest version)
- Telepresence  (latest version)

GCP, 各Saasの用途は次の通りです
- GKE
  - マイクロサービス
- CloudPub/Sub
  - イベントメッセージング
- StackDriver
  - 各クラウドサービスのログ集約
- PagerDuty
- DataDog
- CircleCI
- Github
- Codecov

インフラはSREチームが管理しておりサービスチームはTerraformに修正をかけてプルリクエストを送るフローとなっています。
プルリクエストが承認されればCIを通してGCP環境へ反映するという形です。

Goでの開発は標準パッケージを使用したスタイルを採用していました。
loggerやmiddlewareはライブラリに依存していましたがgRPCを使用していた事もありhttpやtestingなど標準パッケージを使用し開発していました。

#### マイクロサービス間で使用する共通ライブラリの修正
各マイクロサービスでは直接DBを操作できるないよう[腐敗防止層](https://docs.microsoft.com/ja-jp/azure/architecture/patterns/anti-corruption-layer)を通してDBにアクセスする形になっていた。
マスターデータの取得は既存のモノリスシステムにAPIが用意されていて、マイクロサービスではそのAPIを呼び出しデータを取得する形になっていました。
そのAPIを呼び出すためのクライアントライブラリが用意されていましたがversionアップされたため、それを各サービスに適応するタスクを担当しました。

#### DAOレイヤーサービスのCRUD機能実装
データベースCRUD操作用のサービス開発を行いました。gRPCのprotoファイルを用意しCRUD操作用のロジックを作成する形だったため特段テクニカルな事はしていません。
Goで実装し、testingパッケージを使用したユニットテスト。テスト環境はDockerコンテナを立ててローカル、CI上で実行する形式でした。
テストカバレッジは8割を基準として、Codecovで結果を確認しレビュー後にマージというフロー。

#### 実績
- マイクロサービスアーキテクチャにおける設計スキル
- Goの標準パッケージを使用した開発スキル
- DAOレイヤーのマイクロサービスの実装
- gRPCを使用した開発フローの理解

### 2018/05〜2018/10: 女性向けライブコマースアプリ案件
#### 職務
バックエンドエンジニア (準委任契約)

#### 開発規模
チーム規模14名
- プロデューサー1名
- デザイナー1名
- リードエンジニア1名
- バックエンドエンジニア5名
- フロントエンジニア6名

#### 開発手法
スクラム開発

#### 役割
バックエンドエンジニアのメンバーとしてアサインしました (準委任契約)

#### 使用技術の詳細
フロントエンドはSwift(iOS)、Kotlin(Android)を使用し、バックエンドはGoを使用した開発環境。
メンバー全員がMacで統一されていたためローカル環境にて開発。管理画面や別のマイクロサービスはDockerイメージからコンテナを作成し、docker-composeで起動しポートフォワードし、マイクロサービス化したコンテナへアクセスする形で開発しています。
確認環境はGCP上に構築し、Github上の特定ブランチにマージされた後にCircleCIから自動テスト後にGKEを自動構築する方法をとっています。

クライアントアプリケーションからはhttp(s)を使用しバックエンドからリソースをjsonフォーマットで受け取る形でのやり取りを行い、
管理画面はSPA(React.js)で実装し、こちらもGoのAPIを通してバックエンドからリソースをjsonフォーマットにて受け取る形でやり取りを行っています。

バックエンドの技術詳細は次の通りです。

- Go(v1.10)
- MYSQL5.7
- Redis
- ElasticSearch
- Package Manegerは[dep](https://github.com/Go/dep)
- ORMは[gocraft/dbr](https://github.com/gocraft/dbr)
- Webフレームワークに[labstack/echo](https://github.com/labstack/echo)
- Migrationに[rubenv/sql-migrate](https://github.com/rubenv/sql-migrate)
- Tesitingフレームワークは[smartystreets/goconvey](https://github.com/smartystreets/goconvey)
- Terraform
- Ansible
- Push通知サーバに[mercari/gaurun](https://github.com/mercari/gaurun)

GCP, 各Saasの用途は次の通りです
- GKE
  - アプリケーションサーバ
  - Push通知サーバ
  - その他のマイクロサービスの用途として
- StackDriver
  - 各クラウドサービスのログ集約
- ElasticCloud
  - アプリケーションからの検索機能の用途として
- GoogleCloudSql
  - プロダクトで扱う必要な情報保存用のRDBMS
- GCE
  - バッチサーバ
  - デプロイサーバ
- GCS
  - 静的リソースの永続ストレージ
- KMS
  - 秘密情報の暗号化
- CloudFunctions
  - GCSへのアップロードをトリガーにした動画ファイルのトランスコード処理として
- Firebase
  - リアルタイムチャット機能
- Akamai
  - 静的リソース用CDN
- CircleCI
  - Githubへpushされた際の自動テスト実行
  - 確認環境であるGKEへのデプロイ&Migration実行
  - Apiaryの作成
  - Coverallsへカバレッジ
- Coveralls
  - テストカバレッジのhtmlによる可視化
- Apiary
  - RestfulAPIのインターフェースドキュメント
- wowza
  - ストリーミングサーバ
- Container Registry
  - Dockerイメージの管理
- Zencoder
  - トランスコードサーバ

私が担当したタスクは次の通りです。

- メルカリ社製のGaurunを使用してのPush通知機能の実装とGKE上にPush通知サーバを構築する
- GCE上でバッチサーバを構築する
- 管理画面でのCRUD機能を、フロントエンド、バックエンド共に作成する
- ポイント機能の実装、マイクロサービスとしてGKEにサーバ構築
- 動画ファイルのトランスコード処理をZencoder、GCS、CloudFunctionsを用いサーバレスで構築

####  Push通知サーバのタスク
Push通知サーバのタスクでは、クライアントからPush通知の許可・不許可を設定するためのAPIの作成と、
Push通知を送るためのCLIを実装と、Push通知サーバの構築を担当しています。

Push通知の設定は、「全体の通知を許可」「Bの通知の許可」「Cの通知の許可」などと、
画面上から各種設定がセグメントごとに別れており、テーブル設計、API設計を行い、設定のON・OFFを行う簡易なAPIを作成しました。
その設定を元にPush通知を送信するためのCLIを作成しました。

Push通知サーバの構築のフローは次のように行いました。

- Gaurunサーバの基本設定をDockerfileで作成
- GCPのRegistryにDockerfileをアップロード
- TerraformからDockerfileをもとにGKEを、指定した設定に従い構築する
- APNs, FCMトークンや設定ファイルの情報はGKEのsecret機能を使い暗号化して保存しており、GKE構築前にコマンドから取得しセットするよう対応
- Gaurunでのエラーログ、アクセスログは標準出力する事でStackDriverにログが流れる仕様のため、そこからGCSにjsonフォーマットでログを保存し永続化する

####  バッチサーバ構築タスク
Push通知を送るためのCLIを作成する必要があり、そのCLIをバッチサーバから実行する必要があったため、バッチサーバの構築タスクも担当しました。

バッチサーバはGCEを使用しTerraformとAnsibleを使用し必要なライブラリのインストールや環境変数のセットなどをPlaybookとして作成。
バッチサーバからDBの接続情報、APNs、FCMのトークンを取得する必要があり、GKEのsecretに保存されたデータはkubectlコマンドを通して実行。

バッチサーバではスケジューラとしてcronをセットする形式をとり、Goビルドしたバイナリをバッチサーバにデプロイし、cron登録するPlaybookも作成。

本番環境で現在稼働しており問題なく動作している。ただ、ユーザー数がまだ少ないためスケーリングの検証は出来ていない。

#### 動画ファイルのトランスコード処理タスク
商品の紹介動画がmp3で作成され納品されるため、それをHLSへと変換するサーバとしてCloudFunctions(Node.js version8)を使用しました。HLSへのトランスコードはZencoderというSaasを使用。処理の流れとしてはGCSへmp3がアップロードされるとアップロードイベントをトリガーとしてCloudFunctionsを起動する。CloudFunctionsからZencoderのAPIをリクエストし、ZencoderはHLSフォーマットに変換し再びGCSへと保存する。ZencoderのAPIが成功すればCloudFunctionsからSlackへと通知を行うという流れです。
これによりファイルアップロード時だけ動画の変換処理を実行する事ができ、サーバレスのメリットを活かした。

#### 実績
- GCPのサービスを組み合わせて、Push通知サーバを構築し、Push通知の送信機能を実装した
- Docker, Terraform, Ansibleを使用したインフラ構築を行った
- React.jsを使用しSPAで管理画面を作成する知見
- ライブコマースサービスの新規開発から本番リリース、運用フェーズと一環して携わったことによる知見

### 2018/02〜2018/04: ソーシャルゲーム案件
#### 職務
バックエンドエンジニア (準委任契約)

#### プロジェクト
有名IPパズルゲーム

#### 開発規模
チーム規模30名
- プロデューサー1名
- ディレクター5名
- デザイナー3名
- 外注管理、シナリオ管理3名
- リードエンジニア1名
- バックエンドエンジニア4名 (内、外部開発会社2名)
- フロントエンジニア4名 (内、外部開発会社2名)

#### 開発手法
スクラム開発の手法を取り入れた、ウォーターフォール開発

#### 役割
アプリリリース2ヶ月前に、バックエンジニアメンバーとしてアサイン。(準委任契約)
リリース直前という事もあり、バックエンドメインに溢れたタスクを担当

#### 使用技術の詳細
プロダクトはAppStore, GooglePlay向けのIPを利用したパズルゲーム。
バックエンドはApache、PHP7、MYSQL5.6、MemcachedをAWS環境で構築し利用し、フロントエンドはUnityを使用したソーシャルゲームの開発では標準的な環境であった。
開発環境はAWS上のEC2(AmazonLinux)上にWeb、DBと構築されていて、開発者はその環境にsshして作業するというスタイル。ステージング・本番環境ではDBはAurora、MemcachedはElasticacheを利用。

私が担当した主なタスクは次の通りです

- 開発・ステージング・本番などの環境毎のDB差分を管理画面上に出力する機能
- DB-Migration機能の作成
- 開発環境EC2のAMI、スナップショットを自動で保存する
- リリース後の障害対応
  - APCuキャッシュの容量が閾値を超えたため、原因となる箇所の調査と修正対応

#### 開発環境毎のDB差分表示タスク
リリース用、リリース後の機能追加用と開発環境が分かれていて、私がアサインされた頃はデータベースの更新差分を手動で行っており、操作ミスによるDBが破壊される事が度々行っていた。
そこでDBの差分を管理画面に出力し、その出力をコピーペーストするだけで環境が揃う仕組みを作成しました。

#### DB Migrationタスク
Migration機能はOSSを利用してはどうかと提案したが、sqlファイル形式で管理しsqlファイル内にはスキーマだけではなく、マスターデータのinsertやupdateも入れて管理を行いたいという事であった。

実行したsqlファイル名をDBに保存し、その内容とmigration用ディレクトリに存在するファイル一覧を比較する事で、実行の可否を判別するよう実装しました。ロールバック機能は不要という事で実装はしていません。

#### 開発環境EC2のAMI、スナップショットを自動保存するタスク
開発環境のEC2のAMIを日毎にバックアップを取れるようにしてほしいという依頼があり、
CloudWatchのスケッジューライベントをAWS Lambda(Node.js)に通知し、
Lamdbaから対象EC2インスタンスのAMI、スナップショットを日毎に作成するよう機能実装。
また、N日前のAMI、スナップショットは削除するようにも実装し、実行ログはSlackのIncomingWebHookで通知する対応。

AMI、スナップショットには「タグ」をつける事が出来るため、対象インスタンス名とLamdbaから作成されたというタグをつけ、N日前判定には、ファイル名に日時を含めることで解決した。

Lambdaを実装する際は、serverlessコマンドをローカルマシンにインストールし、ローカル開発を可能とし、ローカルシミュレートしてからAWS環境でテストを行う形式で開発していました。

#### サービスリリース後に発生したAPCu障害対応
サービスリリース直後、APIサーバのAPCuキャッシュが溢れてしまう問題が発生した。
APCuは閾値を超えると、キャッシュクリアを行う挙動になっており、その際にPHPのプロセスをブロックする事からAPIサーバが応答せずゲームがプレイできなくなる問題が発生。APCuをモニタリングするWebUIがあるため内容を調査した所、マスターデータをキャッシュする際にwhere inでのキャッシュを行っていたため、ヒット率が悪い無駄なデータが作成されてる事を発見した。

where inを実行しているSQLをすべて、DBから直接参照する対応を行い、その結果APUcの肥大化は落ち着き、ゲームプレイも問題なくプレイできる改善を行った。

#### 実績
- 簡易的なMigration機能の実装
- AWS Lambda + CloudWatchによるスケジューラー処理の知見
- 本番リリース後のAPCキャッシュ肥大化の対応
  - リリース後、数時間の内に調査、原因の発見、対応、テスト、デプロイまでのスピード感
- Capistranoの修正対応、ステージング環境でのapache.confのsymlinkの設定ミス、開発環境のfluentd更新、Unity(C#)の実装ミスによる修正対応など、幅広い対応力

### 2015/10〜2018/01: 株式会社DMM.comラボ
#### 職務
バックエンドエンジニア (正社員)

#### プロジェクト
部内で使用するPHPライブラリの基盤開発、R&Dプロジェクト

#### 開発規模
チーム規模約8名

- リードエンジニア1名
- バックエンドエンジニア5名 (フロント兼任2名)

#### 開発手法
スクラム開発の手法を取り入れた、ウォーターフォール開発

#### 役割
- 開発メンバーとしてプロジェクト共通のバックエンド基盤機能開発を担当
- ゲーム内チャットやプレイヤー間バトルなど、リアルタイムシステムの開発を担当

#### 使用技術の詳細
部内で共通して使用する基盤開発として、PHPを使用してComposerプラグインの開発を行いました。
基盤機能はComposerプラグインのSatisを使用し、Packagistのミラーリングを社内サーバに用意して、
そこからプロジェクトチームは必要なコンポーネントを取り込む方針で開発していました。
機能開発では要求を洗い出す所から始まり、設計、実装、ユニットテスト、ドキュメント作成、レビュー、リリースというフローを採用していました。

CIにはJenkinsを使用し、リモートリポジトリへのマージ後のユニットテスト実行と、
phpdocsドキュメントの自動生成、コードフォーマットチェックを行いシステムの品質を維持に努めていました。

私は機能開発だけではなく、部内で採用されたLaravelフレームワークの基礎学習用チュートリアルも作成しました。
そのチュートリアルは中途社員、新入社員の学習コンテンツとして採用されています。

ゲーム機能のライブラリ化だけではなく、部内の要求としてリアルタイム通信もフレームワーク化するという話が上がり、
リアルタイム通信の技術やクラウドサービスの調査を行うタスクをエンジニア4名で始めました。

リアルタイム通信サービスの調査では、Photon Cloud、Monobit、AmazonGameLiftを対象とし、
クラウドではなくNode.jsを使用した内製開発した場合の優位性などを調査しました。

調査した結果、自社でNode.jsを使用したリアルアイム通信フレームワーク開発を行う事になり、
システム設計を行い、検証環境としてAmazonWebServiceを使用し、アーキテクチャの妥当性などを確認しつつ開発を進めました。
開発のフェーズをいくつかに分け、調査・検証、αフェーズ、βフェーズと段階的に開発を進める形式でした。

調査・検証フェーズでは、サーバー動作やデプロイツールの確認をするため、Elastic Beanstalk、EC2、Elasticache、ELBなどを使用し、
Node.jsで簡易的なチャットシステムを構築しました。

αフェーズでは具体的な設計と実装を開始し、Node.js、TypeScript、いくつかのnpmモジュールを使用して、
フレームワーク開発を現在しています。

#### 実績
- プルリクエスト時にコーディング規約に対する指摘の多さから、コードフォーマッタを導入しコードレビューの工数を減らしました
- メンバーのプルリクエストの粒度が大きく、手直しが多く発生していたため、
テーブル設計、モデル作成、API作成など粒度を小さくしてプルリクエストを提案し、リジェクト時の手直しの頻度を少なくしました
- 過去に自身がIT教育業界にいたため、新入社員、中途社員向けのLaravelチュートリアルドキュメントを作成しました
- Node.jsとTypeScriptでWebsocketを使用したリアルタイム通信システムの開発

#### プロジェクト
男性向けスマホ・ブラウザゲーム開発プロジェクト

#### 開発規模
チーム規模約20名
  - プロデューサー2名
  - ディレクター3名
  - デザイナー4名
  - 外注管理、シナリオ管理3名
  - フロントエンジニア5名
  - バックエンドエンジニア4名
  - リードエンジニア1名

#### 開発手法
スクラム開発の手法を取り入れた、ウォーターフォール開発

#### 役割
開発メンバーとして、バックエンド、フロントエンド開発を兼任しました。

#### 使用技術の詳細
サーバーサイドはLaravel5.1, フロントエンドはUnity5.3を使用。データベースはMYSQL5.6を使用しシャーディングを行いました。
キャッシュサーバにはRedisを採用。マスターデータはjsonスキーマで管理し、クライアントサイドでもマスターデータをAssetで管理するため
jsonスキーマから自動でUnity用C#クラスへと変換する機能を使用しました。
マスターデータをDB定義ではなく、jsonスキーマが採用されたのはクライアントサイドエンジニアも修正を行えるというのが理由です。

RestfulAPIから返されるjsonレスポンスはSwaggerなどの自動ドキュメント生成ツールを使用するのではなく、Google Spread Sheetで管理をしていました。

UnityではUnityEditorを拡張し、Google Spread SheetからLocalize用のファイルを生成するなど、部内で用意された各プロジェクト共通の機能を使用していました。
部内共通の機能は他にも、クライアントサイド開発でMVCモデルを使用できるようにController, Model, SceneやWWWを管理するManagerなどが用意されて、
その機能を継承することで統一して実装できるようになっていました。

#### 実績
- ゲーム内アイテムを交換する機能、プレイヤー間同士のバトル機能、イベントの機能をフロントエンド、バックエンド共に担当し、
DB設計、API設計、実装、ディレクター・デザイナーとの折衝など統括して担当しました。
- フロントエンジニアへのGit教育
- プロジェクトとは関係ないですが、新卒向け会社説明会のエンジニア担当として説明を行いました

#### プロジェクト
乙女ゲーム開発プロジェクト

#### 開発規模
- チーム規模約20名
  - プロデューサー1名
  - ディレクター3名
  - プロジェクトマネージャー1名
  - デザイナー3名
  - フロントエンジニア9名
  - バックエンドエンジニア4名
  - リードエンジニア1名

#### 開発手法
スクラム開発の手法を取り入れた、ウォーターフォール開発

#### 役割
リードエンジニアとしてバックエンドの設計、開発ルールの作成(設計方針、ドキュメント作成、レビュー指針など)、開発ツール選定、実装、テスト、チーム内の調整を担当しました。
実装だけではなく、開発の進め方、タスク管理の方法、ディレクターなど他職種との調整、フロントエンジニアとのAPI設計すり合わせ、
新規アサインメンバーへの教育担当など、チーム開発に必要なコミュニケーションの仲介をするなど様々な役割を担いました。

#### 使用技術の詳細
タスク管理はJIRA、ドキュメント管理はConfluence、VCSはBitbucketを使用していました。
サーバーサイドはLaravel5.1を使用し、部署内で初めてLaravelを使用した本番リリースを行いました。
scala製の負荷テストツールgatlingの使用や、ruby製のデプロイツールのCapistranoを使用するなどPHPに拘りなく使用。
インフラ構成は、webサーバにnginx, phpモジュールはphp-fpm、マスターデータのキャッシュはmemcachedを使用し、
セッションやユーザーに起因したキャッシュはRedisを使用。RDBMSにMYSQL。シャーディングを行っておらず複数のDBを垂直に分割して管理していました。
監視ツールとしてcacti、newRelicを使用。デプロイツールはCapistrano3。
負荷テストではGatlingを使用。ログサーバにはfluentdを使用。ビルド、デプロイタスクなどはJenkinsを使用していました。

プロジェクトは、ブラウザ, GooglePlay, iTunesStore向けのゲームを開発し、フロントエンドにcocos2d-js、サーバーサイドにLaravelを採用。
サーバーサイドはテーブル設計、API設計、実装、ユニットテストとフェーズを分けて、開発に取り組むフローを採用していました。

テストを書くために工数をたくさん使うような事がないよう、カバレッジは意識せず、
修正時に影響範囲の広い箇所を中心にテストコードを記述していました。テストプログラムとしては単体テストが多かったです。
それにより回帰テストの自動化、手作業によるデバッグ工数を減らすことが出来たと思います。

画像リソースにはNginxのセキュアリンクを使用し、復号化用のハッシュ値なしではクライアントから直接参照できないよう対応していました。

#### 実績
- 大きなバグもなくDMM, GooglePlay, iTunesStoreと3プラットフォーム同時に本番リリースをしました
- 部署内の標準フレームワークとしてLaravelが採用されたため、リリース後のノウハウ共有勉強会開催を行いました
- 初期段階からサービスの設計に携わり、本番リリース後、運用まで一貫して担当しました (運用は1.5ヶ月程度で別チームに異動)

### 2012/07〜2015/09: 株式会社Altplus
#### 職務
バックエンドエンジニア (正社員)

### 2008/12〜2012/06: 株式会社ケンソフト
#### 職務
パソコンスクールインストラクター (正社員)
