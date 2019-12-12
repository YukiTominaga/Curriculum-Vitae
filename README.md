# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|富永 裕貴 (Yuki Tominaga)|
|Blog|[apps-gcp](https://www.apps-gcp.com/author/tominaga/)|

## 資格
- Google Certified Professional Cloud Architect (2017/12 ~)
- Google Certified Professional Data Engineer   (2018/01 ~)
- Google Certified Professional Cloud Developer (2019/01 ~) 
- Google Certified Associate Cloud Engineer     (2018/08 ~)
- Certified Kubernetes Application Developer    (2019/03 ~)
- Google Cloud Authorized Trainer               (2018/05 ~)

## スキル
### プログラミング言語

- TypeScript/JavaScript(他人のコードをレビューできる)
- Go(業務ロジックを独力で実装できる)
- Java(主にApache Beamで使用する程度)
- Python(できればやりたくない)
- PHP(経験2年弱)

### その他

- Google Cloud Platform
- Kubernetes
- Istio
- Helm
- Docker
- Knative
- Terraform
- Pulumi
- Prometheus(PSQLチョット書ける)
- Grafana(Prometheusのメトリクスを可視化するためにちょっとだけ使用)
- Datadog(1環境の監視をやったことがある程度)

## 言語

- 日本語
  - ネイティブ
- 英語
  - 技術文書のReading
  - 英語サポート窓口への英語での問い合わせ(中学生みたいな文章で訊きたいことを伝えられる、それでも過去に困ったことがないので、英語圏の人は優しい)

## 強み

- Google Cloud Authorized Trainer
- FFXIV 7500時間以上プレイ

## やったことはないが興味があるもの

- 英語のSpeaking & Listening(2023年くらいまでに喋れるようになりたい)
- Job実行基盤としてのspinnaker
- 大規模トラフィックへのクラウド技術の適用

## 職務経歴

### 2017/11 - 現在 : クラウドエース株式会社

職務: Lead Engineer

#### Cloud Speech to Textを用いた日報の音声入力

- NodeJS
- Angular
- Kubernetes

#### [Schoo](https://schoo.jp/class/4923)に出演

#### KubernetesにデプロイしたDBへの負荷試験検証

- Cassandra
- Redis
- Kuberentes

#### 外部API利用による手書き文字認識Webアプリケーション開発

- Angular

#### Cloud Speech to Textを利用したコールセンター向け通話音声の文字化アプリケーション

- Python
- Angular
- Firebase

#### 建設現場で利用する出退勤アプリケーション

- Kubernetes
- Angular

#### 大手ゲーム会社への半常駐

- Terraform

#### DRを考慮した金融系システム

- Kubernetes
- Istio
- Helm
- Terraform
- helmfile

#### Google Cloud Platform 認定トレーナー業務

- [Architecting](https://www.coursera.org/specializations/gcp-architecture)
- [Data Engineering](https://www.coursera.org/programs/google-cloud-authorized-trainer-program-ngnti?collectionId=FTUIQ&productId=D6Ap6_7hEeaRogry0hUlXg&productType=s12n&showMiniModal=true)
- [Kubernetes](https://www.coursera.org/learn/google-kubernetes-engine)

### 2016/04 - 2017/11 : 株式会社トライビート

職務: PHPプログラマ

#### 採用系ウェブアプリケーションの保守開発

- PHP
- MySQL
- Vagrant開発環境のDocker化、及びdocker-compose化

## 登壇歴
### Google Cloud OnBoard 大阪 名古屋
- https://inthecloud.withgoogle.com/onboard-osk-jp-19/register.html?utm_source=google&utm_medium=social&utm_campaign=FY19-Q2-apac-onboard-physicalevent-er-gcp_field_oskjp_onboard_0604_scl&utm_content=gcp_blog
- https://inthecloud.withgoogle.com/onboard-ngy-jp-19/register.html

### 翔泳社主催 Codezine Academy
- https://event.shoeisha.jp/cza/20190927

## 課外活動
### GCPのユーザーグループへの参加/登壇

### 過去の登壇資料
* [connpass](https://connpass.com/user/YukiTominaga/)
* [codezine](https://drive.google.com/open?id=1NbZgrMJF1QzxCe3lYlvURgVDzxmWAM1hZagsjErYQ6k)

### 受賞歴
* AUTHORIZED TRAINER OF THE YEAR'18

世界中のGCP認定トレーナーの中で最も有能であると評価された証

### 執筆歴

* [ネットメディアの記事](https://www.atmarkit.co.jp/ait/articles/1808/20/news024.html)
* Software Design 2019年9月号 GCP特集

### 社内ブログ記事
https://apps-gcp.com/author/tominaga/

## 各OSS/製品に対して業務レベルで取り組めること

### Kubernetes(GoogleKubernetesEngineを含む)
* Podを起動する各リソースのデプロイ
* 想定クエリ/リクエスト量に対する各コンテナへのresroucesの検証と設定
** これに伴うNodeのマシンタイプの設計
* taint, affinity, priorityを利用したPodの配置戦略
* PodSecurityPolicyの策定
* RBACの設定とGoogleアカウントとの連携
* Helmを用いたマニフェストファイル共通化の取り組み
* helmfileを用いたマニフェストファイルのマルチ環境化
* その他GKEにまつわるIAPやWorkroadIdentityの設定

### Istio
* virturalservice, gateway, destinationruleなど基本要素の理解とマニフェストファイルの作成
* circuit-breakerの動作検証
* NodePort ingressgatewayとGCPのHTTP負荷分散を用いたマルチリージョンへの展開(動作検証中)

### Terraform
* localsを利用したマルチ環境への適用を考慮したコーディング
* terraform moduleを利用した定義ファイルの集約

### Angular
* クリーンアーキテクチャーを意識した設計
* 単体テストのコーディング

## できそうに見られるけどできないこと
* アドレスレンジなどを考慮したネットワークの設計
* vmwareなどのオンプレミス環境の運用
* 複雑なSQLの記述
* windowsでの開発
* 基本的にネットワークに関することは苦手

## その他
GCPのトレーニングでは、ArchitectとData Engineeringの両方を務めているので、ほぼ全ての製品に対して基礎は確実に抑えています。
実務レベルで使ったことの無い主なサービスは、`Dataproc`, `Cloud Router`, `BigTable`, `Spanner`, `各種相互接続`, `IoT Core`, `最近出てきたAutoML`です。
