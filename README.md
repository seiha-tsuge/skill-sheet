# 職務経歴書

2021 年 10 月 24 日

## 個人情報

| 名前 | 年齢 | 居住地             | 最寄駅           |
| :--- | :--- | :----------------- | :--------------- |
| S・T | 28   | 神奈川県川崎市幸区 | 新川崎駅, 日吉駅 |

## 職務要約

私はこれまで 3 年 8 ヵ月、Web アプリケーションエンジニアとしてシステム開発業務に従事し、キャリアを積んで参りました。そこでは Java, Python を利用したバックエンド開発、Vue.js を利用したフロントエンド開発に邁進し、加えて設計などの上流工程での業務にも注力することで、着実に Web アプリケーションエンジニアとしての経験・スキルを積み重ねることができたと振り返ります。

## 職務経歴（略歴）

### システム開発に関する職歴

| 時期             | 期間    | プロジェクト名                                                                        |
| :--------------- | :------ | :------------------------------------------------------------------------------------ |
| 2021/07〜2021/10 | 4 ヵ月  | [就職情報システムリプレイス](#就職情報システムリプレイス)                             |
| 2020/07〜2021/06 | 12 ヵ月 | [コミュニケーションプラットフォーム開発](#コミュニケーションプラットフォーム開発)     |
| 2020/05〜2020/06 | 2 ヵ月  | [QRCode Hangtag](#QRCode-Hangtag)                                                     |
| 2019/06〜2020/04 | 11 ヵ月 | [入出荷 Web システム及び SCM システム開発](#入出荷-Web-システム及び-SCM-システム開発) |
| 2019/03〜2019/05 | 3 ヵ月  | [可視化システム(Mobile Data Viewer)](#可視化システムmobile-data-viewer)               |
| 2018/12〜2019/02 | 3 ヵ月  | [在庫管理システム画面側開発](#在庫管理システム画面側開発)                             |
| 2018/03〜2018/11 | 9 ヵ月  | [H31 システム更改](#H31-システム更改)                                                 |

## 職務経歴

### 就職情報システムリプレイス

#### 2021/07〜2021/10

#### プロジェクト概要

就職情報(合同企業説明会, 就活イベント, 就活セミナー等)システムのリプレイス

#### 担当業務

- Vue.js を用いたフロントエンド開発を担当

#### 工夫した点・実績

| 課題                                       | 解決策                                            | 改善                                                                                                                                                               |
| :----------------------------------------- | :------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ソースコードを ZIP ファイルでやりとり      | GitHub の導入を働きかける                         | バージョン管理ができるようになり、チームの作業効率が向上                                                                                             |
| 開発経験が浅いメンバーが半数以上           | コードレビューを実施                    | 積極的にフィードバックすることで、チームの技術力向上に貢献する。また、各人が担当した機能以外に関わることが無いため属人化していたが、仕様が共有されることで属人化を防止 |
| 各ファイルが数千行もあり、見通しが悪い状態 | 共通する部品を洗い出し責務ごとにコンポーネント化 | コンポーネントを用意することでチームの開発速度が向上。同時に、JavaScriptの処理を関心ごとに切り分けることで、変更に強いソースコードに改善                                       |

技術的負債が大きく、影響範囲の大きいリファクタリングが必要なソースコードについても、推進力を持って負債の返済を行いました。アンチパターンがよく見受けられる品質の悪いソースコードをリファクタリングするのは初めてだったため、スキル向上の転機になりました。

#### 使用技術

AWS(EC2, S3), JavaSctipt, Vue.js, PHP, Laravel, MySQL

---

### コミュニケーションプラットフォーム開発

#### 2020/07〜2021/06

#### プロジェクト概要

紙の社内報やイントラネットに代わる、効率的・効果的・戦略的な社内コミュニケーションプラットフォームの開発

#### 担当業務

- Vue.js を用いたフロントエンド開発および設計、単体・結合テストを担当
- 顧客とのカウンター業務

#### 工夫した点・実績

このプロジェクトでは、デザイナーチームの方と協業しながら UI 設計を行いました。
新機能開発ではライブラリの調査から導入まで一人称で対応しながら、
特に「顧客との信頼関係づくり」「顧客のビジョン達成」「チーム開発のコミュニケーション」のために、以下のような取り組みをしてきました。

【顧客との信頼関係づくり】

1. 顧客との定例会議に毎日参加
1. 隔週で顧客とのゲーム界に参加

【顧客のビジョン達成】

1. 顧客との定例会議に毎日参加し、要件や仕様について協議する
1. プロダクトの強みや特徴などの理解し、顧客とのコミュニケーションを行う
1. 仕様について自ら顧客に働きかけて合意形成する

【チーム開発のコミュニケーション】
1. 設計方針や実装方針について前もって議論を重ね、実装後も相互にコードレビューをして、品質向上に尽力する
1. バックエンドチームと意見を出し合いながら API を設計
1. バーチャルオフィス（Gather.Town） を利用 
対面と遜色ないコミュニケーションをとり、全員フルリモートでの開発環境をよりスムーズなものにしました。
1. プロダクトやチーム、技術的な課題についてチームメンバーと日々意見を出し合う

#### 使用技術

AWS(MediaConvert, CloudFront, CloudSearchy, S3, CodePipeline, CloudSearch), JavaSctipt, Vue.js, Python, Flask, Flask-RESTPlus, MySQL

---

### QRCode Hangtag

#### 2020/05〜2020/06

#### プロジェクト概要

商品を購入した一般消費者が商品購入後、下げ札の QR コードをスマホで読み取ることで、ブラウザベースで商品に紐付くコンテンツ(機能説明)を閲覧可能にする。  
年始に受注予定案件を前倒しで開発に着手するも、同時に複数案件を受注できたため、一旦プロジェクトを中止

#### 担当業務

- 画面/API/DB 設計、API/フロントエンド開発、単体テストを担当
- Python, Vue.js を用いたアプリケーション開発に従事

#### 工夫した点・実績

このプロジェクトは、ペアプログラミングでの開発でした。
そのため、ペアの相手との積極的な雑談や、チーム全体での毎週進捗報告・意見交換を行い、円滑に作業が進むよう邁進しました。
さらに、TDD とクリーンアーキテクチャを採用し、バックエンドの品質管理を徹底しました。
AWS は当時未経験でしたので、日々の開発を通じたキャッチアップに努めました。

- ペアプログラミングにて開発。相互の信頼関係を構築するために、雑談などを積極的に行う
- 毎週振り返りを行うことで、チームとしての成長を図る
- AWS は初めて触れる技術でしたが、日々の開発を通じてキャッチアップ
- バックエンドは、TDD およびクリーンアーキテクチャを採用することで品質管理を徹底。

#### 使用技術

AWS(Lambda, API Gateway, CloudFront, S3, Cognito, Amplify), TypeSctipt, Vue.js, Vuetify, Python, SQLAlchemy, MySQL

---

### 入出荷 Web システム及び SCM システム開発

#### 2019/06〜2020/04

#### プロジェクト概要

SCM(サプライチェーン・マネジメント)システムの新規開発  
SCM と連携する API および Web 画面の新規開発

#### 担当業務

- 基本設計、単体/内部結合/外部結合/シナリオテストの各仕様書作成を担当
- チームメンバーが作成した各仕様書のレビュー
- チームメンバーの取りまとめや、プロジェクトマネージャーの補佐

#### 工夫した点・実績

試験観点の策定など未経験の建てつけ作業を試行錯誤しながら推進しました。
また、テストリーダーの業務負担軽減のため、要件や仕様の把握を丁寧に行うことを意識しました。
さらに、以下 3 点から、成果物の品質向上に貢献しました。

1. 設計の抜け漏れを早期に検知
1. 大量の設計書のレビューを実施し、スケジュールを遵守
1. 多数いる設計未経験な若手に、これまでの経験を生かしてアドバイス

それに加えて、以下 4 点の心がけを継続して行いました。

1. 遠方のメンバーとの円滑な意思疎通
1. メンバーのモチベーションを維持するためのコミュニケーション
1. メンバーとプロジェクトマネージャーの間に入り、プロジェクトマネージャーを補佐
1. プロジェクトマネージャーにチームの問題を把握して報告

#### 使用技術

Azure(API Management, Azure Functions, Azure Storage, Azure Database for MySQL), TypeSctipt, Vue.js, Vuetify, Node.js, Sequelize

---

### 可視化システム(Mobile Data Viewer)

#### 2019/03〜2019/05

#### プロジェクト概要

都市部の渋滞や移動困難者、公共交通のドライバー不足など、さまざまな社会課題の解決策を目的とした「MaaS」プロジェクト

#### 担当業務

- API/フロントエンド開発、単体テストを担当
- Flask を用いたユーザー管理画面向けの API 開発
- ゼンリン API や内製 API(携帯基地局情報や自動車の走行データ)と連携し、地図上に各データを重ね描画

#### 工夫した点・実績

このプロジェクトに私が最も貢献したのは、リソースに必要な機能を 1 人称で開発したことです。
また、このプロジェクトを通じて、TypeScript と Flask の技術を身につけました。
この時に初めてコードレビューを受け、ベテランエンジニアのノウハウを学ぶ機会となりました。

#### 使用技術

AWS(RDS, EC2, S3), TypeSctipt, Vue.js, Vuetify, Python, Flask, Flask-RESTful, SQLAlchemy, MySQL

---

### 在庫管理システム画面側開発

#### 2018/12〜2019/02

#### プロジェクト概要

外部システムと連携し、在庫管理を支援する画面を新規開発

#### 担当業務

- API/フロントエンド開発、単体テストを担当
- Django REST framework , Wijmo を用いたアプリケーション開発に従事

#### 工夫した点・実績

このプロジェクトで、Vue.js, Wijmo, Python, Django の技術を会得しました。
さらに、担当画面のバックエンド・フロントエンドを単独で開発し、プロジェクトの一翼を担いました。
API 開発とフロントエンド開発を同時にこなすことで、幅広い視野を獲得できたと実感しています。
その上で、テストリーダーと綿密に協力してすべてのバグの改修にも取り組みました。

#### 使用技術

Python, Django, Django REST framework, JavaSctipt, Vue.js, Wijmo, jQuery, MySQL

---

### H31 システム更改

#### 2018/03〜2018/11

#### プロジェクト概要

システムの刷新に係る職業紹介システムの設計・開発等

#### 担当業務

- 基本設計、バックエンド開発、単体テスト
- Java/JSP を用いて求人画面を更改

#### 工夫した点・実績

まず、要件定義書を基に、顧客の要望を満たす設計書を作成しました。
その設計書に関して、チームレビュー、リーダーレビュー、元請けレビュー、顧客レビューなど多くの視点から指摘を頂き、考慮不足を認識して成長することができました。
また、その設計書をもとに、上流から下流まで一貫したシステム開発を経験することができました。

#### 使用技術

Java, Spring, Servlet/JSP, Symfoware

## 活かせるスキル・経験

| スキル     | 経験年数    |
| :--------- | :---------- |
| Java       | 5 ヵ月      |
| Python     | 8 ヵ月      |
| JavaSctipt | 1 年 7 ヵ月 |
| TypeSctipt | 5 ヵ月      |
| Vue.js     | 2 年        |
| 設計書作成 | 1 年 3 ヵ月 |

## 自己 PR

- 私はテクニカル的には Vue.js を利用したフロントエンド開発を得意としております。
- フロントエンド開発だけではなく、バックエンド開発も可能です。
- 過去案件においては、周囲からフォロワーシップやメンバーシップを高く評価していただきました。
  - PM にお前がいなかったら心が折れてたと言われる
-

フォロワーシップでは、メンバーが困っていることなどの情報を集め、必要に応じてリーダーに情報をあげる、
フォロワーシップやメンバーシップの能力を評価されることが多いです。フォロワーシップでは、リーダーの方にお前がいなかったら心が折れてたとよく言われます
メンバーシップでは、みんなのモチベーションが上がるように努めます
褒めたし、感謝の気持ち忘れないし、自信が持てるようにしてあげてた、達成感を持たせる
諦めない投げ出さない
どういう状況下でもプロジェクトを前に進める
コミュニケーションを大事にしていて、その場の雰囲気やメンバーの性格や好きなものとかを把握するように努め、メンバー間の心理的安全性を作るのが得意で、
困っていることをちゃんと掴んで、上の人にあげて、みんながハッピーにできるよ

フォロワーシップとは、チームの成果を最大化させるために、「自律的かつ主体的にリーダーや他メンバーに働きかけ支援すること」です
週２の個人開発をデザインから行うことで UI 設計の実践や、最新技術を採用することでモダンな開発手法を身につける s
また、プログラミングブートキャンプ（プラハチャレンジ）に参加し課題解決力や技術力を高めています

- 力づけ　フォロワーシップ
- 習慣を変えれる　試してみて
- 定着した習慣
- 年齢や経験年数が上の相手に意見を言える
- ドキュメント読む
- 設計
- エピソード一つ書くぐらい
- こういう出来事があってっていう事実ベースで書く

私はテクニカル的には、Python を利用した Web アプリケーション開発を得意としております。さらにバックエンド開発だけではなく、フロントエンドの開発も可能で御座います。過去案件においては、Web 関連の能力・知識を周囲から高い評価を頂き、ウォーターフォール開発では上流工程のリーダー・サブリーダーも任せていただくこともありました。そこでもただ任された業務をそのままこなすのではなく、チームにおける円滑な開発プロセスを意識し、特にレビューをする際にも、ただのレビューで終わらすのではなく相手への伝え方や、ネクストアクションや積み残しタスクの視える化や、抜け漏れのない業務の徹底を行い、生産性向上とモチベーションアップを意識して行動に落とし込んでまいりました。また、私が仕事に取り組む中で最も大切にしていることは、チームでのノウハウ共有です。ドキュメント管理を徹底し、チームメンバーには積極的に共有、そして全員がそのノウハウを共有する文化を醸成することで、「1 人の学びを皆の学びにする」筋肉質かつ骨太なチームの構築経験が御座います。今後のプロジェクトにおいても同様に、より良い環境を作り上げ、常に PDCA を回し続けながら、さらに自分自身を成長させていきたい決意です。
何卒宜しくお願いします。

web クリエイターとして、さらにレベルアップを図るべく、昨年「カラーコーディネーター」の資格を取得しました。終業時間が不規則なこともあり、限られた時間の活用法を追求するうち、業務を効率よく進める姿勢にもつながりました。社内からは web のクリエイティビティはもちろん、「誰よりも段取りが早く的確」との評価を得られるようになったことも大きな収穫です。これまでの経験を生かしつつ、御社が手がける大規模なプロジェクトや新たなサービスを通して web ディレクターとして、さらにキャリアアップしたいと考えております。

今まで目的を達成するために必要であれば、英語のスキルやデータベースの資格取得などを行い、積極的に習得してきました。未経験のことも身に付けていく自信があります。これまでにない国際的なイベントを開催している貴社で、英語力とこれまでの積極性を持って新たなことを吸収しながら貢献していきたいと思っています。
