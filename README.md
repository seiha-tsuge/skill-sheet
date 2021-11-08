# 職務経歴書

2021 年 10 月 28 日

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

| 課題                                       | 解決策                                           | 改善                                                                                                                                               |
| :----------------------------------------- | :----------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| ソースコードを ZIP ファイルでやりとり      | GitHub の導入を促進                              | バージョン管理を可能にし、チームの作業効率が向上                                                                                                   |
| 開発経験が浅いメンバーが 5 名中 3 名       | コードレビューを実施                             | 積極的にフィードバックすることで、チームの技術力向上に貢献。また、仕様が共有されることで、各人が担当した機能以外にも関わるようにし、属人化を防止。 |
| 各ファイルが数千行もあり、見通しが悪い状態 | 共通する部品を洗い出し責務ごとにコンポーネント化 | コンポーネントを用意することでチームの開発速度が向上。同時に、JavaScript の処理を関心ごとに切り分けることで、変更に強いソースコードに改善。        |

影響範囲の大きいリファクタリングが必要なソースコードについても、推進力を持って技術的負債の返済を行いました。
アンチパターンがよく見受けられる品質の悪いソースコードをリファクタリングするのは初めてだったため、スキル向上の転機になりました。

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

このプロジェクトでは、以下のチームメンバーと協業しながら UI 設計を行いました。
・バックエンドチーム　 3 名
・フロントエンドチーム　 2 名（私を含む）
・デザイナーチーム　 2 名

新機能開発ではライブラリの調査から導入まで一人称で対応しながら、
特に「顧客との信頼関係づくり」「顧客のビジョン達成」「チーム開発のコミュニケーション」のために、以下のような取り組みをしてきました。

【顧客との信頼関係づくり】

1. 顧客との定例会議に毎日参加
1. 隔週で顧客とのゲーム会に参加

【顧客のビジョン達成】

1. 顧客との定例会議に毎日参加し、要件や仕様について協議する
1. プロダクトの強みや特徴などを理解し、顧客とのコミュニケーションを行う
1. 仕様について自ら顧客に働きかけて合意形成する

【チーム開発のコミュニケーション】

1. 設計方針や実装方針について事前に議論を重ね、実装後も相互にコードレビューをして、品質向上に尽力
1. バックエンドチーム 3 名と意見を交わしつつ API を設計
1. バーチャルオフィス（Gather.Town） を利用  
   対面と遜色ないコミュニケーションをとり、全員フルリモートでの開発環境をよりスムーズなものにしました。
1. プロダクトやチーム、技術的な課題について各チームメンバーと日々意見を出し合う

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
そのため、ペアの相手と積極的な雑談や、意見交換を行い、円滑に作業が進むよう邁進しました。
また、毎週のふりかえり(KPT・YWT)を意欲的に推進することで、問題の共有と解決を迅速に行いました。
さらにはチーム 5 名に必要な知識を適宜共有し学びを吸収した結果、チームの成長に貢献することができました。
加えて、TDD とクリーンアーキテクチャを採用し、バックエンドの品質管理を徹底しました。
AWS は当時未経験でしたので、日々の開発を通じたキャッチアップに努めました。

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

1. 15 人前後のメンバーの負荷状況・タスク進捗状況の把握に努め、プロジェクトマネージャーを補佐
1. フロントエンドチームとバックエンドチームのコミュニケーションのハブになり、円滑な連携を支援
1. メンバーに対してポジティブなフィードバックや感謝の気持ちを積極的に伝える
1. 口数が少ないメンバーに配慮して意見や感情を引き出すなど、発言しやすい環境づくり

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
その上で、テストリーダーと綿密に協力してテスト観点を考慮したテストケースを作成し、発生したバグの改修にも取り組みました。

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

フォロワーシップとは、チームの成果を最大化させるために、「自律的かつ主体的にリーダーや他メンバーに働きかけ支援すること」です

- 力づけ　フォロワーシップ
- 習慣を変えれる　試してみて
- 定着した習慣
- 年齢や経験年数が上の相手に意見を言える
- ドキュメント読む
- 設計
- エピソード一つ書くぐらい
- こういう出来事があってっていう事実ベースで書く

- 技術的には Vue.js を利用したフロントエンド開発が得意

  - フロントエンド開発だけではなく、バックエンド開発も可能

