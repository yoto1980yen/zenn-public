---
title: "【AWS Summit】AWS Summit Japan 2025 初めて参加しました【オフライン参加レポート】"
emoji: "📝"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["AWS", "AWSSummit"]
published: true
---
## はじめに
執筆者は AWS Summit に初参加です。オンライン参加もしたことがない初心者です。
今回は個人的な事情もあり Day 2 のみの参加になります。
そんな初心者が初心者なりに参加する際のやっておいたほうが良いことだったり楽しみ方をまとめます

## 事前準備
AWS Summitは事前に聞きたいセッションを登録できるためやっておくことをおすすめします
自分も1か月前からAWS Summitの参加登録をしていたのですが人気のセッションはすでに満席になってました(ワークショップは特に)
一応当日参加でセッションを聞くこともできますが座れないこともあるので注意です

## 現地到着と会場の様子
開催時間は10時なのでそれまでに現地到着するように！
クッションほしい方は特に大事！
自分の場合は以下のスケジュールでした
06:55 飛行機に乗り羽田空港へ
08:25 羽田着(実際は5分遅れで08:30着)
08:40 羽田空港第1ターミナル(空港連絡バス)の14番乗り場から幕張メッセへ(迷う気しかしなかったが何とか見つけれた)
09:35 幕張メッセ到着
入り口では皆さん入場手続きをしておりかなり混雑してました
入場手続きですがAWS Summitにログインしたら確認できるQRコードと身分証明書が必要です(じぶんは焦って手間取っちゃいました)
10時までに行けば先着5000名にクッションがもらえるらしくもらえるかなーと期待しましたがもらえなかったです
同僚に聞いたところ9時30分頃に券をもらえたらしく10時講演のイベントの席に置いてあったらしいです
うらやましい

会場の様子はこんな感じです
![](/images/kaijo1.jpeg)
![](/images/kaijo2.jpeg)
![](/images/kaijo3.jpeg)

## 展示とデモ
会場の様子を見ていただくとわかるように大量の展示がありました
例えばですがDatadogだとこんな感じです
モニターがあり各社サービスの紹介してくれました
気軽に質問や課題を相談できたりもしました
![](/images/datadog.jpeg)

ほかにもレースゲームでAIがレースを作って実際にゲームを楽しめたり
QR読み取ってコーヒー争奪戦してたりとセッション以外もめっちゃ面白かったです

また、各展示の前を通るだけで皆さん資料や菓子類、自社ロゴの入ったグッズなどを配られてました
ちなみに受け取ってしまうと首に下げたネームタグのQRコードを読み取られました
皆さん必死にQRを集めようとしているように感じましたが、企業側でも何か戦っているのでしょうか？

今回受け取ったものはこちらです
個人的にうれしかったのはHashiCorpの箸とDatadogのTシャツです
![](/images/senrihin.jpeg)
<br>

次はセッションに参加したレポートや感想などをまとめます
## セッション
### [10:00 - 11:30] [スペシャルセッションビルダーのための AWS テクノロジー：その深化と進化]
#### 概要
> AWS のサービスは、Amazon のビジネス課題を起点に生まれ、インフラを支える革新的な技術の「深化」と、お客様からいただくご要望に基づくサービスの「進化」を続けてきました。このセッションでは、AWS がインフラ領域において重ねてきた技術革新を掘り下げ、なぜ「ビルダーが描く価値創造」をセキュアかつスピーディに実現できるのか、その背景を紐解きます。さらに、AWS を活用して変革を実現されてきたお客様のお取組みと、お客様の声から生まれた最新のサービスをご紹介します 。

#### レポート
- AWSの信頼性
    - セキュリティは最優先事項
    - 脅威インテリジェンスのプロジェクト(MadPot(攻撃の分析), Sonaris(ネットワークトラフィックの分析), Mithra(ドメインの分析))
    - Nitro System
        - チップの製造品質からファームウェアの品質まで厳密に検証しリアルタイムで認証し続ける
- ドワンゴの講演
    - 3年かけてオンプレからAWSに移行
    - 3年目にサイバー攻撃
    - 2か月で移行しきる(すごい)
