## 魔法少女アイ ～データのそばに、魔法を。～

![扉絵](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-front-01.png)

![このマンガについて](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-front-02.png)

<details>
<summary>「このマンガについて」をテキストで読む</summary>

**このマンガについて**

このマンガについて

本作は、ベクトル検索からRAG（検索拡張生成）、AIエージェントといった話題を「データのそばに、AIを」という考え方を中心に魔法の世界に例えて解説したファンタジーマンガです。

前作『【マンガ】はじめてのインデータベースAI～ベクトル検索・RAGからAIエージェントまで～（コミカライズ版）』（副題「データのそばに、AIを。」）では、新人エンジニアの青山アイと先輩の神宮寺がAIを活用した保守サポートシステムを設計していく物語でした。この魔法少女編では、この物語を魔法の世界に例えて、新米魔法少女アイが、師匠の魔導士・神宮寺の助けを借りながら受付の水鏡による相談を支える魔導システムを設計する技術ファンタジーとして再構成しています。

前作の続編ではなく単体の作品としてお楽しみいただけるものです。

このマンガの内容は原作者個人の経験・見解であり所属する日本オラクルを代表するものではありません。

</details>

前作マンガ：『[【マンガ】はじめてのインデータベースAI～ベクトル検索・RAGからAIエージェントまで～（コミカライズ版）](https://qiita.com/yuji-arakawa/items/1c6d0ae4400ca2b4bae3)』（副題「データのそばに、AIを。」）

原作：『[はじめてのインデータベースAI～ベクトル検索・RAGからAIエージェントまで～](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960)』

人物・場面に画像生成AIを用い、文字・図・コードは別途組版しています。このマンガの制作に使用した [Manga Generator](https://github.com/stockedge/manga-generator) を公開されている月森ナギ様に感謝します。

## プロローグ　新米魔法少女、水鏡に立つ

![プロローグ 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-01.png)

![プロローグ 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-02.png)

![プロローグ 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-03.png)

![プロローグ 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-04.png)

![プロローグ 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-05.png)

![プロローグ 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-06.png)

![プロローグ 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-07.png)

![プロローグ 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-08.png)

![プロローグ 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-09.png)

![プロローグ 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-10.png)

![プロローグ 11コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-pro-11.png)

<details>
<summary>プロローグの会話をテキストで読む</summary>

**プロローグ 1コマ目**

**アイ：** データのそばに、魔法を！ マジカル・インデータベース！

**プロローグ 2コマ目**

**アイ：** 王立サポートギルド、新米魔法少女のアイです！ ご相談をどうぞ！

**プロローグ 3コマ目**

**ミラ：** 星見の塔のミラです！ 塔の魔導炉の管理盤が開かないんです！ 今夜は流星群なのに！

**ガルド：** 竜騎士団団長、ガルドだ！ うちの契約で、砦まで来てもらえるのか！

管理盤が開かない

砦まで来てもらえるか

**プロローグ 4コマ目**

**アイ：** は、はい！ えっと、すぐ確認しますので、少々お待ちください！

**プロローグ 5コマ目**

**ガルド：** おい、今、よその塔が見えたぞ

**アイ：** わわっ、ごめんなさい！

**プロローグ 6コマ目**

**アイ：** 神宮寺師匠！ 起きてください！

**プロローグ 7コマ目**

神宮寺　ギルドの上級魔導士。アイの師匠

**神宮寺：** ……アイ。お客さまの話は、混ぜてはいけないよ

**プロローグ 8コマ目**

**神宮寺：** 君に、サポート魔導システムの設計を任せる

**アイ：** わたしが!? ……やります！ まずは無詠唱魔術で、ぱぱっと！

**プロローグ 9コマ目**

**神宮寺：** その前に。誰の、どんな仕事をサポートするのかを考えよう

**アイ：** 水鏡番が、手順を探すこと。それから、契約で何ができるかを確かめること！

**プロローグ 10コマ目**

**アイ：** ……ところで師匠、その手綱は？

**神宮寺：** いつか使う

**プロローグ 11コマ目**

**ハルシーネ：** わたくしは虚言の魔女ハルシーネ。答えなんて、それっぽければいいのですわ！

魔法少女アイ ～データのそばに、魔法を。～

</details>

## 第1話　ただ一つの真実の図書館

![第1話 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-01.png)

![第1話 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-02.png)

![第1話 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-03.png)

![第1話 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-04.png)

![第1話 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-05.png)

![第1話 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-06.png)

![第1話 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-07.png)

![第1話 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-08.png)

![第1話 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-09.png)

![第1話 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-10.png)

![第1話 11コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c1-11.png)

<details>
<summary>第1話の会話をテキストで読む</summary>

**第1話 1コマ目**

**アイ：** 手順の巻物は検索の塔へ、契約の石板はこっちの金庫へ。別々にしまって整理整頓です！

**神宮寺：** では、契約が変わったら？

**第1話 2コマ目**

**アイ：** 両方に書き写します！

**第1話 3コマ目**

**コピーゴーストA：** 竜騎士団は解約済みでーす

**コピーゴーストB：** いや、契約中でーす

**第1話 4コマ目**

**コピーゴーストC：** 最新？ 知らなーい

**ガルド：** 誰が解約したと!?

**第1話 5コマ目**

**アイ：** な、なにこれ!?

**神宮寺：** 写したあと、置き去りにされた分身の幽霊。コピーゴーストだ

**第1話 6コマ目**

**神宮寺：** 別の場所へ写すと、契約の変更や、取り下げた手順まで、ずっと写し直し続けないといけない

**第1話 7コマ目**

**神宮寺：** だから、手順の巻物も契約の石板も、この一つの図書館にしまう。ここが『ただ一つの真実の図書館』だ

**第1話 8コマ目**

**アイ：** つまり、ここにしまえば、いつでも 最新の石板と突き合わせられるってことですね！

**神宮寺：** そう。手順は意味で探す。現地保守を頼めるかは、契約の条件で調べる。性質の違う問いを、一つの図書館の中で組み合わせられる

**第1話 9コマ目**

**コピーゴーストA：** 最新、まぶしーい！

**第1話 10コマ目**

**ハルシーネ：** わたくしのかわいい手下たちが！ ……ふん、今日のところは見逃してさしあげますわ

**第1話 11コマ目**

**アイ：** あの人、プロローグでも……誰ですか？

**神宮寺：** 虚言の魔女。もっともらしい話で、水鏡の相談をかき回す。そのうち嫌でも会うよ

</details>

## 解説：第1話の種明かし

![第1話の種明かし 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t1-01.png)

![第1話の種明かし 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t1-02.png)

![第1話の種明かし 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t1-intro.png)

![第1話の種明かし 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t1-03.png)

![第1話の種明かし 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t1-04.png)

![第1話の種明かし 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t1-05.png)

![第1話の種明かし 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t1-06.png)

[1. 文書の意味検索と業務データの照会を組み合わせる](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#1-%E6%96%87%E6%9B%B8%E3%81%AE%E6%84%8F%E5%91%B3%E6%A4%9C%E7%B4%A2%E3%81%A8%E6%A5%AD%E5%8B%99%E3%83%87%E3%83%BC%E3%82%BF%E3%81%AE%E7%85%A7%E4%BC%9A%E3%82%92%E7%B5%84%E3%81%BF%E5%90%88%E3%82%8F%E3%81%9B%E3%82%8B)

<details>
<summary>第1話の種明かしの会話をテキストで読む</summary>

**第1話の種明かし 1コマ目**

**アイ：** 神宮寺さん、さっきの『ただ一つの真実の図書館』って……

**神宮寺：** うん、種明かしをしよう

**第1話の種明かし 2コマ目**

| 魔法の世界 | 実際の技術 |
| --- | --- |
| ただ一つの真実の図書館 | コンバージド・データベースOracle AI Database |
| 手順の巻物 | 保守文書の表 |
| 契約の石板 | 契約の表 |
| コピーゴースト | 複製先の古いデータ |

データの正本を一か所に置く（Single Source of Truth）

**第1話の種明かし 3コマ目**

製品

Oracle AI Database

業務表も、文書も、ベクトルも。一つのDBで

**第1話の種明かし 4コマ目**

性質の違う二つの問い

| 魔法の世界 | 実際の技術 |
| --- | --- |
| 手順を探す | 意味が似ている文書の検索（ベクトル検索） |
| 現地保守を頼めるか | 契約の条件の照会（SQL） |

**第1話の種明かし 5コマ目**

**アイ：** コピーゴーストの正体は……

**神宮寺：** 別の検索基盤へ写したデータだよ。契約の変更や文書の公開取消を、写した先へ反映し続けないといけない

複製すると同期が要る 変更・公開取消も

**第1話の種明かし 6コマ目**

**アイ：** 一つの図書館、つまりデータベースの中なら、写さずに、元の契約の表とそのまま突き合わせられるんですね

**神宮寺：** そう。SQLのJOINやEXISTSで、文書の検索と契約の照会を組み合わせる

写さずに元の表を参照 JOIN・EXISTSで組み合わせる

原記事「1. 文書の意味検索と業務データの照会を組み合わせる」

**第1話の種明かし 7コマ目**

**アイ：** コピーゴーストは、同期の遅れだったんですね

**神宮寺：** あの例えは、なかなかの出来だった

</details>

## 第2話　意味を読む精霊

![第2話 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-01.png)

![第2話 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-02.png)

![第2話 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-03.png)

![第2話 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-04.png)

![第2話 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-05.png)

![第2話 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-06.png)

![第2話 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-07.png)

![第2話 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-08.png)

![第2話 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-09.png)

![第2話 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-10.png)

![第2話 11コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-11.png)

![第2話 12コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-12.png)

![第2話 13コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-13.png)

![第2話 14コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c2-14.png)

<details>
<summary>第2話の会話をテキストで読む</summary>

**第2話 1コマ目**

**アイ：** ミラさんの相談札なのに、何も出てこない……！

**第2話 2コマ目**

**神宮寺：** ミラさんからは『管理盤』と聞いているが、巻物では『制御陣』と書かれているね

管理盤

第一　制御陣に入れないとき

**第2話 3コマ目**

**アイ：** 同じ話なのに、言葉が違うと見つからない……！

**第2話 4コマ目**

**神宮寺：** 文字が同じかではなく、意味が似ているかで探そう

**アイ：** 意味を読める精霊なら、山の向こうの精霊の塔にいます！巻物を全部運んで、読んでもらいましょう！

**神宮寺：** よし、頼もう

**第2話 6コマ目**

**神宮寺：** 精霊は巻物を読んで、その意味を『概念の矢』にする

**第2話 7コマ目**

**アイ：** 巻物の矢と、相談札の矢が届きました！ 読み終えた巻物も一便、戻りました！

**第2話 8コマ目**

**神宮寺：** 矢が指すのは、意味の星空の一点だ。意味が似ている巻物ほど、矢の向きが近い

**アイ：** ミラさんの星図みたい！

第一　制御陣に入れないとき

管理盤の明かりが消えたとき

飛竜舎のそうじ

**第2話 9コマ目**

**神宮寺：** 書架には、巻物と矢を並べてしまう。答えに使うのは、巻物の本文だからね

**第2話 10コマ目**

**神宮寺：** 方角の羅針盤で、相談の矢と向きが近い矢を探す

**第2話 11コマ目**

**アイ：** ……あった！ 手順の巻物、第一！

**第2話 12コマ目**

**アイ：** 見つかった！ あとは、塔に預けた残りの巻物と相談札を返してもらえば……

**第2話 13コマ目**

**神宮寺：** あっ、そんなに急いだら……！

星見の塔 管理盤が開かない

</details>

## 解説：第2話の種明かし

![第2話の種明かし 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t2-01.png)

![第2話の種明かし 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t2-02.png)

![第2話の種明かし 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t2-intro.png)

![第2話の種明かし 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t2-03.png)

![第2話の種明かし 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t2-04.png)

原記事（第1節）：[ベクトル検索は文字の一致だけでは拾えない候補も探してくれる](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#%E3%83%99%E3%82%AF%E3%83%88%E3%83%AB%E6%A4%9C%E7%B4%A2%E3%81%AF%E6%96%87%E5%AD%97%E3%81%AE%E4%B8%80%E8%87%B4%E3%81%A0%E3%81%91%E3%81%A7%E3%81%AF%E6%8B%BE%E3%81%88%E3%81%AA%E3%81%84%E5%80%99%E8%A3%9C%E3%82%82%E6%8E%A2%E3%81%97%E3%81%A6%E3%81%8F%E3%82%8C%E3%82%8B)・[ベクトル検索の処理概要](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#%E3%83%99%E3%82%AF%E3%83%88%E3%83%AB%E6%A4%9C%E7%B4%A2%E3%81%AE%E5%87%A6%E7%90%86%E6%A6%82%E8%A6%81)

<details>
<summary>第2話の種明かしの会話をテキストで読む</summary>

**第2話の種明かし 1コマ目**

| 魔法の世界 | 実際の技術 |
| --- | --- |
| 精霊の塔へ運ぶ | 外部の埋め込みAPIへ送る |
| 意味読みの精霊 | 埋め込みモデル |
| 概念の矢 | ベクトル |
| 意味の星空 | ベクトル空間 |
| 方角の羅針盤 | VECTOR\_DISTANCE（COSINE） |
| 相談札の言葉 | 質問文 |

**第2話の種明かし 2コマ目**

**アイ：** 羅針盤で矢の向きを比べたのは……

**神宮寺：** 問いと似ている巻物を探している。Oracle AI Database の AI Vector Search で、ベクトルの距離を比べるんだ。向きが似ていれば、コサイン距離は小さい。つまり似ている

意味が似ると、向きが近い COSINE距離で並べる

**第2話の種明かし 3コマ目**

Oracle AI Databaseの機能

AI Vector Search

ベクトルの距離を使い、意味の似た文書を検索

SQLで検索

ベクトル列

ベクトルの近さ

**第2話の種明かし 4コマ目**

**神宮寺：** 巻物と矢を並べてしまったのは、本文とベクトルを両方保存するためだ。ベクトルだけから本文は復元できないからね

本文とベクトルを保存 本文は本文として読む

**第2話の種明かし 5コマ目**

**アイ：** あの『落とし物』は……？

**神宮寺：** 外部の埋め込みAPIへ、文書や質問を送るたとえだよ。埋め込みモデルをDBの中へインポートすることもできる。次の話で紹介しよう

外部APIでベクトル化 次回：モデルをDBへ

</details>

## 第3話　精霊を図書館に招け

![第3話 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-01.png)

![第3話 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-02.png)

![第3話 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-03.png)

![第3話 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-04.png)

![第3話 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-05.png)

![第3話 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-06.png)

![第3話 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-07.png)

![第3話 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-08.png)

![第3話 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c3-09.png)

<details>
<summary>第3話の会話をテキストで読む</summary>

**第3話 1コマ目**

**ガルド：** ……星見の塔の管理盤が開かない？ なぜ、よその相談がうちの砦に降ってくる

**アイ：** わあああ、回収ー！

**第3話 2コマ目**

**神宮寺：** 全部を外へ運べば、運ぶたびに落とす心配がつきまとう

**神宮寺：** 巻物を運ぶのではなく、精霊のほうに来てもらおう

**第3話 3コマ目**

意味読みの精霊　どの国の言葉でも、意味を読み取って『概念の矢』を放つ

**神宮寺：** 意味読みの精霊に、図書館の中に住んでもらおう

**第3話 4コマ目**

**アイ：** 塔の精霊さん、お引っ越し完了です！

**第3話 5コマ目**

**神宮寺：** 今度は、図書館の中で巻物を読んでもらおう

**第3話 6コマ目**

**アイ：** 精霊さん、これからも巻物に矢をお願いします！

**神宮寺：** 同じ精霊だから、届いている矢はそのまま使えるよ

**第3話 7コマ目**

**アイ：** 図書館の中でも、相談札に矢を！

**第3話 8コマ目**

**アイ：** 精霊さんが図書館の中にいるから、巻物を外へ運ばなくていいんですね。もう落とさない！

**神宮寺：** 精霊が働く分、図書館の力も使う。どれだけ働けるかは、自分の図書館で確かめよう

**第3話 9コマ目**

**アイ：** 巻物を書き直したら、矢も放ち直さないとですね

</details>

## 解説：第3話の種明かし

![第3話の種明かし 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t3-01.png)

![第3話の種明かし 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t3-02.png)

![第3話の種明かし 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t3-intro.png)

![第3話の種明かし 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t3-03.png)

![第3話の種明かし 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t3-04.png)

![第3話の種明かし 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t3-05.png)

[2. 埋め込みモデルをDB内へ持ち込み、DBの中でベクトルを作る](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#2-%E5%9F%8B%E3%82%81%E8%BE%BC%E3%81%BF%E3%83%A2%E3%83%87%E3%83%AB%E3%82%92db%E5%86%85%E3%81%B8%E6%8C%81%E3%81%A1%E8%BE%BC%E3%81%BFdb%E3%81%AE%E4%B8%AD%E3%81%A7%E3%83%99%E3%82%AF%E3%83%88%E3%83%AB%E3%82%92%E4%BD%9C%E3%82%8B)

<details>
<summary>第3話の種明かしの会話をテキストで読む</summary>

**第3話の種明かし 1コマ目**

**アイ：** 意味読みの精霊さんは、本当は……

**神宮寺：** 埋め込みモデルの multilingual-e5-large。汗はかかないけど、CPUは使う

**第3話の種明かし 2コマ目**

**アイ：** 精霊さんを図書館に招いたのは……

**神宮寺：** 埋め込みモデルを、ONNX形式でDBの中へインポートしたということ。DB内のモデルなら、文書をDBの外へ出さずにベクトルにできる

外部APIへ送る DB内のモデルで作る

**第3話の種明かし 3コマ目**

Oracle AI Databaseの機能

埋め込みモデルのインポート

モデルをDBへ取り込み、文書をDB内でベクトル化

**第3話の種明かし 4コマ目**

**神宮寺：** 埋め込みは、DBのCPUとメモリーを使う。どれだけ使うかは、自分の環境で測ろう。文書を直したら、ベクトルも作り直す

埋め込みはDBの中 回答のLLMは外部 文書を直したら作り直す

**第3話の種明かし 5コマ目**

```
SELECT doc_id, chunk_text,
  VECTOR_DISTANCE(embedding,
    VECTOR_EMBEDDING(MULTILINGUAL_E5_LARGE
      USING 'query: 管理画面が固まって操作できない' AS data),
    COSINE) AS distance
FROM OJ41_CHUNKS
ORDER BY distance, doc_id
FETCH FIRST 3 ROWS ONLY;
```

**第3話の種明かし 6コマ目**

原記事「2. 埋め込みモデルをDB内へ持ち込み、DBの中でベクトルを作る」

</details>

## 第4話　護符と結界

![第4話 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-01.png)

![第4話 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-02.png)

![第4話 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-03.png)

![第4話 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-04.png)

![第4話 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-05.png)

![第4話 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-06.png)

![第4話 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-07.png)

![第4話 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-08.png)

![第4話 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-09.png)

![第4話 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-10.png)

![第4話 11コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c4-11.png)

<details>
<summary>第4話の会話をテキストで読む</summary>

**第4話 1コマ目**

**ハルシーネ：** 水鏡の相談、わたくしが代わりにお答えしますわ！

**ハルシーネ：** 竜騎士団の砦の魔導炉なら、この手順で直りましたわ！ 似ていますもの！

**第4話 2コマ目**

**ハルシーネ：** 砦まで参りますわ！ 星見の塔さんの契約なら、行けますもの！

**第4話 3コマ目**

**ガルド：** ……今、うちの砦の話を、 よその塔にしたな？

**アイ：** ちょっと！ 別のお客さまの話です！

**第4話 4コマ目**

**神宮寺：** 意味が似ているだけでは、案内に使えない。その相談札のお客さまの範囲で探す必要がある

**アイ：** ハルシーネさんに『よそのお客さまの話はしないで』ってお願いすれば……

**第4話 5コマ目**

**ハルシーネ：** 善処いたしますわ～

**神宮寺：** お願いでは守れない。図書館の仕組みで守ろう

**第4話 6コマ目**

**神宮寺：** 相談を受けたら、相談札を開く。その相談の間は、この護符がお客さまを覚えている

**神宮寺：** そして結界。結界は、護符のお客さまと、巻物や石板に記されたお客さまを比べて、同じお客さまのものだけを見せる

**第4話 7コマ目**

**ハルシーネ：** えいっ

**第4話 8コマ目**

**アイ：** 護符を付け忘れたらどうなるんですか？

**第4話 9コマ目**

**アイ：** 何も見えない！

**神宮寺：** 間違えて、よそのお客さまの話が見えるより、ずっといい

**第4話 10コマ目**

**神宮寺：** それから、書架を直接のぞけたら、結界の意味がない。図書館の決まりで、この結界からしか読めないようにする

**第4話 11コマ目**

**ハルシーネ：** お、覚えてらっしゃい！

</details>

## 解説：第4話の種明かし

![第4話の種明かし 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t4-01.png)

![第4話の種明かし 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t4-02.png)

![第4話の種明かし 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t4-03.png)

![第4話の種明かし 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t4-04.png)

原記事：[混ぜるな危険！](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#%E6%B7%B7%E3%81%9C%E3%82%8B%E3%81%AA%E5%8D%B1%E9%99%BA)・[対応中のチケットの顧客に検索範囲を限定する仕組み](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#%E5%AF%BE%E5%BF%9C%E4%B8%AD%E3%81%AE%E3%83%81%E3%82%B1%E3%83%83%E3%83%88%E3%81%AE%E9%A1%A7%E5%AE%A2%E3%81%AB%E6%A4%9C%E7%B4%A2%E7%AF%84%E5%9B%B2%E3%82%92%E9%99%90%E5%AE%9A%E3%81%99%E3%82%8B%E4%BB%95%E7%B5%84%E3%81%BF)

<details>
<summary>第4話の種明かしの会話をテキストで読む</summary>

**第4話の種明かし 1コマ目**

**アイ：** 護符と結界、本当はどうなってるんですか？

**神宮寺：** PL/SQLとビューだよ

**第4話の種明かし 2コマ目**

| 魔法の世界 | 実際の技術 |
| --- | --- |
| 相談札 | チケット |
| 護符 | 相談中の顧客IDを覚えるPL/SQLパッケージ変数 |
| 結界 | 顧客で行を絞るビュー |
| 図書館の決まり | DB権限 |

ビューは、元の表の必要な行と列を見せる窓

**第4話の種明かし 3コマ目**

**神宮寺：** 護符の正体は、PL/SQLパッケージの変数だ。チケットを開くと顧客IDが入り、同じDBセッションの間、覚えている。ビューはWHEREで各行と比べ、未設定なら0件にするよ

護符＝パッケージ変数の顧客ID 同じDBセッションで保持 未設定なら0件

**第4話の種明かし 4コマ目**

**神宮寺：** 書架を直接のぞかせない決まりは、DB権限のたとえだ。アプリのDBユーザーには、ビューだけを読む権限を与えるよ

書架を直接のぞかせない 元の表は読ませない ビューの読取りだけ

</details>

## 第5話　判定の印

![第5話 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c5-01.png)

![第5話 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c5-02.png)

![第5話 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c5-03.png)

![第5話 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c5-04.png)

![第5話 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c5-05.png)

![第5話 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c5-06.png)

<details>
<summary>第5話の会話をテキストで読む</summary>

**第5話 1コマ目**

**アイ：** 次は、ガルドさんの相談。『砦まで来てもらえるか』ですね！

ガルド／砦まで来てもらえるか

**第5話 2コマ目**

**神宮寺：** 現地保守を頼めるかは、石板には刻まない。結界を通して見てごらん

星見の塔 解約・停止なし 来年の春まで 現地

**第5話 3コマ目**

**神宮寺：** 解約も停止もなく、今日が期間内で、現地保守ありの契約だけに『対象』の印が浮かぶ。結界が、見るたびに判定する

星見の塔 解約・停止なし 来年の春まで 現地

対象

**第5話 4コマ目**

**アイ：** 石板に刻んでおいたら、期限が切れても『対象』のまま残っちゃいますもんね！

去年の秋まで

対象

**第5話 6コマ目**

**アイ：** 竜騎士団さんの護符で見ると……『対象外』。遠隔保守だけの契約だからですね

**アイ：** 対象外の石板も隠さずに見せるから、なぜ対象外か、説明できるんですね！

**ガルド：** なるほど、うちは遠隔だったな。……よその塔に話を漏らさないなら、それでいい

竜騎士団 解約・停止なし 期間内 遠隔

対象外

</details>

## 解説：第5話の種明かし

![第5話の種明かし 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-01.png)

![第5話の種明かし 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-02.png)

![第5話の種明かし 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-03.png)

![第5話の種明かし 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-04.png)

![第5話の種明かし 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-05.png)

![第5話の種明かし 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-05a.png)

![第5話の種明かし 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-05b.png)

![第5話の種明かし 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-05c.png)

![第5話の種明かし 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-05d.png)

![第5話の種明かし 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t5-06.png)

原記事：[契約の判定も LLM に推測させずビューで判定する](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#%E5%A5%91%E7%B4%84%E3%81%AE%E5%88%A4%E5%AE%9A%E3%82%82-llm-%E3%81%AB%E6%8E%A8%E6%B8%AC%E3%81%95%E3%81%9B%E3%81%9A%E3%83%93%E3%83%A5%E3%83%BC%E3%81%A7%E5%88%A4%E5%AE%9A%E3%81%99%E3%82%8B)・[デモA](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#%E3%83%87%E3%83%A2a%E3%83%AA%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%8A%E3%83%AB%E3%83%87%E3%83%BC%E3%82%BF%E3%83%99%E3%83%BC%E3%82%B9%E3%81%AB%E3%82%88%E3%82%8B-%E3%83%99%E3%82%AF%E3%83%88%E3%83%AB%E6%A4%9C%E7%B4%A2--join--%E3%83%95%E3%82%A3%E3%83%AB%E3%82%BF%E3%83%AA%E3%83%B3%E3%82%B0%E6%A9%9F%E7%A8%AE%E3%81%A7%E7%B5%9E%E3%81%A3%E3%81%A6%E3%83%99%E3%82%AF%E3%83%88%E3%83%AB%E8%B7%9D%E9%9B%A2%E3%81%A7%E4%B8%A6%E3%81%B9%E3%82%8B)

<details>
<summary>第5話の種明かしの会話をテキストで読む</summary>

**第5話の種明かし 1コマ目**

**アイ：** 判定の印って、本当は……

**神宮寺：** ビューの計算列だよ

**第5話の種明かし 2コマ目**

| 魔法の世界 | 実際の技術 |
| --- | --- |
| 契約の石板 | 契約の表 |
| 判定の印 | ビューのCASE式で作る判定列 onsite\_eligible |

ビューは、元の表の行と列に、計算した列を加えて見せることもできる

**第5話の種明かし 3コマ目**

**神宮寺：** 石板に刻まなかった判定の印は、ビューのCASE式で作る判定列だ。今日の日付と契約の条件から、その都度決めるよ

判定列はビューで作る 表には保存しない 解約・停止なし／期間内／現地

**第5話の種明かし 4コマ目**

OJ41\_VISIBLE\_CONTRACTSのCASE式

```
CASE WHEN c.status = 'ACTIVE'
       AND r.as_of_date BETWEEN c.start_date AND c.end_date
       AND c.service_scope = 'ONSITE'
     THEN 'Y' ELSE 'N' END AS onsite_eligible
```

デモでは、結果が毎回変わらないよう、今日の代わりに固定の基準日（r.as\_of\_date）を使う

**第5話の種明かし 5コマ目**

**アイ：** 『対象外』の石板も隠さないのは、理由を説明するためなんですね。判定をビューにまとめれば、アプリもAIのSQLも同じ判定を使えます！

対象外（N）の行も返す 判定はビューで共通化

**第5話の種明かし 6コマ目**

**神宮寺：** 結界で範囲を絞り、判定の印でルールを決める。このマンガの原作者は、このビューの使い方を『VIEW as a Harness』と呼んでいるんだ

**アイ：** ハーネスって、馬の手綱みたいなものですか？

**神宮寺：** そう。AIの力を、正しい方へ向けるための仕組みだよ

VIEW as a Harness 範囲を絞る・判定を決める

**第5話の種明かし 7コマ目**

VIEW as a Harness

**第5話の種明かし 8コマ目**

**アイ：** 専用のベクトルデータベースじゃなくて、Oracle みたいな RDB を使う意味って、ここにもあるんですね！

**神宮寺：** そう。ベクトル検索だけなら、専用のデータベースでもできる。でも、ビューで範囲を絞り、SQLで業務ルールを判定し、権限で守る。そうした機能がそろっていることも、RDB を使う意義なんだ

ビュー・SQL・権限

**第5話の種明かし 9コマ目**

**アイ：** 判定の印をビューに持たせておくと、ほかにもいいことがあるんですか？

**神宮寺：** あるよ。言葉からSQLを作る NL2SQL で、この判定列が威力を発揮するんだ。AIに判定の式を一から書かせなくても、判定列を使えばいい。その話は第7話で

NL2SQLでも 判定列を使う

**第5話の種明かし 10コマ目**

原記事「3. チケットの顧客と機種を絞ってベクトル検索する」「デモA」

</details>

## 第6話　根拠を召喚せよ

![第6話 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-01.png)

![第6話 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-02.png)

![第6話 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-03.png)

![第6話 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-04.png)

![第6話 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-05.png)

![第6話 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-06.png)

![第6話 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-07.png)

![第6話 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-08.png)

![第6話 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-09.png)

![第6話 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-10.png)

![第6話 11コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-11.png)

![第6話 12コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c6-12.png)

<details>
<summary>第6話の会話をテキストで読む</summary>

**第6話 1コマ目**

ギルド長　人がよく、文章のうまい者にすぐ感心する

**ギルド長：** ギルド長の私が、新しい相談係を雇ったぞ！ 文章がとてもうまくてな

**第6話 2コマ目**

**アイ・神宮寺（二人の心の声）：** （よりによって……）

**神宮寺：** 彼女の正体は、生成の精霊だ。いたずら好きだが、話す力は本物だよ

**第6話 3コマ目**

**ミラ：** 管理盤が開きません。流星群まで、あと三時間です！

**ハルシーネ：** 魔導炉を37回再起動なさって、月に向かって炉へ歌いかければ直りますわ！

**第6話 4コマ目**

**ミラ：** さ、37回!?

**アイ：** 根拠は!?

**第6話 5コマ目**

**ハルシーネ：** 雰囲気ですわ！

**神宮寺：** 話す力はある。足りないのは根拠だ

**第6話 6コマ目**

**アイ：** 根拠召喚！

第一　制御陣に入れないとき

第十二　現地へ向かう手配

**第6話 7コマ目**

**神宮寺：** この巻物をもとに答えてもらう。巻物に書かれていないことは、分からないと答える

**第6話 8コマ目**

**ハルシーネ：** ……炉の魔力線、水晶の差し込み、 管理盤までの通り道を確かめ、炉の記録を写しておきます。 再起動の前に、塔の明かりへの影響を確かめてください。 根拠は手順の巻物、第一ですわ

**第6話 9コマ目**

**ミラ：** ちゃんとしてる！

**ハルシーネ：** わたくし、本気を出せばこんなものですわ

**第6話 10コマ目**

**神宮寺：** そして返ってきた答えも検査する。根拠の巻物が、渡した巻物の中にあるか。中身が合っているか

**第6話 11コマ目**

**アイ：** つまり、答えが変なとき、探す段階で失敗したのか、話す段階で間違えたのか、分けて確認することが大事ってことですね！

**神宮寺：** 今回は全部合ってる

**第6話 12コマ目**

**ハルシーネ：** ……なんだか、わたくし、監視されてません？

**神宮寺：** されてるよ

</details>

## 解説：第6話の種明かし

![第6話の種明かし 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t6-01.png)

![第6話の種明かし 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t6-intro.png)

![第6話の種明かし 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t6-02.png)

![第6話の種明かし 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t6-03.png)

![第6話の種明かし 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t6-04.png)

![第6話の種明かし 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t6-05.png)

![第6話の種明かし 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t6-06.png)

[4. 検索した文書を根拠にRAG（検索拡張生成）で回答する](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#4-%E6%A4%9C%E7%B4%A2%E3%81%97%E3%81%9F%E6%96%87%E6%9B%B8%E3%82%92%E6%A0%B9%E6%8B%A0%E3%81%ABrag%E6%A4%9C%E7%B4%A2%E6%8B%A1%E5%BC%B5%E7%94%9F%E6%88%90%E3%81%A7%E5%9B%9E%E7%AD%94%E3%81%99%E3%82%8B)

<details>
<summary>第6話の種明かしの会話をテキストで読む</summary>

**第6話の種明かし 1コマ目**

**アイ：** ハルシーネさんの正体は……

**神宮寺：** LLMだね。名前はハルシネーションから。検索した根拠を添えて答えてもらうのが、RAGだよ

**第6話の種明かし 2コマ目**

設計の考え方

RAG（検索拡張生成）

検索した根拠をLLMへ渡し、回答を生成

**第6話の種明かし 3コマ目**

| 魔法の世界 | 実際の技術 |
| --- | --- |
| 根拠召喚 | RAG（検索拡張生成） |
| 生成の精霊 | LLM |
| 手順の巻物 | ビューの範囲で検索した文書 |

**第6話の種明かし 4コマ目**

**神宮寺：** 根拠召喚で渡した二本の巻物は、ビューの範囲で検索した文書だ。書かれていないことは、分からないと答えてもらうよ

結界内の巻物だけを渡す 本文を根拠にLLMが回答 書かれていなければ不明

**第6話の種明かし 5コマ目**

**アイ：** 返ってきた答えは、巻物と照らし合わせましたね。引用した文書が渡した中にあるか、中身も合っているかを確かめるんですね

返ってきた答えも検査 渡した文書の中にあるか 内容は根拠と合うか

**第6話の種明かし 6コマ目**

**神宮寺：** 根拠の巻物を見つけ損ねたなら、検索を直す。見つけた根拠から答えを誤ったなら、生成を直すんだ

原記事「4. 検索した文書を根拠にRAG（検索拡張生成）で回答する」「デモB」「検索の失敗と生成の失敗を分けて直す」

手順の巻物を探す＝検索 答えを作る段階＝生成

**第6話の種明かし 7コマ目**

**アイ：** 37回の再起動は……

**神宮寺：** 根拠のない回答の、いい見本だったね

</details>

## 第7話　言の葉魔法

![第7話 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-01.png)

![第7話 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-02.png)

![第7話 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-03.png)

![第7話 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-04.png)

![第7話 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-05.png)

![第7話 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-06.png)

![第7話 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-07.png)

![第7話 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-08.png)

![第7話 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-09.png)

![第7話 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-10.png)

![第7話 11コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-11.png)

![第7話 12コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-12.png)

![第7話 13コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-13.png)

![第7話 14コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-14.png)

![第7話 15コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-15.png)

![第7話 16コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-15b.png)

![第7話 17コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-16.png)

![第7話 18コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c7-17.png)

<details>
<summary>第7話の会話をテキストで読む</summary>

**第7話 1コマ目**

**ミラ：** 流星群の観測、来月は塔まで来てもらえますか？ うちの契約、まだ続いてますよね？

**アイ：** せ、セレクト・カウント・フロム……いひゃい

**第7話 2コマ目**

**アイ：** 師匠！ 今こそ無詠唱魔術を！

**神宮寺：** 無詠唱ではない。言の葉魔法だ。複雑な魔術式を自分で組み立てずに、ふだんの話し言葉で頼む

**第7話 3コマ目**

言の葉魔法　話し言葉の頼みを、生成の精霊が古代語の魔術式に組み立てて唱える

**アイ：** 魔術式を覚えなくていいなんて、夢の魔法です！ で、魔術式は誰が組み立てるんですか？

**神宮寺：** 生成の精霊――つまり、彼女だ

**第7話 4コマ目**

**ハルシーネ：** 古代語の作文なら、お手のものですわ！

**アイ：** よ、よりによって……

**第7話 5コマ目**

**アイ：** 現地保守を頼める契約を、出して！

現地

解約済み

期限切れ

**第7話 6コマ目**

**ミラ：** えっ、うちの塔、そんなに契約してましたっけ？

**アイ：** なんで!?

**第7話 7コマ目**

**ハルシーネ：** 『現地保守』と刻んである石板を、全部お出ししましたわ！ それっぽいでしょう？

現地

**第7話 8コマ目**

**神宮寺：** 彼女が組み立てた魔術式を見てみよう

**第7話 9コマ目**

**神宮寺：** 判定の印を使わずに、石板の刻みから自分で判定している。『現地』と刻んであれば、解約済みでも期限切れでも出してしまう

現地

**第7話 10コマ目**

**アイ：** 『現地保守を頼める』を、『現地』の刻みだけで判断しちゃダメってことが、ハルシーネさんに伝わってなかったんだ……解約や有効期間も確かめないと

**神宮寺：** そう。そして、その判定は結界に任せる。彼女に判定させてはいけない

**第7話 11コマ目**

**神宮寺：** 修行の三点セットだ。石板の注釈と、手本の巻物、そして書架の封印。封印は、彼女が読める書架を、結界だけに限る

**神宮寺：** 封印とは別に、図書館の決まりでも、元の書架は直接のぞかせないこと

石板の注釈

『現地保守を頼める』は、判定の印を見ること

手本の巻物

**第7話 12コマ目**

**ハルシーネ：** 最初から、そうおっしゃってくださいな

**第7話 13コマ目**

**アイ：** 現地保守を頼める契約を、出して！

**第7話 14コマ目**

**アイ：** 判定の印で絞ってる。中身よし！

**第7話 15コマ目**

**アイ：** 判定の印は、今日の判定。

**アイ：** 来月のことは……契約の終わりは来年の春。来月の観測日も期間内です！

**ミラ：** よかった、来月も来てもらえる！

星見の塔 解約・停止なし 来年の春まで 現地

対象

**第7話 16コマ目**

**ハルシーネ：** わたくし、古代語の作文は完璧ですのよ。知らなかったのは、この図書館の言葉の意味と、約束事だけですわ

**第7話 17コマ目**

**アイ：** 言の葉魔法って、何でも叶える夢の魔法じゃなくて、ちゃんと言葉の意味や約束事を、精霊に教えておく必要があるんですね

**神宮寺：** そのとおり。注釈も手本も封印も、精霊への教え方だ

**第7話 18コマ目**

**神宮寺：** ……ちなみに私くらいになると、言の葉魔法で世界を創造できる

</details>

## 解説：第7話の種明かし

![第7話の種明かし 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t7-01.png)

![第7話の種明かし 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t7-intro.png)

![第7話の種明かし 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t7-02.png)

![第7話の種明かし 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t7-04.png)

![第7話の種明かし 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t7-05.png)

![第7話の種明かし 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t7-06.png)

![第7話の種明かし 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t7-07.png)

![第7話の種明かし 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t7-08.png)

[5. NL2SQL で契約情報を照会する](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#5-nl2sql-%E3%81%A7%E5%A5%91%E7%B4%84%E6%83%85%E5%A0%B1%E3%82%92%E7%85%A7%E4%BC%9A%E3%81%99%E3%82%8B)

<details>
<summary>第7話の種明かしの会話をテキストで読む</summary>

**第7話の種明かし 1コマ目**

**アイ：** 言の葉魔法って、つまり……

**神宮寺：** AIによるコード生成。Oracle AI Database では、Select AI という機能で、言葉で頼むとAIがSQLを書いてくれる

**第7話の種明かし 2コマ目**

Oracle AI Databaseの機能

Select AI

自然言語からSQLを生成し、データを照会

自然言語の質問

生成されたSQL

実行結果

**第7話の種明かし 3コマ目**

| 魔法の世界 | 実際の技術 |
| --- | --- |
| 言の葉魔法 | Select AI（自然言語からSQLを生成） |
| 生成の精霊（ハルシーネ） | SQLを組み立てるLLM |
| 古代語の魔術式 | SQL |
| 魔術式の写し見 | showsql |
| 石板の注釈 | 注釈（ANNOTATIONS） |
| 判定の印 | ビューの判定列 onsite\_eligible |
| 手本の巻物 | Select AI Feedback |
| 書架の封印 | object\_list と enforce\_object\_list=true |

**第7話の種明かし 4コマ目**

**神宮寺：** 失敗の原因は、AIがこの表の言葉の意味を知らなかったことだ。注釈で列の意味を、Feedbackで正しい例を教えるよ

AIは表の言葉の意味を知らない 注釈で列の意味を教える Feedbackで手本を示す

**第7話の種明かし 5コマ目**

**神宮寺：** 書架の封印は、object\_list と enforce\_object\_list=true で、参照先をビューに限る仕組みだ。DB権限も別に絞るよ

判定列を持つビューだけ 元の契約の表は読まない DB権限も別に絞る

**第7話の種明かし 6コマ目**

契約ID：contract\_id／契約終了日：end\_date

```
SELECT contract_id, end_date
FROM OJ41_VISIBLE_CONTRACTS
WHERE service_scope = 'ONSITE';
```

```
FROM
  "ORAJAM41USER"."OJ41_VISIBLE_CONTRACTS" "c"
WHERE
  "c"."ONSITE_ELIGIBLE" = 'Y'
```

**第7話の種明かし 7コマ目**

原記事「5. NL2SQL で契約情報を照会する」「デモC」

**第7話の種明かし 8コマ目**

**アイ：** 言の葉魔法で世界を創造というのは？

**神宮寺：** このマンガ自体が、生成AIを使って制作されているんだ

</details>

## 第8話　使い魔と手綱

![第8話 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-01.png)

![第8話 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-02.png)

![第8話 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-03.png)

![第8話 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-04.png)

![第8話 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-05.png)

![第8話 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-06.png)

![第8話 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-07.png)

![第8話 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-08.png)

![第8話 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-09.png)

![第8話 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-10.png)

![第8話 11コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-11.png)

![第8話 12コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-12.png)

![第8話 13コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-13.png)

![第8話 14コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-14.png)

![第8話 15コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-15.png)

![第8話 16コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-c8-16.png)

<details>
<summary>第8話の会話をテキストで読む</summary>

**第8話 1コマ目**

**神宮寺：** 相談が増えてきた。手順探しと契約の確認を、使い魔に手伝ってもらおう

**第8話 2コマ目**

使い魔エージェ　道具を使って調べものをする。はりきりすぎるのが玉にきず

**アイ：** 出でよ、わたしの使い魔、エージェ！

**エージェ：** 呼んだ？ 呼んだよね？

**第8話 3コマ目**

**神宮寺：** 道具を2つ持たせる。文書検索と契約照会だ。この2つで対応できる仕事なら、何でも任せられる

文書検索

契約照会

**第8話 4コマ目**

**エージェ：** あっ、竜だ！ 友だちになりたい！

星見の塔 管理盤が開かない

**第8話 5コマ目**

**ハルシーネ：** ついでに竜騎士団の魔導炉も調べてさしあげなさい！ そっちの方が面白いですわ！

**エージェ：** わーい、竜の方ー！

**第8話 6コマ目**

**ガルド：** うちの砦に、勝手に来るなぁぁ！

**アイ：** エージェ、だめー！

**第8話 8コマ目**

**アイ：** 『いつか使う』って言ってた、あの手綱！

**神宮寺：** この手綱、つまりハーネスは、力を止めるためのものではない。力を正しい方へ向けるためのものだ

**第8話 9コマ目**

**神宮寺：** 使い魔が決めていいのは、どの道具を使うかと、何を探すか（検索語）まで

**神宮寺：** 調べる魔導炉は、開いている相談札から、ギルドの仕組みが決める。使い魔には決めさせない

**第8話 10コマ目**

**アイ：** 検索語は任せても、調べる魔導炉は勝手に変えさせないんですね

ギルドの見張り番

**第8話 11コマ目**

成功

手順の巻物 第一

手順の巻物 第十二

星見の塔 解約・停止なし 来年の春まで 現地

対象

**第8話 12コマ目**

**エージェ：** 星見の塔の契約は、現地保守の対象だよ！

**エージェ：** 手順で直らなかったときのために、塔へ向かう手配案を作ったよ。出発を決めるには、担当者の承認が要るよ。根拠は手順の巻物、第十二！

手配案／要承認

手順の巻物 第一

手順の巻物 第十二

星見の塔 解約・停止なし 来年の春まで 現地

対象

**第8話 13コマ目**

**神宮寺：** 最後に行動日誌を開こう。どの道具を、どんな入力で呼んで、成功したか、何が返ったか

**アイ：** 道具を呼ばずに答えていたら、成功した答えとして通さない。……今回は全部合ってます！

行動日誌

文書検索：管理盤・訪問の手配 → 手順の巻物 第一・第十二（成功）

契約照会：星見の塔 → 現地保守の対象（成功）

**第8話 14コマ目**

**ハルシーネ：** ちょっと！ 淑女に手綱だなんて、あんまりですわ！

**神宮寺：** すまない。君の話す力は、ここに必要だ。手綱と同じ力を、マントに込めよう

**第8話 16コマ目**

**ハルシーネ：** ……し、仕方ありませんわね。紫と金なら、着てさしあげてもよくってよ

</details>

## 解説：第8話の種明かし

![第8話の種明かし 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-01.png)

![第8話の種明かし 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-intro.png)

![第8話の種明かし 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-02.png)

![第8話の種明かし 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-03.png)

![第8話の種明かし 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-04.png)

![第8話の種明かし 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-05.png)

![第8話の種明かし 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-06.png)

![第8話の種明かし 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-07.png)

![第8話の種明かし 9コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-harness.png)

![第8話の種明かし 10コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-07b.png)

紹介ブログ：[Oracle AI Database Agent Engineの紹介](https://blogs.oracle.com/oracle4engineer/ja-introducing-oracle-ai-database-agent-engine)

![第8話の種明かし 11コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-engine.png)

![第8話の種明かし 12コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-t8-08.png)

[6. 文書検索と契約照会をAgentのツールにする](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960#6-%E6%96%87%E6%9B%B8%E6%A4%9C%E7%B4%A2%E3%81%A8%E5%A5%91%E7%B4%84%E7%85%A7%E4%BC%9A%E3%82%92agent%E3%81%AE%E3%83%84%E3%83%BC%E3%83%AB%E3%81%AB%E3%81%99%E3%82%8B)

<details>
<summary>第8話の種明かしの会話をテキストで読む</summary>

**第8話の種明かし 1コマ目**

**アイ：** エージェ、かわいかったですね

**神宮寺：** 本当はSelect AI Agent。かわいさは、ちょっと足した

**第8話の種明かし 2コマ目**

Oracle AI Databaseの機能

Select AI Agent

DB内のツールを使い、実行の履歴を残す

**第8話の種明かし 3コマ目**

| 魔法の世界 | 実際の技術 |
| --- | --- |
| 使い魔 | Select AI Agent |
| 道具袋 | Tool（文書検索・契約照会） |
| ギルドの見張り番 | 確定的なパラメータはアプリケーションで固定 |
| 行動日誌 | USER\_AI\_AGENT\_TOOL\_HISTORY |
| 手綱とマント | ハーネス |

**第8話の種明かし 4コマ目**

**神宮寺：** 使い魔が選ぶのは、道具と検索語までだったね。対象の機器や顧客は、チケットからアプリが設定する

使い魔が選ぶ：道具と検索語 対象はチケットから決定

**第8話の種明かし 5コマ目**

```
SELECT invocation_id,team_exec_id,tool_name,start_date,input,output
FROM USER_AI_AGENT_TOOL_HISTORY
WHERE task_name='OJ41_SUPPORT_TASK'
ORDER BY start_date DESC
FETCH FIRST 10 ROWS ONLY;
```

**第8話の種明かし 6コマ目**

**神宮寺：** 行動日誌を答えと照らし合わせたように、ツールの入力と結果を確かめるんだ。ツールを呼ばずに答えていたら、成功として扱わないよ

行動日誌と回答を照合 ツール・入力・成否・結果

**第8話の種明かし 7コマ目**

**アイ：** エージェが作ったのは、まだ手配案でしたね。現地保守の対象でも、訪問や出発を決めるには担当者の承認が要るんですね

**神宮寺：** そう。人の承認を求めるツールや、訪問の手配を実行するツールを渡して、使い魔の仕事を広げることもできるね

現地保守の対象 まだ訪問の承認ではない 手配案まで。承認は人が

**第8話の種明かし 8コマ目**

**神宮寺：** エージェの手綱もハルシーネのマントも、ハーネスのたとえだ。使える範囲・道具・検査・記録を整えて、力を正しい方へ向けるんだよ

手綱もマントもハーネス 範囲・道具・検査・記録

**第8話の種明かし 9コマ目**

設計の考え方

ハーネス

AIが使える範囲・道具・検査・記録を整える

使える範囲

道具

AI

検査

記録

**第8話の種明かし 10コマ目**

**神宮寺：** それから、2026年10月には、Agent Engine という新機能も登場した。

**神宮寺：** エージェントのワークフローを、Open Agent Specification という共通の仕様で書けるんだ。対応する実装の間で持ち運べるし、並列や分岐、繰り返しといった流れも組める。今度、試してみよう！

**アイ：** はい！

**第8話の種明かし 11コマ目**

Oracle AI Databaseの機能

Agent Engine

Open Agent Specificationで書いたワークフローを、DB内で実行

DB内のワークフロー

順次

並列

分岐・繰り返し

LLM

ワークフローで決めた所でだけ呼ぶ

対応する実装の間で持ち運べる

Open Agent Specification

ワークフローの型（例）

**第8話の種明かし 12コマ目**

原記事「6. 文書検索と契約照会をAgentのツールにする」「デモD」

</details>

## エピローグ　データのそばに、魔法を。

![エピローグ 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-epi-01.png)

![エピローグ 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-epi-02.png)

![エピローグ 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-epi-03.png)

![エピローグ 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-epi-04.png)

![エピローグ 5コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-epi-05.png)

![エピローグ 6コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-epi-06.png)

![エピローグ 7コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-epi-07.png)

![エピローグ 8コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-epi-08.png)

<details>
<summary>エピローグの会話をテキストで読む</summary>

**エピローグ 1コマ目**

**ミラ：** 間に合いましたー！

**エピローグ 2コマ目**

**ハルシーネ：** 竜騎士団さまなら、たぶん大丈……

**エピローグ 3コマ目**

**ハルシーネ：** ……こほん。竜騎士団さまは遠隔保守のご契約ですので、こちらから炉の記録を拝見しますわ。根拠は手順の巻物、第一ですわ

**ガルド：** うむ。よその塔の話も出なかった。気に入った

**エピローグ 4コマ目**

**コピーゴーストA：** 最新、気持ちいーい

**エピローグ 5コマ目**

**アイ：** 師匠。魔法って、すごい力を出すことだと思ってました

**神宮寺：** データのそばで、正しい範囲に、手綱を付けて使う。それがいちばん強い魔法だ

**エピローグ 6コマ目**

**アイ：** データのそばに、魔法を！ マジカル・インデータベース！

**エピローグ 7コマ目**

**エージェ：** 呼んだ？

**エピローグ 8コマ目**

**アイ：** 呼んでない！

おしまい

</details>

## 解説：おわりに

![おわりに 1コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-tend-01.png)

![おわりに 2コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-tend-intro.png)

![おわりに 3コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-tend-03.png)

[原記事](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960)・[本編のマンガ](https://qiita.com/yuji-arakawa/items/1c6d0ae4400ca2b4bae3)

![おわりに 4コマ目](https://kutsushitaneko.github.io/in-database-ai-manga/assets/magical-girl-ai/v19/panel-v19-tend-04.png)

<details>
<summary>おわりにの解説をテキストで読む</summary>

**おわりに 1コマ目**

**アイ：** 物語の魔法と、本当の技術。つながってましたね

**神宮寺：** データのそばでAIを動かす、インデータベースAI。範囲と検査も決めておく。魔法の言葉でも、技術の言葉でも、言っていることは同じだよ

**おわりに 2コマ目**

設計の考え方

インデータベースAI

データのある場所で、AIの検索や処理を動かす

**おわりに 3コマ目**

原記事「はじめてのインデータベースAI～ ベクトル検索・RAGからAIエージェントまで～」 本編の漫画『【マンガ】はじめてのインデータベースAI～ ベクトル検索・RAGからAIエージェントまで～ （コミカライズ版）』（副題：データのそばに、AIを。）

**おわりに 4コマ目**

**アイ：** ……呼んでないですよ？

</details>

## 原典とコードの出典

技術原典：Yuji Arakawa「[はじめてのインデータベースAI～ベクトル検索・RAGからAIエージェントまで～](https://qiita.com/yuji-arakawa/items/1df29b844478f9df5960)」。記事・図の利用条件は [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) です。物語は技術の仕組みを魔法に置き換えた翻案です。

コード：[orajam41-in-database-ai-demo](https://github.com/kutsushitaneko/orajam41-in-database-ai-demo)（Copyright Yuji Arakawa、[MIT License](https://github.com/kutsushitaneko/orajam41-in-database-ai-demo/blob/main/LICENSE)）。第5話のCASE式は原典の空白・改行・字下げを保持しています。第7話の契約SQLは原典の実在する表・列を使った漫画用の例で、モデルの実測出力ではありません。物語の顧客・契約期限は創作した設定です。

## 謝辞

この漫画の制作に使用した [Manga Generator](https://github.com/stockedge/manga-generator) を公開されている月森ナギ様に感謝します。

