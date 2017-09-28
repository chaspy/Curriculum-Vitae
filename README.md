# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|takeshe12|
|Blog|[ツナワタリマイライフ](http://take-she12.hatenablog.com/)|
|Twitter|[@take_she12](https://twitter.com/take_she12)|
|Speakerdeck|[takeshe12](https://speakerdeck.com/takeshe12)|

## スキル

### 言語

- プログラミング言語
  - Ruby
  - Python
  - Go
  - shell

- 日本語
  - ネイティブ
- 英語
  - 検索結果を調べながら読むことができる
  - gitのREADMEをかける

### 資格

|資格名|取得年月|
|---|-----|
|情報セキュリティスペシャリスト|2015-6|
|ネットワークスペシャリスト|2014-12|

## 強み

- OSS導入/活用推進
  - phpipam(IPアドレス管理)
  - knowledge(ノウハウ共有)
  - Gitlab(ソースコード管理システム)
  - mattermost(slack互換のチャット)
  - redmine(チケット管理システム)
  - hubot(bot基盤)
  - minio(S3互換オブジェクトストレージ)
- 構築自動化による属人化の排除
  - ansible
  - docker
- インフラのコード化およびテスト
  - ansible
  - capistrano
  - terraform
  - serverspec
- CI/CDプロセスの導入
  - gitlab-ci
  - circleci
  - jenkins
- パブリック/プライベートクラウドの運用経験
  - OpenStack
  - VMware
  - KVM
- チーム開発推進
  - カンバン
  - chatops

## やったことはないが興味があるもの
* SRE(Site Reliability Engineering)
* パブリッククラウドでのシステム構築・導入・運用
* モニタリングと可視化
* データベースパフォーマンスチューニング

## 職務経歴

### 2014/04 - : 某SIer

職務: ソフトウェアエンジニア

#### プライベートクラウド向け管理製品の開発

* Ruby on Railsによるプライベートクラウド向け管理製品の開発を行う
* 管理対象のハードウェアを制御するため、サーバ・ネットワーク・ストレージといったインフラの基礎技術を学ぶ
* チームで使うクラウド環境(VMware)の管理者を担当し、開発者のテスト環境の運用・トラブル対応を行う

#### OpenStackによるパブリッククラウド開発/保守

* IaaS(+α)のnova,cinder,glance,keystone,heatを担当
* 障害対応を行い、バグ修正、トラブル対応を担当
* 開発環境改善としてインフラやconfigの自動テストに取り組む

#### 開発工程へのCI/CDプロセス導入

* リーダーを担当
* デリバリ(リリース)方式をrpmパッケージへ変更
* ソースコード管理方式を改善し、ブランチ運用、テストの実施、テスト環境への適用のフローを整備
* UnitTest/IntegrationTestを導入し、CI環境を構築、開発者の導入支援を実施。(Jenkins/Gitlab-CI/Docker)

#### クラウドにおけるデータベースのオンラインアップグレード

* MariaDBのバージョンを5.5系から10.2系にアップグレード
* サービス無停止で実施
* ほとんどの作業をscript化、リリース担当の負荷軽減
