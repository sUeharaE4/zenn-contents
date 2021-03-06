---
title: "エンジニアのスキルマップを考えてみた"
emoji: "🤔"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["スキルマップ", "スキル"]
published: true
---

# エンジニアのスキルマップを考えるきっかけ

2021 年は猛烈に忙しい一年で、チームメンバにもかなり負荷をかけてしまった中なんとか乗り切ってもらうことが出来ました。
ただ、仕事納めをしながら 2021 年でチームのスキルはどう成長したかを考えてみると各メンバそれぞれは成長したもののチームとしてはあまり成長させられなかったのではないか、そもそもチームのスキルってどう定義・評価すれば良いんだって後悔の念と疑問が生じました。
ここで言うチームの成長は特定のメンバがスキルを習得することではなく、習得したスキルをチーム内に展開でき特定のメンバ以外でも(多少の効率ダウンはあったとしても)スキルを活かした開発が出来るような状態になることを成長としています。個人の技能は高まったけど組織の技術にはなっていない状態です。

## 現状のチーム構成
私のチームは自社製品を開発しておりメンバは多くても 10 人未満程度の規模で開発しています。製品は顧客環境にインストールして動かす Web アプリです。我々がホスティングせず顧客環境に Web サーバを建てて動作させます。
私は開発リーダとしてユーザへのヒアリングや市場調査・企画に参加し、実現可否や開発方針の検討を担当しています。実際の開発は各メンバに依頼しています。開発は既存改修や新規開発が常時いくつか平行でおこなっています。チーム内で 2~4 人の小さなチームに分けて開発してもらうことが多いです。
フロントエンド・バックエンド開発に加えてセンサデータの収集加工なども行うため短期間でシステムを構築するために色々な言語のフレームワークやツールを組み合わせて開発をしています。どうしても分担して学びながら開発してもらうことになるのですが、その後チームの技術まで持っていけなかったなと反省しているところです。

# スキルマップをどう使うか
多くの言語やフレームワークを組み合わせてシステムを成立させる関係上、全員が全ての技術領域に精通することは出来ません。ただ、この開発はこの人しか出来ないという状態になってしまえばチームではなく単なる個人の集まりになってしまいますし、若手にはもっと広く使えるスキルを身に付けてもらいたいのにこの開発はその人しか出来ないとその人物の成長する機会を奪ってしまうことにもなるのでそれは避けたいと思っています。
なので各技術領域でメンバが持つスキルをランク付けして属人化の度合いを見えるようにし、各技術領域を複数のメンバが担当できるようにタスクをアサイン出来るようになる必要があります。

そこで IPA の IT スキル標準を参考にスキルマップを考えてみました。人事評価に使うことは考えていません(そういう立場でも無いですが)。チームの技術をどう成長させていくか考えるためのインプットとするので各メンバの差を積極的に表現することになるため人事評価には向きません。開発者が他者を自分より高く評価し目標にするためのものです。
年末年始に個人で考えた程度ではたたき台程度のものしかできなかったのでメンバと相談して改善していくところですが、公開することでより多くの方の声が集まったらよりチームのためになると思い公開することにしました。