- 周囲からフォロワーシップ高く評価される

  - PM にお前がいなかったら心が折れてたと言われる
  - リードエンジニアに
  - メンバーに対して中期的なキャリアの観点からフィードバックすることができる
  - チームメンバーの負荷状況を把握している
  - システムコーチやリードエンジニアの支援をもらった上で、チームの関係性の質を高めるための対話の場を作ることができる
  - チームのメンバーが意見を言いやすい場作りができる
  - チームメンバー同士での定期的な振り返りの場を作ることができている
  - チームメンバーの強みや弱みを理解し、チームの成果を最大限発揮するような役割分担を行うことができる
  - チームのメンバーが新しい挑戦や 実験 を行うことを推奨し、挑戦行動に対してポジティブなフィードバックを返すことができている
  - 意見をあまり言わないチームのメンバーがいた場合に、配慮して意見を聞き、居場所をつくってあげることができる
  - 周りがなかなかやらないが、やらないといけない作業を率先してやっている
  - 将来の懸念点やリスクを事前に的確に予見し、意見することができている
  - チームの関係性の質を高めるための対話の場を設計、用意することができる
  - メンバー同士のピア・フィードバックを行う場づくりを定期的に行うことができた上で、自分自身への今後の機会点（Next）も含めたフィードバックを積極的に受けるようにできている
  - 開発標準、開発プロセス、開発環境、会議設計、ベロシティ、チームの関係性の質について意見や改善提案を主体的に行う
  - 職位に関係なく関わるメンバーに対して良い点だけでなく、今後の機会点もフォードバックすることができる
  - タスクの進捗状況を積極的に把握した上で、遅れているタスクに対して適切な解決を行うためのアクションを行うことができる
  - 将来の懸念点やリスクを事前に的確に予見し、意見することができている
  - ユーザー体験を考慮した上で、提案、意見を出すことができている
  - 社内メンバーとのコミュニケーションにおいて、人によって態度や振る舞いを変えないようにできている

- 過去案件の実績

  - 設計書や仕様書の作成

    - 要件定義において抽出した要件を機能単位に分割し、設計手法を理解した上で、基本設計書を作成することができる
    - テスト観点を考慮したテストケースを作成することができ、必要に応じて単体・結合・シナリオテスト仕様書を作成することができる

  - 新機能の実装

    - 可読性や保守性を考慮したコードを書くことができている
    - プラットフォーム、開発言語、フレームワーク、ライブラリに関する基礎知識があって実践で活かせている
      全体システムの設計思想、方針を理解した上で、担当する機能実装についての詳細設計を独力で実施できる
      可読性や保守性、テスト容易性、変更容易性、耐障害性、追跡可能性を考慮した上で、安定して本番反映可能なコードを書くことができる
      仕様が複雑な部分であったり、サービスに影響ある部分の開発も担当する事ができる
      チームが担当する機能の実装容易性や実装可能性を損なう事が無いように、前行程での仕様の確認、合意形成、連携する関連システムとの仕様調整などを行う事ができる

  - 技術的負債の返済

    - 技術的負債の削減・返済についての計画を行い、主導的な役割を担って解決
    - 技術的負債の返済についての方針策定を主導して行い、自ら複雑な部分の解決も行う
    - 技術的負債が大きく、影響範囲大きいリファクタリングが必要なコードについても、推進力を持って負債の返済を行う

- ビジネスコミュニケーション

  - 社内のビジネスコミュニケーションとして円滑なやりとり
    - プロジェクトにおいて連携する他業種の業務内容や専門用語などを理解し、連携性において円滑なコミュニケーション
    - 仕様について自ら関係者に働きかけて合意形成
    - チームが担当する機能の実装容易性や実装可能性を損なうことが無いように、前工程での仕様の確認、合意形成、連携する関連システムとの仕様調整などを行う
  - 社内だけでなく、顧客とのビジネスコミュニケーションも問題なくやりとり
    - 実施する作業や業務内容が顧客のビジネスにどのようなインパクトを与えるかを理解し、不明な点は確認
    - 顧客の事業やビジネス方針、プロダクトの強みや特徴などを理解して顧客とコミュニケーションを行うことができる
    - 顧客に直接質問をしたり、前向きに進める意見を出したり、ネガティブリスクについて共有

- 自学
  - 専門的な技術領域について社内外の勉強会やプログラミングブートキャンプ（プラハチャレンジ）に参加して、学びを深めている
  - 業務時間外を活用して、仕事に役立つ知識を書籍などから自主的に身につける
  - GitHub で定期的にコードをアウトプットし、コードを書く習慣が身についている
  - 週２の個人開発
    - 特定の専門領域だけでなく、関連する周辺の技術領域について、実際に手を動かし学習
    - デザインから行うことで UI 設計の実践。
    - 最新技術を採用し、実際に手を動かし学習することで最新技術をキャッチアップ
      - 今後、導入が必要となる新しい技術について調査・検証を行う
