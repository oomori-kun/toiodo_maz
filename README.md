# toiodo_maz

toioDoで使う場合，以下のURLでアクセスする

### 手順
1. エクセルブック（map.xlsm）とCSVファイル(map.csv)ををダウンロード（マクロは有効にしてください）して，「マップ設定シート」でマップを作成
   * マップの各セルにアイテムをプルダウンメニューから設置
   * 一括で”空”を入れる場合は【初期化】ボタンを押す
   * 全マスに座標数字（10の桁は行，1の桁は列を示す）を入れる場合は【座標数字設定】ボタンを押す
   * toioDoにマップ情報を設定するためのCSVファイル（UTF-8形式）に保存する場合は【CSV出力】を押す。その場合，map.csvファイルが上書き保存される
   
1. 次のURLにアクセスする

   [迷路プログラミングの環境](https://toio.github.io/toio-visual-programming/beta/?project=https://github.com/oomori-kun/toiodo_maz/blob/main/toiodo_maz.sb3)
   
1. ステージ上の「マップデータ読み込み」ボタンを押す
2. ステージ左側に表示されるリストからデータの読込（右ボタン）を選択して，CSVファイルの1列目のデータを読み込む
3. ステージ右側に表示されるリストからデータの読込（右ボタン）を選択して，CSVファイルの2列目のデータを読み込む
4. マップ作成ボタンを押す
5. 作成するプログラムは，スプライト（プログラム）に対して行う。その際に（Scriptを各エリアで「＝」ボタンを押すとサンプルと説明が真ん中に出てくる
6. プログラム作成後にステージ上にある「スタート」ボタンを押すと実行される

### 使えるブロックの説明
