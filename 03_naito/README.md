AJACS番町1：塩基配列解析およびゲノム編集のためのデータベース・ウェブツール
---------------

ライフサイエンス統合データベースセンター（DBCLS）  
内藤 雄樹（[自己紹介](http://researchmap.jp/meso_cacase/)）  
2018年8月29日 統合データベース講習会 AJACS番町1  
JST東京本部（サイエンスプラザ）　B1大会議室

  - [スライドPDF](https://github.com/AJACS-training/AJACS71/blob/master/03_naito/AJACS71_03_naito.pdf)

講習で紹介するデータベースやウェブツールへのリンクです。

#### NCBI ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/ncbi_600.png
"スクリーンショット")

  - NCBI - http://www.ncbi.nlm.nih.gov/

#### NCBI BLAST ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/ncbiblast_600.png
"スクリーンショット")

  - NCBI BLAST - http://www.ncbi.nlm.nih.gov/BLAST

#### UCSC BLAT ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/BLAT.png
"スクリーンショット")

  - UCSC BLAT - https://genome.ucsc.edu/cgi-bin/hgBlat
  - 配列を探してみよう - tgaatgaagacgatcgactcaaattcacagctccacaggatggaattcttcttaacaaagctcgacaattcgga （線虫）
  - 統合TVによる解説動画
    - [高速アラインメントツールBLATをプライマー設計支援ツールとして使い倒す2009](http://togotv.dbcls.jp/ja/20090619.html)

#### UCSCゲノムブラウザ ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/867440539.png
"スクリーンショット")

  - UCSCゲノムブラウザ – https://genome.ucsc.edu/cgi-bin/hgTracks
  - 統合TVによる解説動画
    - [UCSC Genome Browserの使い方〜基本編](http://togotv.dbcls.jp/ja/20091113.html)
    - [UCSC Genome Browserの使い方〜表示編](http://togotv.dbcls.jp/ja/20091126.html)
    - [UCSC Genome Browser の使い方〜アノテーショントラック編〜](http://togotv.dbcls.jp/ja/20100722.html)
    - [UCSC Genome Browserの使い方〜wig形式のファイルをトラックとして追加する〜](http://togotv.dbcls.jp/ja/20120116.html)
    - [UCSC Genome Browserの使い方〜表示+ENCODE編〜 2012](http://togotv.dbcls.jp/ja/20120528.html)
    - [UCSC genome browserの使い方～配列取得編～2013](http://togotv.dbcls.jp/ja/20131113.html)


#### 統合遺伝子検索GGRNA ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/GGRNA.v2.jpg
"スクリーンショット")

  - 統合遺伝子検索GGRNA – http://GGRNA.dbcls.jp/
  - 統合TVによる解説動画
    - [GGRNAで遺伝子をGoogleのように検索する](http://togotv.dbcls.jp/ja/20120124.html)
  - ヒトのnanogを検索 – http://GGRNA.dbcls.jp/hs/nanog
  - Accession番号から検索 –  http://GGRNA.dbcls.jp/NM_003380
  - 塩基配列から検索
    - 14bp – http://GGRNA.dbcls.jp/hs/caagaagagattgc
    - 11bp – http://GGRNA.dbcls.jp/hs/caagaagagat
    - 8bp – http://GGRNA.dbcls.jp/hs/caagaaga
  - アミノ酸配列から検索 – http://GGRNA.dbcls.jp/SEHPL+MTCQSC
  - PCRプライマー検索 – http://GGRNA.dbcls.jp/hs/seq%3aagctcattactttatcagtgca+comp%3atgacgtattcactcttctggtt
  - マイクロアレイのプローブ検索 – http://GGRNA.dbcls.jp/1552311_a_at

#### 高速配列検索GGGenome ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/GGGenome_screen2.png
"スクリーンショット")

- 高速配列検索GGGenome – http://GGGenome.dbcls.jp/
  - 統合TVによる解説動画
    - [高速配列検索 GGGenome《ゲゲゲノム》の使い方](http://togotv.dbcls.jp/ja/20131025.html)
    - [GGGenome《ゲゲゲノム》で転写因子結合サイトを検索してゲノムブラウザに表示する](http://togotv.dbcls.jp/ja/20150721.html)
  - ミスマッチやギャップを含む検索 – http://GGGenome.dbcls.jp/hg19/2/TTCACTGACAACATTGAGTA
  - 表計算ソフトで塩基配列検索
    - [Googleスプレッドシート](https://docs.google.com/spreadsheet/ccc?key=0AqoKv30zqpDbdHJpSFI1SzJOZmxjVkYzUXByMFhrWWc&usp=sharing#gid=0) を参照
  - 検索結果をゲノムブラウザ上に表示
    1. UCSCゲノムブラウザ (http://genome.ucsc.edu/cgi-bin/hgTracks)
    2. 「add custom tracks」ボタン
    3. 「http://GGGenome.dbcls.jp/hg19/(検索したい配列).bed」と入力

#### CRISPR設計ウェブサーバCRISPRdirect ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/CRISPRscreen.png
"スクリーンショット")

  - CRISPRdirect - http://crispr.dbcls.jp/
  - 統合TVによる解説動画
    - [CRISPRdirectを使ってCRISPR/Cas法のガイドRNA配列を設計する](http://togotv.dbcls.jp/ja/20140412.html)

#### 参考：各生物種のゲノム ####

  - NCBI Genome - https://www.ncbi.nlm.nih.gov/genome/browse/
  - Ensembl Genomes - http://ensemblgenomes.org/
    - 昆虫はEnsembl Metazoa - http://metazoa.ensembl.org/
    - 植物はEnsembl Plants - http://plants.ensembl.org/

#### おまけ：研究に役立つウェブツール ####

  - siRNA設計ツールsiDirect - http://siDirect2.RNAi.jp/
  - 統合TVによる解説動画
    - [siDirectでsiRNAを設計する2011](http://togotv.dbcls.jp/ja/20110606.html)
    - [siDirectのオプションを使いこなす & shRNAを設計する](http://togotv.dbcls.jp/ja/20110712.html)

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/siDirect_top.jpg
"スクリーンショット")

  - テキスト比較ツール difff《ﾃﾞｭﾌﾌ》(http://difff.jp/)
  - 統合TVによる解説動画
    - [difff《ﾃﾞｭﾌﾌ》を使って文章の変更箇所を調べる](http://togotv.dbcls.jp/ja/20130828.html)

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/difff6.png
"スクリーンショット")

  - Wolfram Alpha (https://www.wolframalpha.com/)
  - 統合TVによる解説動画
    - [WolframAlphaを使い倒す](http://togotv.dbcls.jp/ja/20090626.html)
    - [Wolfram Alpha を高機能関数電卓として使う その1:基本操作編](http://togotv.dbcls.jp/ja/20140404.html)
    - [Wolfram Alpha を高機能関数電卓として使う その2:数式入力編](http://togotv.dbcls.jp/ja/20140604.html)
    - [Wolfram Alpha を高機能関数電卓として使う その3:微分・積分・方程式編](http://togotv.dbcls.jp/ja/20140717.html)

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/Wolframalpha1.png
"スクリーンショット")

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/Wolframalpha2.png
"スクリーンショット")

  - TogoDB (http://togodb.org/)
  - 統合TVによる解説動画
    - [TogoDBの使い方 自分のデータベースを作る](http://togotv.dbcls.jp/ja/20100807.html)

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/TogoDB.png
"スクリーンショット")

  - 研究者の情報を調べるためのツール
    - 研究成果から
      - 日本の博士論文をさがす CiNii Dissertations - http://ci.nii.ac.jp/d/
      - 特許情報プラットフォーム J-PlatPat - https://www.j-platpat.inpit.go.jp/
    - 研究資金から
      - 科研費採択課題 KAKEN - https://kaken.nii.ac.jp/
      - 日本の研究.com - https://research-er.jp/
    - 本人が発信する情報から
      - researchmap - http://researchmap.jp/
      - Facebook - https://www.facebook.com/
      - Twitter - https://twitter.com/

  - 参考:内藤雄樹 編『[今日から使える! データベース・ウェブツール 達人になるための実践ガイド100](https://www.yodosha.co.jp/jikkenigaku/book/9784758103435/)』実験医学増刊 2014年12月発行

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS71/master/03_naito/images/B2uOQ3eCIAAFX9A.png
"スクリーンショット")
