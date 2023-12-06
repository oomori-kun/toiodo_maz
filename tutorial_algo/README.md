# toioを用いて基本技法からアルゴリズムまでを学ぼう
---
## 用意するもの
   * toio™（株式会社ソニー・インタラクティブエンタテインメント） 1台
   * パソコン(現時点ではiPadでは利用できません）
   * 簡易マット（株式会社ソニー・インタラクティブエンタテインメント　　A3版）もしくはtoio™開発用プレイマット
---
## 基本操作
1. 以下の各ステップを読み込んだあと、下図のアイコンを選択（クリック）してステージにマップを描画してください。  
   <img width="100" alt="マップ描画" src="https://github.com/oomori-kun/toiodo_maz/assets/17058514/0cb74e6e-7e8e-49f2-bad7-1bf90b0a0b80" >  

1. その後、下図のアイコンをクリックしてコード作成エリアを表示してください。  
   <img width="80" alt="コードエリア" src="https://github.com/oomori-kun/toiodo_maz/assets/17058514/1c0fc6de-b729-4d49-8b4c-67b9a739f4b3" >  


1. 下の図のように左側に各ステップで使えるブロックが表示されます。  
   特に指示がない限り，ここに表示されているブロックを使ってください。  
   コードは，右側の「スタート位置....」ブロックの続きに作成してください。  
   * 【注意】「スタート位置....」のブロックが実行されると、toioはマップのスタート位置まで移動し、指定された向き（上、下、右、左）に向きます。  
   <img width="500"  alt="コードエリア" src="https://github.com/oomori-kun/toiodo_maz/assets/17058514/db383da4-6a52-4967-8917-90653158678c" >

---
## 基本的な考え方
<img width="600" src="https://github.com/oomori-kun/toiodo_maz/assets/17058514/e3f5c524-9a83-4c56-8311-929cfacee90a" >  

アルゴリズムとデータ構造を体系化しようとすると，上の図のようになると思われる。プログラミングを体系的に学ぶためには，逐次処理，繰り返しや条件分岐などの技法レベルだけでは十分でなく，データ処理技法，基本アルゴリズムとの相互の関係性を学ぶ必要があると思われる。それによってアルゴリズムの設計法を理解するための道筋が付けられて，各種問題解決を行う場合の考え方が身につくのではないかとの仮説のもと，このtutorialを作成している。まだ途中段階であるが今後の実践を通して明らかにしたい。


---
## ステージ1 【基本操作要素技法レベル】

* 以下のリンクを開く場合は次のようにいてください。
  * [Windows] CTRキーを押しながらリンクをクリックする
  * [Mac]　Commandキーを押しながらリンクをクリックする
* マウスに左右のボタンがない場合に、右クリックで（複製、貼り付けなどを行う）サブメニューを開く場合
  * [Macの場合]　Controlキーを押しながらマウスボタンをクリック
* ステージ１の[ガイドブック・テキスト](https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/guidebook/guideBook_Stage1.pdf)は、この左のリンクからダウンロードしてください

1. __逐次，繰り返し，条件分岐の基本__
	1. __一つ前に進もう__  
 		[前に一マス進む](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_1.sb3)

	1. __3つ前に進もう__  
 		[前に3マス進む](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_2.sb3)

	1. __L字の経路に沿って進もう__  
		[L字に進む](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_3.sb3)

	1. __コの字の経路に沿って進もう__  
	  	[コの字に進もう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_4.sb3)

	1. __四角形に沿って進もう__  
		[時計回りに四角形に沿って時計回りに回る（最後はスタート位置に戻ってくる）](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_5.sb3)

	1. __間違い探し：正しく経路に沿って進むよう修正しよう__  
		__【デバッグ】__　[プログラムに間違いは2カ所ある。見つけて修正しよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_6.sb3)

	1. __同じ動作をまとめて見よう　〜まっすぐ進もう__  
 		[1_ⅱを繰り返しを使って簡略化](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_7.sb3)
    
	1. __同じ動作をまとめて見よう　〜L字に進もう__  
		[1_ⅲを繰り返しを使って簡略化 ※繰り返しの入れ子は使わない](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_8.sb3)

	1. __同じ動作をまとめて見よう　〜四角形にそって進もう__  
 		[1_ⅴを繰り返しを使って簡略化　※繰り返しの入れ子は使わない](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_9.sb3)
    
	1. __間違い探し：正しく経路に沿って進むよう修正しよう　その2__  
 		__【デバッグ】__　[間違いは1カ所](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_10.sb3)

	1. __お宝があったらLEDを光らせよう__  
 		[マップにあるお宝を見つけたら，「LED」を光らす](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_11.sb3)  
		マット上にtoioを置いてプログラムをスタートしよう。お宝の上におければLEDが青くひかり，そうでなければ赤く光る

	1. __経路上にお宝があったらLEDを光らせよう__  
 		[経路上にあるお宝を見つけたら，「LED」を光らす](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_12.sb3)  
		toioをスタート位置から動かしてお宝の上を通ればLEDが光る

	1. __お宝が何個あったか数えよう__  
 		[経路上にあるお宝の数を数えよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_13.sb3)  
		toioをスタート位置から動かしてお宝の上を通れば変数「お宝の数」を1づつ増やし，最後に何個としゃべる

	1. __経路上に隠された数字はいくつ？__  
 		[経路上にある数字をしゃべろう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_14.sb3)  
		toioをスタート位置から動かして数字の上を通れば数字をしゃべり，数字がなければ.....う... とうなろう。
		数字は「数字ON/OFF」を押して消しておくと宝探しゲームになる
 
	1. __真下の数字が1だったら右へ，0だったら左へ__  
 		[数字を判断してゴールを目指そう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_15.sb3)  
		toioをスタート位置から一マスずつ動かして真下の数字によって右に回ったり左に回ったりしてゴールまで動かします。  
		どちらに回転するかは次の通り！
		* 数字が0の場合は左に回転
		* 数字が1の場合は右に回転

	1. __間違い探し：正しく経路に沿って進むよう修正しよう　その3__  
 		__【デバッグ】__[経路をたどってゴールしよう　※間違いは1カ所](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_16.sb3)

	1. __ブロックを避けてゴールを目指せ__  
		[ブロックを避けてゴールを目指せ](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_17.sb3)
   
	1. __数字を順番にたどろう！__  
	   	[数字を順番にたどってゴールを目指せ](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_18.sb3)

	1. __これはどんな動きをするかな？__  
 		__【コードを読み解く】__[どのような動作をするかな](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_19.sb3)  
		まずはコードを読んで動きを想像してみよう。どのように動くかメンターの人に話して動かしてみよう。想像通りに動いたかな？

	1. __自由に動きを作ってみよう！__  
 		__【自由課題】__[自由に動きを作ってみよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_1_20.sb3)  
		スタートから初めて、スタートに戻ってくるコード（プログラム）を作ろう。使うことができるブロックは表示されているものです。各1つしかありませんが、ブロックをマウスの右ボタンで選択すると「複製」（コピー）ができます。自由に複製（コピー）して使ってください。  
	   	__数字やお宝のアイテムはマップにありません。動きの命令（一つ前に進む、右に90度回転、左に90度回転）と繰り返し命令だけを使ってうごかしましょう。__  
    		作成したプログラムはメンターの方に説明して動作を確認してもらいましょう。

1. __逐次処理を極めよ！__  
	* ここでは、繰り返し、条件判断は利用せずに、 __逐次処理__ だけでプログラムを作ります。順番を意識して考えましょう。
	* 下の図のように左側に各ステップで使えるブロックが表示されます。  
   	以降、特に指示がない限り，ここに表示されているブロックを __「複製」__ して使ってください。  
   	__「複製」__ は命令ブロックの上でマウスの右ボタンを押してください。メニューが表示され、その中に「複製」があります。
   		<img width="500"  alt="コードエリア" src="https://github.com/oomori-kun/toiodo_maz/assets/17058514/db383da4-6a52-4967-8917-90653158678c" >  
  
	1. __ひたすらまっすぐ進め__  
		 [ひたすらまっすぐゴールまで進もう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_1.sb3)

	1. __間違い探し：ひたすらまっすぐ進めるようにしよう__  
 		__【デバッグ】__[ゴールできるように修正しよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_2.sb3)  

	1. __迷路をゴールしよう__  
    		[迷路をゴールしよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_3.sb3)  

	1. __8の字を描くように進もう__  
    		[8文字を描こう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_4.sb3)  
		スタートから初めて、8の字を描いてスタートに戻ってこよう。  

	1. __間違い探し：8の字を描くように進もように修正しよう__  
 		__【デバッグ】__[ゴールできるように修正しよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_5.sb3)  

	1. __お宝の上を全て通ってゴールに行こう その1__  
    		[お宝の上を全て通って進もう1](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_6.sb3)  
		スタートから初めて、すべてのお宝の上を通ってからゴールに行こう  

	1. __お宝の上を全て通ってゴールに行こう その2__  
    		[お宝の上を全て通って進もう2](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_7.sb3)  
		スタートから初めて、すべてのお宝の上を通ってからゴールに行こう  

	1. __ブロックを避けてお宝を通りながらゴールに行こう__  
    		[お宝の上を全て通って進もう2](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_8.sb3)  
		スタートから初めて、ブロックを避けてながら，すべてのお宝の上を通ってからゴールに行こう  

	1. __間違い探し：ブロックを避けてゴールしよう__  
    		__【デバッグ】__[お宝の上を全て通って進もう2](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_9.sb3)  
		スタートから初めて、ブロックを避けてながらゴールにたどり着けるようにプログラムを修正しよう  

	1. __これはどんな動きをするかな？__  
 		__【コードを読み解く】__[どのような動作をするかな](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_2_10.sb3)  
		まずはコードを読んで動きを想像してみよう。どのように動くかメンターの人に話して動かしてみよう。想像通りに動いたかな？


1. __繰り返しを極めよう！__  
	* ここでは、 __逐次処理__ と __繰り返し処理__ だけでプログラムを作ります。順番を意識すること，同じ処理がどこにあるかを意識して考えましょう。
	* 下の図のように左側に各ステップで使えるブロックが表示されます。  
   	以降、特に指示がない限り，ここに表示されているブロックを __「複製」__ して使ってください。  
   	__「複製」__ は命令ブロックの上でマウスの右ボタンを押してください。メニューが表示され、その中に「複製」があります。
   		<img width="500"  alt="コードエリア" src="https://github.com/oomori-kun/toiodo_maz/assets/17058514/db383da4-6a52-4967-8917-90653158678c" >  

	1. __ひたすらまっすぐ進め__  
		 [ひたすらまっすぐゴールまで進もう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_1.sb3)  
		__繰り返し処理__ の命令を使ってプログラミングしよう  

	1. __間違い探し：ゴールに向かって進もう__  
 		__【デバッグ】__[ゴールできるように修正しよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_2.sb3)  

	1. __迷路をゴールしよう__  
    		[迷路をゴールしよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_3.sb3)  
		同じ処理が繰り返されている場所を見つけて __繰り返し処理__ の命令を使ってプログラミングしよう  

	1. __8の字を描くように進もう__  
    		[8文字を描こう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_4.sb3)  
		スタートから初めて、8の字を描いてスタートに戻ってこよう。  ここでも同じ処理が繰り返されている場所を見つけて __繰り返し処理__ の命令を使ってプログラミングしよう  

	1. __これはどんな動きをするかな？__  
    		__【コードを読み解く】__[どのような動作をするかな](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_5.sb3)  
		まずはコードを読んで動きを想像してみよう。どのように動くかメンターの人に話して動かしてみよう。想像通りに動いたかな？  

	1. __お宝の上を全て通ってゴールに行こう その1__  
    		[お宝の上を全て通って進もう1](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_6.sb3)  
		__繰り返し処理__ の命令を使って，スタートからすべてのお宝の上を通ってからゴールに行こう  

	1. __お宝の上を全て通ってゴールに行こう その2__  
    		[お宝の上を全て通って進もう2](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_7.sb3)  
		__繰り返し処理__ の命令を使って，スタートからすべてのお宝の上を通ってからゴールに行こう  

	1. __ブロックを避けて数字を順番に通りながらゴールに行こう__  
    		[数字を順番に通って進もう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_8.sb3)  
		スタートから初めて、ブロックを避けてながら，数字の上を順番に通ってからゴールに行こう  

	1. __これはどんな動きをするかな？__  
 		__【コードを読み解く】__[どのような動作をするかな](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_9.sb3)  
		まずはコードを読んで動きを想像してみよう。どのように動くかメンターの人に話して動かしてみよう。想像通りに動いたかな？  

	1. __自由に動きを作ってみよう！__  
 		__【自由課題】__[自由に動きを作ってみよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_3_10.sb3)  
		スタートから初めて、ゴールに進むプログラムを作ろう。使うことができるブロックは表示されているものです。各1つしかありませんが、ブロックをマウスの右ボタンで選択すると「複製」（コピー）ができます。自由に複製（コピー）して使ってください。  
	   	__数字やお宝のアイテムはマップにありません。動きの命令（一つ前に進む、右に90度回転、左に90度回転）と繰り返し命令だけを使ってうごかしましょう。__  
    		作成したプログラムはメンターの方に説明して動作を確認してもらいましょう。  

1. __条件分岐を極めよう！__  
	* ここでは、 __逐次処理__ ， __繰り返し処理__ および __条件分岐処理__ を使ってプログラムを作ります。特に，条件によって処理が異なる場合を意識して考えましょう。
	* 下の図のように左側に各ステップで使えるブロックが表示されます。  
   	以降、特に指示がない限り，ここに表示されているブロックを __「複製」__ して使ってください。  
   	__「複製」__ は命令ブロックの上でマウスの右ボタンを押してください。メニューが表示され、その中に「複製」があります。
   		<img width="500"  alt="コードエリア" src="https://github.com/oomori-kun/toiodo_maz/assets/17058514/db383da4-6a52-4967-8917-90653158678c" >  

	1. __目の前の壁をよけよう__  
		 [目の前の壁をよけよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_1.sb3)  
		__条件分岐処理__ の命令を使って，目の前に壁（ブロック）があった場合，下に一マス進むようにプログラミングしよう  

	1. __目の前の壁を避けてゴールへ__  
		 [目の前の壁を避けてゴールへ](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_2.sb3)  
		__条件分岐処理__ と __繰り返し処理__ 　の命令を使って，目の前に壁（ブロック）があった場合，下に一マス進むようにプログラミングしよう  

	1. __これはどんな動きをするかな？__  
		 __【コードを読み解く】__[どのような動作をするかな](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_3.sb3)  
		まずはコードを読んで動きを想像してみよう。どのように動くかメンターの人に話して動かしてみよう。想像通りに動いたかな？
		なお，　__周辺状況（前後左右）の４番目__ というブロックはtoioの進行方向右側に何があるか（ブロック，お宝，数など）がわかる命令です  

	1. __壁（ブロック）を右が側にみながらゴールへ__  
		[壁（ブロック）を右が側にみながらゴールへ](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_4.sb3)  
		__周辺状況（前後左右）の４番目__ というブロックはtoioの進行方向右側に何があるか（ブロック，お宝，数など）がわかる命令です  

	1. __コの字の経路に沿って進もう__  
	  	[コの字に進もう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_5.sb3)  
		__周辺状況（前後左右）の４番目__ というブロックはtoioの進行方向右側に何があるか（ブロック，お宝，数，空など）がわかる命令です  
		回数を指定した繰り返しを使わないで，どのような場面でtoioをどのように動かせばよいかを考えよう  

	1. __真下の数字によって行動を決めよう__  
	  	[真下の数字によって行動を決めよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_6.sb3)  
		toioの真下にある数字が[1]の場合は右に90度回転して一マス進んで，それ以外はそのまま一マス進むことでゴールを目指そう 
		回数を指定した繰り返しを使わないで，どのような場面でtoioをどのように動かせばよいかを考えよう  
	
	1. __間違い探し：ゴールに向かって進もう__  
 		__【デバッグ】__[ゴールできるように修正しよう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_7.sb3)  
		間違いは２カ所あります。間違いを修正して正しくゴールするようにしてください

	1. __真下の数字が１の時にビープ音をならそう__  
	  	__【機能を追加】__[真下の数字が１の時にビープ音をならそう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_8.sb3)  
		すでにマップの一番外を回ってゴールするプログラムがあります。このプログラムにtoioの真下にある数字が[1]の場合はビープ音をならすコードを追加しましょう  

	1. __８の字を永遠に回る__  
	  	[８の字を永遠に回る](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_9.sb3)  
		すでに，toioの正面にあるマスが __ブロック__ あるいは __外__ でければ一マス進むコードを記述している。これに，toioの正面にあるマスが __ブロック__ あるいは __外__ である場合の行動（右に行くか，左に行くか）を決定するコードを追加しよう。
		どのような条件になったら，どちらに回転する必要があるかマップを良く観察してプログラムを考えよう  	
	
	1. __これはどんな動きをするかな？__  
 		__【コードを読み解く】__[どのような動作をするかな](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_10.sb3)  
		まずはコードを読んで動きを想像してみよう。どのように動くかメンターの人に話して動かしてみよう。想像通りに動いたかな？  

1. __基本操作要素技法レベル　総合課題__  
	1. __迷路を解くプログラムを作ろう__  
 		__【総合課題】__[迷路を解くプログラムを作ろう](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_4_11.sb3)  
		迷路をとくプログラムを考えよう  
		基本的な考え方は、常に左側が壁（ブロック）になるように進もう　　

---
## ステージ2 【抽象データ処理レベル】

### ステージ2−1【単純技法レベル】

* 以下のリンクを開く場合は次のようにいてください。
  * [Windows] CTRキーを押しながらリンクをクリックする
  * [Mac]　Commandキーを押しながらリンクをクリックする
* マウスに左右のボタンがない場合に、右クリックで（複製、貼り付けなどを行う）サブメニューを開く場合
  * [Macの場合]　Controlキーを押しながらマウスボタンをクリック
  
1. __最も基本的な技法を知ろう__	
	
	1. __2つの値を比較して小さい方はどっち　その1__  
 		[2つの値を比較して小さい方はどっち　その１](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_S2_1_1.sb3)  
		toioの右側の数値と左側の数値を比較して小さい方に移動しよう  
		toioの右側の数値は __周辺状況（上下左右）の６番目__ の命令（変数）ブロック，　左側の数値は __周辺状況（上下左右）の4番目__ の命令（変数）ブロックで確認できます。  

	1. __2つの値を比較して小さい方はどっち　その2__  
 		[2つの値を比較して小さい方はどっち　その１](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/tutorial_algo/sb3/toiodo_maz_S2_1_2.sb3)  
		toioの右側の数値と左側の数値を比較して小さい方の数値をしゃべろう  
		toioの右側の数値は __周辺状況（上下左右）の６番目__ の命令（変数）ブロック，　左側の数値は __周辺状況（上下左右）の4番目__ の命令（変数）ブロックで確認できます。
		
	1. 2つの値を比較して小さい方はどっち　その3	
	1. 2つの値を比較して大きい方はどっち　その1	
	1. 2つの値を比較して大きい方はどっち　その2	
	1. 2つの値を比較して大きい方はどっち　その3	
	1. 間違い探し：2つの値を比較して大きい方を選べるようにしよう	【デバッグ】
	1. 経路上の最大値を探そう　その1	
	1. 経路上の最大値を探そう　その2	
	1. 経路上の最小値を探そう その1
	1. 経路上の最小値を探そう その2	
	1. 間違い探し：経路上の最大値を選べるようにしよう	【デバッグ】
	1. 経路上の数の合計を求めよう　その1	
	1. 経路上の数の合計を求めよう　その2	
	1. 間違い探し：経路上の数の合計を求められるようにしよう	
	1. 二値の交換　その1	
	1. 二値の交換　その2	
	1. 間違い探し：二値が交換できるようにしよう	【デバッグ】
	1. これは何をするプログラムか考えよう	【コードを読み解く】

### ステージ2-2【基本アルゴリズムレベル】

1. __経路上にある数を探そう__  
一次元配列の探索問題（線形探索，2分探索など）
	1. 数字で描かれた一本道で移動しよう	線形探索
	1. 道に置かれている数字を教えてあげよう	線形探索
	1. 指定した数字のところで止まろう	線形探索
	1. 指定した数字のところ全てで音を鳴らそう	線形探索
	1. 間違い探し　正しく数字のところで音がなるようにしよう	線形探索の間違い探し
	1. このプログラムはどのように動くか説明しよう	線形探索
	1. 数字で書かれた一本道の真ん中に移動しよう	2分探索
	1. 数字で書かれた一本道の真ん中の数字を教えてあげよう	2分探索
	1. 数字で書かれた一本道の真ん中の数字が指定された数だったら教えてあげよう	2分探索
	1. 数字で書かれた一本道の真ん中の数字が指定された数字より大きいかどうかを教えてあげよう	2分探索
	1. 数字が指定された数より大きいときは左側の真ん中へ移動しよう	2分探索
	1. そのときの数字が指定された数と同じか教えてあげよう	2分探索
	1. 数字が指定された数より小さいときは右側の真ん中へ移動しよう	2分探索
	1. そのときの数字が指定された数と同じか教えてあげよう	2分探索
	1. 2分探索
	1. 2分探索	

1. __キューとスタックの動きを理解しよう__	
	1. a
	1. b
	1. c
	1. d	
	1. e	
	1. f
	1. g
	1. h

1. __迷路を解くプログラムを作ろう__	
	1. __深さ優先探索__	グラフの探索
	1. __幅優先探索__ 	グラフの探索

## ステージ3【問題解決概念レベル】
### ステージ3-1【アルゴリズム設計法】
1. __最適計画法__