- サービス紹介
    - [AWS Security Incident Response](https://aws.amazon.com/jp/security-incident-response/)
    - [AWS Trainium2](https://aws.amazon.com/jp/ai/machine-learning/trainium/)
    - [AWS Graviton4](https://aws.amazon.com/jp/ec2/graviton/)
    - [S3](https://aws.amazon.com/jp/s3/)の歴史
    - DB
        - マルチリージョンでも強い整合性と低遅延を実現
        - [Amazon Aurora DSQL](https://aws.amazon.com/jp/rds/aurora/dsql/)
        - [Amazon DynameDB global tables](https://aws.amazon.com/jp/dynamodb/global-tables/)
- AI
    - Amazon Robotics
        - アマゾン倉庫がどのように管理されているのか知らなかったので衝撃だった
    - [Amazon Bedrock](https://aws.amazon.com/jp/bedrock/?trk=07e11748-d254-4d68-b9eb-c40a095bfc9d&sc_channel=ps&ef_id=Cj0KCQjwpf7CBhCfARIsANIETVql5AR6Srx0mT5Ewyw1yyko8TSCCT-QAKCjsZjqc19oAPZz2Ju9fBwaArtUEALw_wcB:G:s&s_kwcid=AL!4422!3!692062154777!e!!g!!amazon%20bedrock!21048268287!157173579577&gad_campaignid=21048268287&gbraid=0AAAAADjHtp9FhpL1eLszYe5F2WW7lGFVy&gclid=Cj0KCQjwpf7CBhCfARIsANIETVql5AR6Srx0mT5Ewyw1yyko8TSCCT-QAKCjsZjqc19oAPZz2Ju9fBwaArtUEALw_wcB)
        - AmazonのRufasもBedrockで作っている
    - [Amazon Nova](https://aws.amazon.com/jp/ai/generative-ai/nova/?trk=38cc0cc4-7da9-4785-9231-aba910a719d1&sc_channel=ps&ef_id=Cj0KCQjwvajDBhCNARIsAEE29WqU3qsrlkKhNxPuN5P8oFLOlDnrNWzaQ1-vwtuihn8_iivepm562WIaAgV8EALw_wcB:G:s&s_kwcid=AL!4422!3!692062154792!e!!g!!amazon%20nova!21048268290!157173580977&gad_campaignid=21048268290&gbraid=0AAAAADjHtp-hIXj7b4Nups6LOAXBS0Zin&gclid=Cj0KCQjwvajDBhCNARIsAEE29WqU3qsrlkKhNxPuN5P8oFLOlDnrNWzaQ1-vwtuihn8_iivepm562WIaAgV8EALw_wcB)
    - [Amazon Q Developer](https://aws.amazon.com/jp/q/developer/)
        - 計画からコード実装、テスト、運用までライフサイクル全般をサポート
        - AIは進化し、サポートするのではなく自立して開発からテスト、ドキュメンテーションまで行うようになっている
    - MCP
        - [Strands Agents](https://aws.amazon.com/jp/blogs/news/introducing-strands-agents-an-open-source-ai-agents-sdk/)
            - わずか数行のコードで AI エージェントを構築・実行するモデル駆動型アプローチを採用したオープンソース SDK
- モダナイズについて
    - [AWS Transform](https://aws.amazon.com/jp/transform/)
         - .NET Framework, COBOL on Mainframe, VMwareの移行を支援する
    - [AWS EVS](https://aws.amazon.com/jp/evs/)でVMwareをモダンに移行する
- ANGEL Dojoで内製化支援も

#### 感想
AWSのサービスについて自分はちゃんと調べたことはなかったのでこんなサービスがあるのか、Amazon倉庫ってこんなにロボットで管理されていたのかと驚かされました
仕事で使っているなら把握しとけって話ですが


### [12:50 - 13:30] [オンラインゲーム開発におけるプラットフォームエンジニアリングと Amazon EKS による実装例]
#### 概要
> クラウドの進化によってインフラとアプリケーションの境界が曖昧になる中で、プラットフォームエンジニアリングを取り入れることでゲーム制作チームが自律してゲームバックエンドを開発・運用できるようにする、そのための新しいインフラチームのあり方を提案します。また、それを実現するための手段として Amazon EKS を中心とした実装例を紹介します。

#### レポート
- 課題
    - サーバーの開発と運用の課題解決
    - 大規模なトラフィックの解消
- 理想 基盤を共通化しインフラの負荷を減らしながらスケールしやすい環境をチームごとに作ること
    - プラットフォームエンジニアリング
    - 開発チームごとに開発基盤を起動できるようにしIaCやCloudFormationで簡単に起動できるようにする
    - インフラチームはドキュメントやトレーニングを主に行う
- プラットフォームエンジニアリングを行う上で大事なこと
    - 最小限から始める(ドキュメントのみからはじめ、自動起動やトレーニングなど行う)
    - 余計な機能は作らない
    - 新技術に柔軟に対応できるようにする
- 実例
    - Amazon EKSで開発チームごとにアカウントを用意し一元管理(AWS Organizations, AWS Control Tower)
    - TerraformでEKSクラスターを簡単に起動できるようにする
    - デプロイも簡単に行うためGitOpsを利用する(ArgoCD)
        - image も [ArgoCD Image uploader](https://argocd-image-updater.readthedocs.io/en/stable/)で自動反映
    - スケールは[Karpenter](https://karpenter.sh/)
        - スケール後の起動が早いしコスト最適化してくれる

#### 感想
ほとんど自分が開発でやっていることと同じすぎて共感の嵐だった
ArgoCD Image Uploaderは使ったことないので検討してみたい
imageの変更って単純作業ではありますが何度もやるので面倒ですもんね(Tag変えてPushして...)

### [13:30 - 14:00] [研究成果を最速でリリースするための Amazon EKS プラットフォーム - 100 以上のサービスを支える基盤]
#### 概要
> Sansan の研究開発部では、ビジネスに直結する研究開発を行っており、“Sansan Labs” というデータを活用したプロダクトアイデアをベータ版的に迅速にリリースする仕組みも開発しています。これを支えるのが、研究開発部が運用している EKS 基盤 “Circuit” です。この Circuit では、数十から百単位のアプリケーションが稼働していますが多種多様です。研究開発部ではインフラの運用効率化を目指しており、どのような判断基準/方法で Circuit に移行するのか、また Circuit を運用する上で工夫している点についてお話します。

#### レポート
- 課題
    - 開発チームが複数開発を行うがリリースが一つずつしか行えずリリースでボトルネックになっていた
- 対応
    - EKSを採用
    - 認知負荷、kubernetesの習得が重いなど問題がある
    → アプリ,API,パッチ等をテンプレートを用意。UIで変更できるようにすることで解消
- 結果
    - リリース頻度の向上
- その他
    - コスト按分が必要
        - チームごとだったりでコストを知りたい場合
        → ノードごとにnamespaseを分ける
        - 利用者視点のコストを知りたい
        →[SCAD](https://docs.aws.amazon.com/cur/latest/userguide/split-cost-allocation-data.html)を使う
    - 運用負荷を減らすため自動でimageの更新を行う
        - ArgoCD Image Uploaderを使う
        - ECRの認証が非効率だったのでArgoCD Image Uploaderを止めて内製化した

#### 感想
imageの自動更新はやはり必要だなと思いました
kubernetesは学習コストが重いからこれを開発者がいかに触れることなく使えるようにするのかは大事ですね
実際、自分もKubernetes触れ始めたとき全然意味わからなかったです

### [14:20 - 14:50] [PlayStation™Network のボイスチャットサーバの Amazon EKS 移行と Hybrid Cloud 化]
#### 概要
> 本セッションでは、PlayStation™Network のボイスチャットサーバ を Amazon EC2 から Amazon EKS へ移行し、Hybrid Cloud 化 した事例を紹介します。加えて、Hybrid Cloud 化によるコスト最適化達成のために、Kubernetes の拡張 OSS である Agones をどのように活用し、ボイスチャットサーバのセッション管理、ライフサイクル管理、スケーリングなどを実現したか、およびグローバルチームで行ったプロダクション導入プロセスについて紹介します。

#### レポート
- 課題
    - ボイスチャットサーバーはセッションが途切れるわけにはいかないのでいかにセッションを維持したままスケールするかが難しい
    - スパイクアクセスやピーク・オフピークがわからない
    - リアルタイム性のため低遅延な通信
- 対応
    - [Agones](https://agones.dev/site/)を使う
        - UDP通信、Pod(セッション)の保護やフリート機能などゲームサーバに適したホスティングプラットフォーム
    - EC2からEKSに移行したことで柔軟にスケールできる基盤を用意
    - スパイクに耐えるためReady状態のセッションを複数起動しておきスパイクアクセスが来ても耐えられるようにする
    - セッション管理を[DynamoDB](https://aws.amazon.com/jp/dynamodb/)、ルーティングを[Lambda](https://aws.amazon.com/jp/lambda/)で実装(マネージドなサービスだと柔軟に操作できないため)
- 余談(Hybrid Cloud化)
    - コスト最適化のため一部オンプレミス環境にボイスチャットサーバーを用意
    - Podの管理サーバやルーティングサービスは全てAWS上に用意
    - ルーティングを一部オンプレミス環境に向けるだけで成立するようにしている

#### 感想
セッションを維持しないといけない、UDP通信しないといけない、急なアクセスがくる場合を考慮しないといけないなど対応するのに苦労したんだなと聞いてて思いました
DynamoDBでセッション管理やLambdaでルーティングがその例かなと
Hybrid Cloud化は勝手に難しいと思っていましたがPodの管理もAWSであとはルーティングするだけなので手法によっては難しくないのだなと感じました

### [15:10 - 15:40] [SmartNews における 1000+ ノード規模 K8s 基盤 でのコスト最適化 – Spot・Graviton の大規模導入への挑戦]
#### 概要
> SmartNews では「世界中の良質な情報を必要な人に送り届ける」をミッションに掲げ、日本と米国でニュースアプリ 「SmartNews」 を提供しています。SmartNews は 1000+ ノード規模の Amazon EKS 基盤を共通プラットフォームとして利用しており、2023 年から 2024 年にかけて、スポットインスタンスや AWS Graviton プロセッサ、Karpenter を戦略的に導入してきました。これにより、インフラコストを最大 50% 削減し、パフォーマンスが向上する効果も現れています。本セッションでは、大規模 Amazon EKS 基盤上でのコスト削減について、Platform 側の横断施策と Product チーム側での取り組みの 2 つの観点から技術的な工夫を含めお話しします。

#### レポート
- 課題
    - 昨日ファストで開発した結果コストがえぐいことに、、、コスト削減したい
    - 柔軟なキャパシティが必要
    - 不安定なリクエストに耐えたい
- 対応
    - 基本的なアクセスはオンデマンドインスタンスを使い、急なアクセスには[スポットインスタンス](https://aws.amazon.com/jp/ec2/spot/)を使う
    - 最新のGravitonを使う(最良の料金とパフォーマンスを提供)
    - 迅速にスケールするためKarpenterを使う
- 対応するにあたって
    - スポットインスタンスの不安解消するためAWSエキスパートと共働で社内セッション実施
    - 安心して使うためにダッシュボードを作成(スポットとオンデマンドそれぞれ分けて監視)
- 大事な点
    - この対応を行う専用のチームを作る
    - どこにコストがかかるか計測から始める
    - ダッシュボードは作るべし
    - 不安定なスポットインスタンスもあるので避けて使うようにする

#### 感想
急なアクセス等にスポットインスタンスを使うのはかなり良いと思いましたが、やはり安定するのかという不安はありますね
実際このセッションを聞いているとどのようにして上の者にこの不安を解消できるか説得したと言う風に聞こえました
自分が仕事しててもスポットインスタンスを使いましょうという提案は通らなさそうだなとやはり思います
あとここでもKarpenterが出ましたね
基本的にKubernetesでスケールするならKarpenterなのでしょうね。AWSが作っているのでサポートを得られやすいという利点もありますし

### [16:00 - 16:30] [モンスターハンターワイルズ 100 万以上のユーザー同時接続を支えたネットワークアーキテクチャ]
#### 概要
> モンスターハンターワイルズは多くのユーザからのアクセスを見込んだクロスプラットフォーム対応 AAA タイトルです。 日本だけでなく世界各地から巨大なトラフィックが見込まれるネットワークタイトルで、サーバを 0 から構築するにあたりどのような技術を選択し、どういった苦労や工夫が行われたかご紹介させて頂きます。

#### レポート
- 背景と課題
    - モンスターハンターワイルズからは自社でネットワークを管理、マルチプラットフォームを実現
    - 数百万人が同時接続しても耐えられるサーバーが必要
- 対応
    - EKS on Fargateを利用
        - Agonesを使うため
        - 管理が楽
        - 結果的にはECSでもよかったかもとのこと
    - マイクロサービスアーキテクチャを採用
         - サーバアプリを12個に分割
         - 良いところはチューニングしやすい、コンフリクトが起きにくい
         - 悪いところはCIが複雑化、トランザクションが重複してしまう
    - サービス間通信の制御をインフラ層で制御するため[AWS App Mesh](https://aws.amazon.com/jp/app-mesh/)を導入
- 事件発生
    - 第一回OBT直前にAWS App Meshのサービス終了のお知らせ
    - 急遽代替製品の選定と負荷試験のやり直しなど必要になった
    - [Amazon VPC Lattice](https://aws.amazon.com/jp/vpc/lattice/)を採用
        - プロキシサーバー等が不要になったがレスポンスは遅くなった(許容できる範囲)
- リアルタイムサーバについて
    - 100人集まるロビーの大量のパケットをリレーしないといけない
    - Gravtion3を採用(かなりの負荷に耐えてくれた)
    - 規模が大きくなりすぎて数万Podを超える、負荷を減らすためクラスターも複数台起動(多いリージョンで5つ)
    - スケール戦略としてユーザー数と腕前で負荷を変えている
    - スケーラーはKarpenter
    - この規模になるとGravtion3を建てられる台数が限界を迎えるらしい(別リージョンで賄う)
- DBについて
    - 兎にも角にも超トラフィックに耐え、スケールできるDBが必要
    - 基本的にはNoSQLであるDynamoDBを使用(ID直接参照する機会が多く負荷は意外と抑えれている)
    - DynamoDBでは厳しい救難信号やサークル検索など複雑な検索には[TiDB](https://pingcap.co.jp/tidb-self-managed/)を利用([Marketplace](https://aws.amazon.com/marketplace/pp/prodview-7xendfnh6ykg2)で利用可能)
- その他
    - モニタリングは[Amazon Managed Service for Prometheus](https://aws.amazon.com/jp/prometheus/)と[Amazon Managed Grafana](https://aws.amazon.com/jp/grafana/?nc=sn&loc=0&refid=3b998ccc-2a3e-4e22-8114-263de972ccfc)
    - APMは[AWS X-Ray](https://aws.amazon.com/jp/xray/)
    - 負荷試験は[Locust](https://locust.io/)。[ECS](https://aws.amazon.com/jp/ecs/)で負荷をかける(最終的には500万同時接続に耐えている)
    - OBT、リリース時には[AWS Countdown Premium](https://aws.amazon.com/jp/premiumsupport/aws-countdown/)を利用し緊急時にサポートしてもらっていた(EBSのクォータを上げたほうが良いとアドバイスがあった)
    - 使用プログラミング言語はGo
    - チーム体制は8人

#### 感想
ブース外にまで聴講しに来ていた人も多く期待感もすごかったが、その期待を裏切らなくらい面白かった
まず規模がすごい、リージョンに建てられるインスタンス数が最大になるとか1クラスターだと負荷がかかりすぎて複数台建てたなど別次元の話をしてて面白い
OBTを行う前に使うサービスが終了するといわれるのは怖いですね、よくOBTまでにサービスを変えて負荷試験等やり切ったのはすごいとしか言いようがないです
最終的にはECSでもよかったかもと言っていたのは気になりました
確かに詳細な設定がそこまで必要なければこちらのほうが楽でしょうしコストも抑えれるのではと思いました
Kubernetesは学習コストが高いのも欠点ですしね

## 一日を通して
初めてAWS Summitに参加しましたがめっちゃ楽しかったです
チームメンバーと一緒に参加して感想を言い合えるのもいいですね
あとは名刺交換をすると聞いてましたが意外とやらない？GitLabの方と話したときに名刺交換をしたくらいでしたね
自分から積極的に交換しようとしない限りはないのかもですね
クッションのリベンジのためにも来年も行きたいですね

## 余談
AWS Summit終わりにチームのメンバーとそのまま飲み会に行ったのですが、呑みすぎでダウンしてしまい申し訳ないと思いながらも皆さん優しかったのでいい思い出です

次の日は有休取ってそのまま東京観光しちゃいました
思い出をここでも共有
![](/images/panda.png)
![](/images/lunch.jpeg)
![](/images/dessert.jpeg)
![](/images/kaminarimon.jpeg)
![](/images/skytree.jpeg)
![](/images/skytree2.jpeg)
![](/images/dinner.jpeg)
![](/images/booty.jpeg)