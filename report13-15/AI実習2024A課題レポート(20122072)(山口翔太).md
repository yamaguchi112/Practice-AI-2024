# AI実習2024　最終課題レポート 


## 各回のグループ討議の要約と個人ワーク
## [第13回～第15回]
## 最終課題
- **課題期間**：   2024/7/18(木)
- **課題提出期限**：　2024/8/7(水) 18:00

- ファイル名は、AI-2024A-Final-Report.md　（すべて半角英数記号）とすること
- 稀に、ファイル名にマルチバイト日本語を入れてGithubにFile Uploadが失敗するケースがあるため
  
-------------
　

<!-- 要 記述 -->

|クラス|学籍番号|  氏    名  |
|:-:|:-:|:-:|
| A |  20122072 |山口翔太   | 

-----
## レポートの作成手順 (マークダウン記法)
- マークダウン記法[^1][^2][^3][^4]でレポートを作成する
- テキストエディタ＋機能拡張をインストール：
 - VSCode  https://code.visualstudio.com/download#
 - 機能拡張(Markdown PDF, Markdown Preview Enhanced ) セットアップ
- ファイル名は、`AI実習2024A課題レポート(学籍番号)(学生氏名).md `
- 作成したらPDFファイル、HTMLファイルを変換生成する

#### マークダウン記法についてわかりやすい説明、Web情報
[マークダウン記法とは？](https://www.bing.com/videos/riverview/relatedvideo?q=%e3%83%9e%e3%83%bc%e3%82%af%e3%83%80%e3%82%a6%e3%83%b3%e8%a8%98%e6%b3%95&mid=4EE93F5EF42F9CAD0CCC4EE93F5EF42F9CAD0CCC&FORM=VIRE) 
[Markdown記法～基礎編～](https://qiita.com/miriwo/items/28d80f46c857de49f34b)
[マークダウン記法一覧](https://qiita.com/miriwo/items/28d80f46c857de49f34b)
[マークダウンの書き方](https://backlog.com/ja/blog/how-to-write-markdown/)

[^1]:(https://www.bing.com/videos/riverview/relatedvideo?q=%e3%83%9e%e3%83%bc%e3%82%af%e3%83%80%e3%82%a6%e3%83%b3%e8%a8%98%e6%b3%95&mid=4EE93F5EF42F9CAD0CCC4EE93F5EF42F9CAD0CCC&FORM=VIRE)マークダウン記法とは？
[^2]:(https://qiita.com/miriwo/items/28d80f46c857de49f34b) Markdown記法～基礎編～
[^3]:(https://www.sejuku.net/blog/77398)マークダウン記法一覧
[^4]:(https://backlog.com/ja/blog/how-to-write-markdown/)マークダウンの書き方

### 外部ツール画面の図式引用
- 本様式をひな型とする
- 様式中に、マークダウンのコメントとして
  　　`<!-- 要 記述　回答 -->` と記されている箇所は忘れずに適切な記述を加筆する
- 図やスクリーンショットを引用する場合、フォルダにまとめておく
- 1つのレポートにつき、1つのフォルダを用意する
- そのフォルダに、md, pdf,html,および, 引用で使用したjpg,png等ファイルをまとめて配置する
- $MR^3$で作成したRDFは、スクリーンショット画像として本文に取り込む
- $Protege$で作成したオントロジは、`OWL/XML Syntax` 形式で、`file名.owl`　として保存する
- $Protege$で作成したLODは、`RDF/XML Syntax` 形式で、`file名.owl`　と保存する
- $Sparql$のソースコードは、マークダウン形式に、引用によって記述する
```
  　Sparqlのクエリコードを　```sql  と ```　で囲み、クエリの実行結果も　``` ``` で囲む
```
### レポート提出方法 Githubのプライベートリポジトリにアップロード

- 2学年4学期の**API実習と同じ方法**
- Githubのアカウントを作成し、**Practice-AI-2024** という名称でプライベートリポジトリを作成
- そのプライベートリポジトリに、指導員のGithubアカウント= **keythrive**を招待する
- Githubのプライベートリポジトリに次の名前で、6つフォルダを用意する：
  - **report1-3**
  - **report4-6**
  - **report7-9**
  - **report10-12**
  - **report13-15**は、**report-Final**　に混ぜてよい
- 
- Githubのアカウント名、プライベートリポジトリ作成、6つのフォルダをつくったか？招待を完了したか？について、FORMSアンケートするので必ず回答すること。
- FORMSアンケートはこちら：
  - https://forms.office.com/r/6iMLLYjw1t
  
- FORMSアンケートに未回答の場合、レポートを取得する方法が確立しないので、必ず回答のうえレポート提出可能な状態にすること

- それぞれの提出期限までに、必要なファイル一式を当該フォルダにアップロードしておく
- 〆切時刻を過ぎた時点で自動的に, 全員のGithubプライベートリポジトリから、```git clone```などでファイルを一括ダウンロードする
- 提出が遅れるとダウンロードできず、未提出と判断される
- 真に止むを得ない事由で、提出期限が遅れる場合、事前にメールにて連絡・相談すること: 
- mailto:  **horikawa.keitaro@kaishi-pu.ac.jp** 
- 事前連絡なしに、期限を過ぎた場合、その課題レポートは未提出として採点しない
- Githubのアカウント登録、プライベートリポジトリ、ファイルアップロードが不明な場合は、必ず事前に確認・相談するか、すでに出来ている友達から教えてもらうこと

------------
## 課題レポートのまとめ方

- 直近のグループ実習3回分をまとめて1つのレポートを作成する
- 毎回休まずに出席して、グループ討論に積極的に参画する
- グループを代表して発表し、質疑応答、議論、メモを確実にとる作業が大切
- 自グループと他グループの発表をしっかり聴いて、議論模様を簡潔にまとめて報告する
- それぞれの回の全てのグループ発表、および、
- 学生と教員からの質疑コメントを要約する
- ここまではグループメンバ間の協力作業で、差異化要素はほとんどないことが予想される
- 自作の成果（RDF,オントロジ等）には極力 "FOAF,SKOS,DC"など共通語彙を適用する
- **個人の努力を差異化要素**として、さらに踏み込んだ検討・実習の成果を3回分の**個人演習**について報告してよい
- 3回で取り組んだ内容、理解を深めたことを独自レポートとして加筆可能
- 例えば、**作成したRDF,オントロジ,使用したLOD, 作成したSparqlクエリ,その他のAI手法やプログラムとの連携技、それらの分析・考察・所感**　など

### 本実習・課題レポートに取り組む意義
- 半年後、本実習を「適当にやり過ごした学生群」と、「真剣に打ち込んで突き詰めた学生群」に明確に分かれることが予想される
- 前者と後者とで、成長の差は著しく広がり、臨地実務実習IIの実習成果および企業担当者から評価が如実に変わる
- 1年後の今頃、就職活動の内々定数（場合によっては、転職ファストパスの数）が大きく変わることが見込まれる
  
--------
## 最終課題
- 第14回ー第15回「情報家電」オントロジを参考に、最終自作オントロジの作成と活用評価を報告する
- 必要な要件は下記のとおり：

- (1) 設計者（貴方）の立場：　新製品や新商品を購入検討中の顧客に対し、適切なアドバイスを提供するコンシェルジェ
- (2) 作成評価するオントロジとそのアプリの要件：　顧客からのどのような問合せ（クエリ）が考えられるか？　ユースケースを具体的に描いて、それに適切に答えられるための必要な知識・概念・語彙をオントロジとして設計する
- 例えば、白物家電（冷蔵庫、エアコン、洗濯機、掃除機、液晶TV）、スマートフォン、PC、タブレット、電気自動車、の買い替えを想定して、さまざまなニーズに応えるための知識を設計する
- 多数の製品・商品群がある中、数多の選択肢から、顧客が十分に満足する製品をどういう条件で絞り込むか？
- (3) 購入要件を満たす製品の絞り込みを可能とする　$Sparqlクエリ$の仕様設計
- 　クエリに整合した、概念・用語・語彙と、その関係整理を製品・製品バリエーション・要求仕様として表現する
- (4) 実際の具体的製品名(LOD)、代表的な属性・共通語彙を使ってオントロジに反映する
- (5) 実際にProtegeを用いたオントロジの作成、Sparqlの動作を確認
- (6) オントロジの評価：　購入要件に複数のバリエーションを用意して、複数パターンのクエリと結果の実例を示すこと。そのうえで、製品購入へのアドバイスの網羅性・精度・頻度を評価考察する
- オントロジを用いた推論は、クラスの同一性、排他性などによるクラス体系整理のレベルであるが、利用価値の高い$Sparql$や$Prolog$による述語論理の検討・提案ができれば加点要素とする
- また、個人作業の高度化の一環で、$Sparql$や$Prolog$の論理演算をDSLとして、他の言語から呼び出す形態で活用してもよい
- 更なる加点要素：Virtuosoを用いたRDFストア化および、Sparqlエンドポイントのローカル動作確認
  
--------------
## 最終課題の記載事項

### 作成したオントロジ名：対象とした新製品・新商品名
### 想定した顧客からの具体的質問、ユースケース事例
### Protegeを用いたオントロジの図式
- **protégé**にて作成された、オントロジファイル (.owl) 形式の成果物
- 画面スナップショット (.jpg, .png)
### Sparqlの実施例とその結果
実施1
ワイヤレスイヤホンで、ノイズキャンセリング・マルチポイント・マルチペアリングという機能を持っているものを検索するクエリ。
```sql
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX ns: <http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#>
SELECT ?イヤホン ?価格
WHERE {
  ?イヤホン a ns:イヤホン ;
            ns:price ?価格 ;
            ns:is-a ns:ワイヤレス ;
            ns:has-a ns:ノイズキャンセリング ;
            ns:has-a ns:マルチポイント ;
            ns:has-a ns:マルチペアリング ;
}
```
結果1
```
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#Elite_10	"23000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#Victor_HA-FX550T	"27000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#Technics_EAH-AZ80	"33000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#WF-1000XM5	"28000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#Victor_HA-A30T2	"9000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#MOMENTUM_True_Wireless_4	"43000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#AVIOT_TE-W1-PNK	"17000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#LinkBuds_S_WF-LS900N	"18000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#WF-C700N	"12000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#WF-1000XM4	"25000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#PerL_Pro_AH-C15PL	"32000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#Technics_EAH-AZ40M2	"15000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#SOLID_BASS_ATH-CKS30TW+	"12000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#Technics_EAH-AZ60M2	"24000"^^<http://www.w3.org/2001/XMLSchema#integer>
```
実施2
ヘッドホンに対して、価格が60000以下で、接続方式が有線とワイヤレスのどちらでもできるという条件をFILTERでかけ、aptX_Adaptiveというコーデックに対応しているヘッドホンを調べ、ヘッドホンと価格を表示させるクエリを作成した。
```sql
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX ns: <http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#>
SELECT DISTINCT ?ヘッドホン ?価格
WHERE {
  ?ヘッドホン a ns:ヘッドホン ;
              ns:price ?価格 ;
              ns:has-a ns:aptX_Adaptive ;
             ns:is-a ?接続方式 .
  ?接続方式 a ns:接続方式 .
  FILTER(?接続方式 = ns:有線 || ?接続方式 = ns:ワイヤレス)
  FILTER(?価格 <=60000)
}
```
結果2
```
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#AONIC_50_GEN_2_SBH50G2-BK-J	"45000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#MOMENTUM_4_Wireless	"41000"^^<http://www.w3.org/2001/XMLSchema#integer>	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#Px7_S2e	"50000"^^<http://www.w3.org/2001/XMLSchema#integer>
```
実施例3
UNION句を使用して、検索条件の和集合を表示させた。BIND句を使用して、UNION句を使用して検索したの区別がつくようにしている。
```sql
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX ns: <http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#>
SELECT DISTINCT ?イヤホン ?価格 ?連続再生時間 ?機能 ?装着タイプ
WHERE {
  {
    ?イヤホン a ns:イヤホン ;
              ns:price ?価格 ;
              ns:continuousPlaybackTime ?連続再生時間 ;
              ns:has-a ns:aptX_Adaptive ;
              ns:is-a ?装着タイプ .
    ?装着タイプ a ns:装着タイプ .
    BIND("aptX_Adaptive" AS ?機能)
  }
  UNION
  {
    ?イヤホン a ns:イヤホン ;
              ns:price ?価格 ;
              ns:continuousPlaybackTime ?連続再生時間 ;
              ns:has-a ns:LC3 ;
              ns:is-a ?装着タイプ .
    ?装着タイプ a ns:装着タイプ .
    BIND("LC3" AS ?機能)
  }
}
```
結果
```
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#MOMENTUM_True_Wireless_4	"43000"^^<http://www.w3.org/2001/XMLSchema#integer>	"7.5h"	"aptX_Adaptive"	http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#カナル型	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#Ultra_Open_Earbuds	"33000"^^<http://www.w3.org/2001/XMLSchema#integer>	"7.5h"	"aptX_Adaptive"	http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#耳かけ型	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#EarFun_Air_Pro_3	"6500"^^<http://www.w3.org/2001/XMLSchema#integer>	"9h"	"aptX_Adaptive"	http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#カナル型	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#QuietComfort_Ultra_Earbuds	"26000"^^<http://www.w3.org/2001/XMLSchema#integer>	"6h"	"aptX_Adaptive"	http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#インナーイヤー型	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#PerL_Pro_AH-C15PL	"32000"^^<http://www.w3.org/2001/XMLSchema#integer>	"8h"	"aptX_Adaptive"	http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#カナル型	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#MOMENTUM_True_Wireless_4	"43000"^^<http://www.w3.org/2001/XMLSchema#integer>	"7.5h"	"LC3"	http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#カナル型	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#WF-1000XM5	"28000"^^<http://www.w3.org/2001/XMLSchema#integer>	"12h"	"LC3"	http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#カナル型	
http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#LinkBuds_S_WF-LS900N	"18000"^^<http://www.w3.org/2001/XMLSchema#integer>	"9h"	"LC3"	http://www.semanticweb.org/yamaguchi/ontologies/2024/6/untitled-ontology-80#カナル型
```
### 作成したオントロジの規模、その活用規模を表す数値を列挙する
- 設計したクラスの数
- 設計したインスタンスの数
- 設計したプロパティの数
- .owlファイルの行数 (XMLファイルの行数をwcでカウント、テキストエディタで確認)
- Sparqlのクエリ数　（クエリ実行のパターン数）
- トータルのSparql行数

|定量パラメタ | 数値 |
|-|-|
|クラス数|11|
|インスタンス数|103|
|プロパティ数|7|
|.owl行数|2093|
|Sparqlクエリ数|3|
|Sparql行数|59|

### 分析・評価・考察
- 選定理由、なぜこのテーマを選定したか？　
- 深く専門的な知識の所在
- ユーザへの寄与・貢献、ユーザにどのように活用してほしいか
- 差異化要素、強みと特徴点
- 共通語彙、プロパティの使い方で自ら発見した知見
- クラスとインスタンスの違いで発見した知見
- オントロジ設計で貫いたポリシー
- 創意工夫のポイント
- オントロジエディタの使い方で習得した技法
- 作業を通じて得られた知見

### 評価の観点
- 独創性と丁寧な設計
- 差異化性（既存と異なる付加価値）
- 深さ　（表面的でなく、知識に深みがある）
- 設計思想　（どのような思いでデザインしたか）
- 見通しの良さ、設計のわかりやすさ
- is-a, has-a, 主語・述語・目的語の簡明さ
- 共通語彙の活用度
- Sparqlの量・質・複雑さ・多様さ
  

### AI実習全体を振り返り、考察・分析・展望
- AI実習（知識工学系）で得た知見を今後どのように活用するか  
- 具体的な知識データの活用方法
- 機械学習、生成系AIとの効果的な連携方法

<!--  自由記述欄 -->
###　振り返り
AI実習を通して、RDFやXMLを用いた知識の表現方法を学ぶことができた。また、これらを実際に使って知識を表現していく際には、どのような要件が必要になってくるのかを講義を通して学ぶことができた。また、物同士の関連性などを調べる際に、RDFを活用したいと考える。また、SPARQLの構文についても学ぶことができたため、これを活用して、より複雑な条件でオントロジに対して検索をかけたり、データの特徴について、分析する際に活用していきたいと考える。また、オントロジやRDFで定義された概念や情報を利用することで、機械学習モデルに必要な特徴量を生成するなどの連携方法があるのではないかと考える。

--------
### 第13回グループ課題の要約・整理

|回数|グループ名|発表者|発表内容|発表への質疑・コメント|
|:-:|:-:|-|-|-|
|13|**青雲の志**|竹田|家電のクエリについて作り始めたため、本日はクエリについてはあまりできていない。データプロパティとして、URLなどを記入。扇風機について作ったが、役割分担して作業を行なった。|本日の講義では、複雑なクエリを作成し実行するという要件であるため、役割分担して複雑なクエリをできるようにしてほしいという質問が出た。|
|13|**鵬程万里**|小柳・小出・安達|小柳：山についてのクエリを作成。地域に絞って１５００メートル以上で検索した。小出：ポケモンについてのタイプを表示する際に、フィルターをかけて、タイプを表示させることができた。特定の事務所に所属している俳優の名前を表示させるクエリを作成。また、俳優の主な出演作品を絞って検索するクエリを作成した。||
|13|**金剛不壊**|相場|ウィキデータを使って、プログラミング言語について検索。プログラミング言語の中から、C言語から影響を受けている言語について検索。2000年以降というフィルターをかけている。その言語で書かれたソフトウェアについて書きたかったが、うまくできなかった。|意図した結果は出ているかという質問が出たが、出ていると言っていた。|
|13|**破竹の勢**|倉石|ウィキデータに対してクエリを送信。プログラムを実行すると、ランダムなサブジェクトが出てきて、サブジェクトに対して、述語がでてくる。それらを選択していくことで、ウィキデータを探索するようにできたら良いなという風にプログラムを作成。|対話的に絞り込んでいくということはいいことだと思う。|
|13|**磐石之固**|加藤|ポケモンについてのオントロジに対して、クエリを作成。特性・進化方法を追加して、複雑なクエリを作成できるように工夫。特性で絞り込んで、ナンバー順に表示させるというクエリを作成。また、進化方法で絞り込んで検索するクエリを作成。|ORを使えばもう少し複雑なクエリにして、複数の対象を検索することができたのではないかということが言われていた。|
|13|**飛龍在天**|大竹|ウィキデータクエリでポケモンについて検索。第９世代までについてのポケモンから、世代別でポケモンについて絞り込みをした。第何世代のポケモンかという点と、No.と、名前について検索。|自分が深く知っているものに対して検索するのは良いと思うと述べていた。|

--------
### 第14回グループ課題の要約・整理

|回数|グループ名|発表者|発表内容|発表への質疑・コメント|
|:-:|:-:|-|-|-|
|14|**青雲の志**|発表なし|||
|14|**破竹の勢**|発表なし|||
|14|**飛龍在天**|大竹|スピーカーのオントロジを作成した。クラスとしてメーカーや機械の情報を設定している。連携機能がついているかなどを今後追加していきたいと考えている。どの層に向けての商品なのかを分けて制作していこうと考えている。スパークルの検索はスピーカーを買いに来た際にイヤホンやマイクが欲しくなることを想定しているためそれに伴った情報を追加していきたいと考えている。|コメント：お風呂で使えるスピーカーの基準の情報を入れたら検索が可能になるためありがたい。スマートスピーカーの電力の情報も記述できたら良いと思う。|
|14|**鵬程万里**|発表なし|||
|14|**金剛不壊**|ロジャー|開志ラボにある機器のオントロジを作成。自動的な機械とマニュアル的な機械の二つを分類した。今後はHTMLやJSを利用してデータの検索ができるようにしたいと考えている。|Q,自動的なものとマニュアル的なものに分けたとあるが、人の手で動かすものと自動的に動かすものという認識であっているか。A,実際に手を動かして行うものなので作業自体の方法によって変えている。A,どういうスパークルを考えたか。Q,クラスを出してどういったインスタンスがあるのかということや、インスタンスからどのようなクラスがあるのかということを調査するもの。|
|14|**磐石之固**|五十嵐寛人、池田、駒木根|五十嵐→イヤホンのオントロジを作成した。イヤホンの種類、特徴、機能などをクラスに設定した。スパークルでの検索はAppleの製品を検索すると価格などの情報を表示する。また、今後はサイズや色などの情報を入れていきたいと考えている。池田→カメラのオントロジを作成した。メーカー、価格、ボディ色、画素数、レンズマウントなどの情報を入れる。クラスとしてカメラの名前、カメラの情報を入れていく。駒木根→冷蔵庫のオントロジを作成した。ユーザーはお金持ちで奥さんが料理好きな素人を想定している。クラスとした、メーカー、昨日、色、価格などを設定している。スパークルの検索では価格を考慮せずに検索をかけることを想定している。|Q,プロの場合はどのようにスパークル検索を行うのか。A,動物を撮る場合はブレ防止などが重要なので、その段階ごとに検索をすることを想定している。Q,価格以外に選ぶ要素はあるのか。A,冷蔵庫の機能で選べるようにする。また、is-a,has-a関係をしっかり記述する。|

--------
### 第15回グループ課題の要約・整理
 
|回数|グループ名|発表者|発表内容|発表への質疑・コメント|
|:-:|:-:|-|-|-|
|15|**青雲の志**|竹田|モニターとその周辺の機器についてのオントロジ。モニターとモニターアームについてオントロジに入力できている。データプロパティを充実させ、モニターの重量・解像度などを入力できるようにした。SPARQLで保証期間が2年以上で、長い順に表示させるというクエリを作成。|複合検索ができているかという質問について、複数の条件を指定して検索することができているのでできているのではないかと述べた。プロパティを複雑にしないと検索の際に、絞り込みがしづらいので良いのではないかということを言っていた。|
|15|**破竹の勢**|倉石|キーボードについてのオントロジ。キーボードの配列やスイッチのタイプなど複雑であるため、奥が深いのでクラスが複数できた。想定するユースケースとしては、細かく検索できるようにしたかったため、素材などについても検索できるようにした。クエリの方はまだできていない。|キーキャップに重さがあり、グラム数によって検索できるのかという質問について、現在は検索できないのでオントロジに追加したいと考えている。ゲームで、キーボードが両手だけでは足りないので、足でも操作できるキーボードがあるのかという質問について、キーボードは手で操作するものだと考えているので、知らないと答えていた。|
|15|**飛龍在天**|大竹・川崎・阿部|大竹：オーディオ機器についてのオントロジ。ブランドをクラスに持ってきた。現在は、クエリ検索が軽くできて、フィルターとしてオーディオ機器のタイプで検索できる。複合検索できるようにしていきたいと考えている。阿部:スマホについてのオントロジ。IOSとアンドロイド。複合条件を入れて検索できるようにしていきたいと述べた。川崎:スマホについてのオントロジ。RAMとROMで検索できるようにした。|スマホについて被っていたが、どのように差別化するのかという質問について、発売日などを追加していきたいと考えている。|
|15|**鵬程万里**|安達|コスメについてのオントロジ。アイシャドウに特化したオントロジを作成。人間の肌は４つのタイプに分けることができ、その肌のタイプに合ったアイシャドウを検索できるオントロジにしたいと考えて作成した。ブランド・アイシャドウの種類・パーソナルカラーなどにクラスを分けた。型番ごとに向いているパーソナルカラーと関連づけていくことができたら良いなと考えている。|肌のタイプについて、どのようなものかという質問について、それぞれ説明してくれた。ブランドの発祥国を３つに分けた理由として、有名なコスメブランドがそれぞれ３つの国にあると考えたため。|
|15|**金剛不壊**|ロジャー|kaishi LABのための検索エンジン。管理者のためのもの。管理者がものについての情報を得られるようにする。実際に機械を検索することができて、それらについての詳細を見ることができるようになっている。|ハンダゴテについて検索できるかということについて、現在は入っていないが今後入れるつもりだと答えていた。これは、今ある開志ラボの機械が出るのかという質問について、そうだといっていた。また、カテゴリと商品のブランドなどについてボタンで検索できるようにしたいと考えている。|
|15|**磐石之固**|加藤・五十嵐|加藤:たこ焼き機について。商品名・メーカーのインディビジュアルを描いた。コメントで検索したい単語を絞り込んで検索できるようにしたいと考えた。五十嵐:イヤホンのオントロジ。クラスが多くて見にくかったため、減らした。検索して、つながりが見れるようにした。sparqlでフィルターをかけれるようになった。|たこ焼き機について、特徴的な部分（長所）からの検索をできるようにしたいということを考えている。重さや音質などで検索できるようにしたいと考えている。|

--------
### [自己成長、成果、上位成績に向けて]　個人成果の報告　
このテーマを選んだ理由として、イヤホン・ヘッドホンにはさまざまな要素があり、人によって重要視する要素が違うため、それらの要素をオントロジに入れることで、イヤホン・ヘッドホンを買う人にとって有用なオントロジを作成できるのではないかと考えたからである。専門的な知識であるコーデックや防塵、防水についても記入し、コメントでわかりやすくした。ユーザには、イヤホン・ヘッドホンを購入する際に、さまざまな要素から絞り込みして条件に合ったものを検索できるので、絞り込みをして購入の際の参考にしてほしいと考える。差異化要素として、イヤホン・ヘッドホンが防水や防塵にどの程度対応しているのかという点について、オントロジを使って検索できるという点である。また、複数の要素を、イヤホン・ヘッドホンの情報として、関連づけてあるため、さまざまな複合条件による検索が可能であるという点が、差異化要素である。工夫した点として、性能に関する情報をオントロジに多く記入したことである。これによって、性能の面からさまざまな条件で、イヤホン・ヘッドホンについての検索ができるようになっている。クラスとインスタンスとの違いで発見した知見として、クラスの中には、そのクラスをより詳しく分けたものを入れるということがわかった。たとえば、イヤホンというクラスには、インスタンスとして、イヤホンの名称を入れるべきということについて理解することができた。

--------
## 注意事項
- 直近3回分の個人演習と毎回のグループ課題の実施結果について、
- 学生ごとの個人のレポートとする
- 他の学生のレポートをコピー＆ペーストしたことが発覚した場合、**不正行為とみなし 、規程に基づく懲罰適用の可能性があるので絶対にやってはいけない**