:::details IPA の IT スキル標準
詳細は[公式](https://www.ipa.go.jp/files/000025745.pdf) を参照してください。

|レベル|説明|
|---|---|
|レベル7|プロフェッショナルとし てスキルの専門分野が確立し、社内外において、テクノロジやメソドロジ、ビジネスを創造し、リードするレベル。市場全体から見ても、先進的なサービスの開拓や市場化をリードした経験と実績を有しており、**世界で通用する**プレーヤとして認められます。|
|レベル6|プロフェッショナルとしてスキルの専門分野が確立し、社内外において、テクノロジやメソドロジ、ビジネスを創造し、リードするレベル。社内だけでなく市場においても、プロフェッショナルとして経験と実績を有しており、**国内のハイエンドプレーヤ**として認められます。|
|レベル5|プロフェッショナルとしてスキルの専門分野が確立し、社内においてテクノロジやメソドロジ、ビジネスを創造し、リードするレベル。社内において、プロフェッショナルとして自他共に経験と実績を有しており、**企業内のハイエンドプレーヤ**として認められます。|
|レベル4|プロフェッショナルとしてスキルの専門分野が確立し、自らのスキルを活用することによって、独力で業務上の課題の発見と解決をリードするレベル。社内において、プロフェッショナルとして求められる経験の知識化とその応用（**後進育成**）に貢献しており、ハイレベルのプレーヤとして認められます。スキル開発においても自らのスキルの研鑽を継続することが求められます。|
|レベル3|要求された作業を全て**独力で遂行します**。スキルの専門分野確立を目指し、プロフェッショナルとなるために必要な応用的知識・技能を有します。スキル開発においても自らのスキルの研鑽を継続することが求められます。|
|レベル2|**上位者の指導の下に、要求された作業を担当します**。プロフェッショナルとなるために必要な基本的知識・技能を有する。スキル開発においては、自らのキャリアパス実現に向けて積極的なスキルの研鑽が求められます。|
|レベル1|情報技術に携わる者に**最低限必要な基礎知識**を有します。スキル開発においては、自らのキャリアパス実現に向けて積極的なスキルの研鑽が求められます。|

:::

# スキルマップ
言語やフレームワーク単位で[このスプレッドシート](https://docs.google.com/spreadsheets/d/152Y8aAcLgwJLHyPyy3Y9u0KTF7slw4i91MY9H-dQGPY/edit?usp=sharing) の項目でスキルを評価しチーム全体でどのスキルがどのレベルまであるか、今後どの部分を強化していくか採用に頼るか検討するために使おうと思っています。
各レベルの判断基準はあまり明確に出来ていないのですが、そもそもチームによって基準は変わってくるとのでこれらの項目に加えて各チームでいくつかの項目を設けて一定数の項目を達成したらレベル認定するような運用が良いのではないかと思っています。もし運用してみた方がいらっしゃったらご意見や追加した項目をご共有いただけますと幸いです。

一応初版を下記に貼っておきますが、枠が小さくてやや見にくいのとスプレッドシートのほうが最新になるのでご注意ください。

:::details スキルマップ
レベルについては元々の IPA の数値に 10 かけてその間にいくつかのステップを設けています。
開発経験期間はあくまで一例です。1 年で十分スキルが身に付く案件もあれば期間が長くてもそれほど成長できない案件もあるので。
設計や要件定義は言語を問わない部分も多いので分けたほうが良いとも思っているのですが、量が多いのと分けて考えた結果レベル感が表現できず諦めました。

| レベル | 説明 | 備考 |
| --- | --- | --- |
| レベル70 | プロフェッショナルとし てスキルの専門分野が確立し、社内外において、テクノロジやメソドロジ、ビジネスを創造し、リードするレベル。市場全体から見ても、先進的なサービスの開拓や市場化をリードした経験と実績を有しており、世界で通用するプレーヤとして認められます。 |  |
| レベル60 | プロフェッショナルとしてスキルの専門分野が確立し、社内外において、テクノロジやメソドロジ、ビジネスを創造し、リードするレベル。社内だけでなく市場においても、プロフェッショナルとして経験と実績を有しており、国内のハイエンドプレーヤとして認められます。 |  |
| レベル50 | プロフェッショナルとしてスキルの専門分野が確立し、社内においてテクノロジやメソドロジ、ビジネスを創造し、リードするレベル。社内において、プロフェッショナルとして自他共に経験と実績を有しており、企業内のハイエンドプレーヤとして認められます。 |  |
| レベル45 | ・チームメンバのスキルレベルより少し高い開発をアサインしてサポートしつつ開発経験を積ませることが出来る。<br>・複数の技術やアーキテクチャから組織にあったものを選択することが出来る。<br>・経験の浅いメンバでも開発しやすいような仕組み(使いやすいAPIの用意やチームに合ったドキュメントフォーマットの整備・ルールの運用など)を用意しスケールしやすい状態を作ることが出来る。 | IPAのレベル4以上は組織によって考え方が大きく変わる可能性が高いのでザックリ。後進育成はしているもののリーダーとしてはまだまだだと思い 4 より上は自分が到達していなくて想像しにくいってこともあるので...。<br>組織にあった技術は例えばJavascriptエンジニアが社内に多ければなるべくJSで頑張る構成が良いみたいな組織内で集めやすい技術を採用しておくと人の異動に耐えやすいとかそういうイメージです。経験が浅いメンバが多いのに高い(または多くの)技術力を求められるような構成にしてしまうと優れた技術でも運用できなくなってしまう可能性もあります。 |
| レベル40 | プロフェッショナルとしてスキルの専門分野が確立し、自らのスキルを活用することによって、独力で業務上の課題の発見と解決をリードするレベル。社内において、プロフェッショナルとして求められる経験の知識化とその応用（後進育成）に貢献しており、ハイレベルのプレーヤとして認められます。スキル開発においても自らのスキルの研鑽を継続することが求められます。 | IPAの定義通り |
| レベル38 | ・仕様の確定に加え、顧客の潜在的な課題を見つけたり改善提案をしたり業務上の改善活動を効果的に行えるレベル。<br>・レビュアーとしてより高品質な実装を指導し改善させたり保守性や今後の展開を意識した実装を指導出来る。<br>・言語やフレームワークで使われるデファクトスタンダードな(またはそれに近しいくらいよく使われる)ツールを把握しチームに導入出来る。<br>・後進のスキルレベルを把握し自身のチームで実現可能なアーキテクチャ構成を選択しチームで実現出来る。 | 改善活動の効果的を評価するのが難しいですが、この辺はチームごとの考えが強く出るのでそのチーム内でこの改善助かったなと強く思えたら効果的で良いかと。<br>ツール導入は例えばフォーマッター使ったほうが良いって提案ではなくこのフォーマッターをこういう設定するとどんな効果が得られるから使ってくれみたいな実際に使わせるための導入手順や方法も用意してくれるのが下位レベルとの違いです。 |
| レベル35 | ・仕様の確定に加え、顧客の潜在的な課題を見つけたり業務上の改善活動を積極的に行えるレベル。<br>・レビュアーとして実装誤りだけではなくメンバの成長を意識したコメントをしたり自身が習得してきたスキルをチームのスキルへ還元しようと行動できる。<br>・実装する機会が与えられたら保守性を意識し技術負債が小さくなるように実装をすることが出来る。 | 改善活動はうまくいかなくても良いから積極的に行ってほしいって願望が強く出すぎている可能性があります...。時々やってくれるとかよりは意識してやってくれると嬉しい。<br>レベル30の要求された作業全て独力でという範囲がどこまでなのかが難しいですが、少なくとも単独で実行出来ることは独力で遂行出来るレベルは超えているのでチームに貢献してもらうように指導やお願いをしていくと良いのではないでしょうか。人それぞれ性格があるので貢献の方法は多々用意出来ると良いのではないでしょうか。みんなが改善活動が好きというわけではないしゴリゴリ開発して遅れそうなメンバのタスクを巻き取ったり、誰でも出来るような開発を若手にさせないでチャレンジングな開発に注力できるように雑多な部分を巻き取るとかそういう貢献も認めるべきだと考えています。 |
| レベル32 | ・レベル31に加え要求を整理・確認する際に後進も巻き込み後進にも経験を積ませることが出来る。<br>・レビュー以外でも後進の支援・指導を積極的に行うことが出来る。<br>・実装する機会が与えられたら要求された実装に加え既存の技術負債の返済にも協力してくれる(既存は絶対触らないみたいなルールがある場合は除く)。 | 組織によってはこのくらいのレベルからだんだん実装機会を与えられなくなることもあるでしょうけど、個人の特性で開発を重視したいメンバにはプロジェクトに余裕があれば開発に携われるようにしてあげられると意欲を大きく削ぐことは避けられると考えています。まぁちょっとした開発じゃ満足できないレベルとかになってるかもなのでなんとも言えませんが。 |
| レベル31 | ・曖昧な要求を整理・ステークホルダーに確認することで仕様を確定出来るレベル。独力でも要件定義を遂行出来るが、顧客の要求に上がっていない潜在的なニーズを見落とさないためにも上位者と相談は継続的に行わせたほうが良い。 | ステークホルダから要求を引き出すためにも情報を整理する力が重要だと思っています。これを完全ではないにしろ独力で出来ることがIPAの定めるレベル2と3の違いかなと。とはいえ1人で気付ける範囲には限界があるので上位者でも後進でも良いから相談しながら作業するべきだと考えています。 |
| レベル30 | 要求された作業を全て独力で遂行します。スキルの専門分野確立を目指し、プロフェッショナルとなるために必要な応用的知識・技能を有します。スキル開発においても自らのスキルの研鑽を継続することが求められます。 | IPAの定義通り |
| レベル28 | ・上位者と相談すれば自身のスキルで実現可能なアーキテクチャ構成を検討し、実装出来るレベル。<br>・言語やフレームワークの標準機能にも目を良く通し車輪の再開発を避け、既存の修正が出来る。 | ここでの実装は個人で完遂する必要はない(よほど小さいサービスなら個人でやっちゃっても良いが)。上位者と一緒に実装できれば良い。上位者抜きで後進たちと実装出来るのはもっと上レベルと評価してあげて良いでしょう。 |
| レベル25 | ・曖昧な要求から仕様を検討し上位者と相談すれば仕様を確定させて実装出来るレベル。レビューでは本質的でないミスに関する指摘は少なくなり品質や性能に関わる内容の指摘が中心になる。<br>・共通機能を開発してもらうときは使い勝手や今後の改修がしやすいかを気にしてレビューしたほうが安全。自分が使うシーンしか想定できていない状態で実装して別の人が使うときにグルーコードが長くなるような作りになっていることもまだ少しはある。 | このレベルになればある程度自然に出来るようになるでしょうけど、レビュアーの負荷を減らすためにプルリクの概要や確認すべき点を整理してレビュー依頼をしてくれるようになっていなかったらそういう指導をする必要がある。今後レビュアーになるときにどのようなところを気にするべきなのか早めに意識させることにもなるし、レビュアーとしてどこを重視するタイプなのかわかる。 |
| レベル22 | ・該当の言語で1年程度の開発経験があり、処理概要から実装方針を検討し上位者と相談すれば方針を確定させられるレベル。例えばSpringのDIコンテナなどフレームワークの機能も理解してきて類似機能の実装を参考に渡さなくても自力で機能選定が出来るようになってくる。<br>・該当の言語で年単位の開発経験があるが、利用するフレームワークは使ったことが無い場合もこのレベルで良いがFlaskは経験あるがDjangoはないなどある程度似たフレームワークの経験があればもう少し上でも良い。 | 自分を振り返ると1年でDIのありがたみを感じるようにはなれなかったけど、経験のさせ方次第では1年あれば十分だと考えています(すごい人が全体構成決めてベースを作っていたのでひたすら量産する担当だった。これはこれで量産体制を作るための勉強になりました)。色々な事情からバッドプラクティスな既存をある程度踏襲せざるを得ないようなシーンでもベストプラクティスではどうするか伝えて後進の成長に繋げることが大事だと考えています。<br><br>共通機能を実装してもらうときには前のレベル同様詳細な要求を与えてあげたほうが良いです。ある程度仕様を自力でも考えられるでしょうけど他の人が機能を使うときのことを想像するのが難しい段階です。 |
| レベル21 | ・詳細な要求や処理内容を元に設計を行い、上位者のレビュー修正を経て設計書を完成させられるレベル。例外系の見落としが多いのでまだまだ設計レビューは大変。<br>・該当の言語で数ヶ月開発経験がありある程度ボイラープレートを押さえられてきたレベル。Effectiveシリーズで紹介されるTipsのうち少なくとも10個程度は把握しているくらい。その言語をしっかり習得したいと考えているのであればEffectiveシリーズを勧めて少しずつ読んでもらうと良いかと。 | Effectiveシリーズはかなり濃厚なので年単位の時間をかけて業務で必要な部分を身につけるように言わないとこのレベルだとビビってしまうので注意です。 |
| レベル20 | 上位者の指導の下に、要求された作業を担当します。プロフェッショナルとなるために必要な基本的知識・技能を有する。スキル開発においては、自らのキャリアパス実現に向けて積極的なスキルの研鑽が求められます。 | IPAの定義通り |
| レベル18 | ・該当の言語で数週間程度の開発経験があり、基本文法は押さえていて処理概要があれば自分でメモレベルのシーケンスやフローチャートを作成して上位者にレビューしてもらえば実装を始められるレベル。ボイラープレートは部分的には知っているだろうがレビュー修正は覚悟しておいたほうが良い。徐々に書き方に関する指摘から性能や品質に関する指摘に割合がシフトしてくる。 | このくらいのレベルになれば上位者の実装をレビューさせて良いと考えています。実装誤りを探してもらうというよりは上位者の実装から書き方や考え方を学んでもらうためにレビューに参加してもらい、よくわからないところは質問してもらうことで実装が複雑な部分を見つけることも出来る。ただしよくわからないのが知識不足が起因している場合もあるのでこのレベルの人がわかりにくいと感じる実装が悪とは限らないので注意。 |
| レベル15 | ・2つ以上の言語(できればコンパイル言語とスクリプト言語を1つずつだと望ましい)の基本文法を習得している人物がほとんど使ったことのない言語で開発する場合に該当するレベル。言語の入門サイトを参照させれば開発出来るレベル。<br>・ボイラープレートは知らないのでPGレビューで多くの修正が必要になる前提でいたほうが良い。可能であればレビュー依頼を待たずともハマっていないか確認したほうが良いが、上位者が無理な稼働捻出をしてまでしなくても良い(作業者が自己判断で質問しに来る)レベル。 |  |
| レベル12 | ・趣味か自己学習で言語に入門したことがあるレベル。簡単なチュートリアルは実施したことがあるが何かの機能を作ったりはしていないか、文法に不安があるレベル。<br>・注意事項はレベル11と同様。レビュアーの負荷を減らすためにもリーダブルコードを授けたほうが良い。 |  |
| レベル11 | ・1つの言語の基本文法を習得している人物がほとんど使ったことのない言語で開発する場合に該当するレベル。仮にシーケンス図やフローチャートが既に用意できていても開発言語の基本を学んでもらったり説明しておいたほうが良いような状態。<br>・言語特有のボイラープレートも当然知らないのでPGレビューで多くの修正が必要になる前提でいたほうが良いし、レビュー依頼を待たずとも定期的にハマっていないか確認してあげる必要がある。 | 1言語習得してればシーケンスあれば大丈夫じゃない？と感じる方は、JavaやC言語を学んだあとに初めてBashに出会ったとかLinux育ちが急にWindowsのバッチを書かなければならなくなった時をイメージしてみてください。<br>Bashで変数に代入するときにスペースを入れてしまったりif でスペースを忘れたりしますよね。あの状態です。Bashをプログラミング言語と呼ぶかはここでは問題としません。あくまでイメージです。 |
| レベル10 | 情報技術に携わる者に最低限必要な基礎知識を有します。スキル開発においては、自らのキャリアパス実現に向けて積極的なスキルの研鑽が求められます。<br>※IPAが定める最低限必要な基礎知識はどの程度か難しいところですが、とりあえずGitの初歩的な操作(指示された通りブランチを作りCommit, Push, PullRequestを発行するくらい)が出来てUML図は読み書き出来る程度と想定します。 | IPAの定義通り |

:::