# wcp1-5
## メインビジュアル

### 画像の取り入れ方
	background-image: url (画像までのパス)
	background-size: 値; / 画像の幅　画像の高さ;
	background-position: top/right/bottom/left/center/⚪︎⚪︎px,%

#### background-sizeのサンプル
	/* 元の画像の大きさを維持したまま、背景の表示領域を埋めるまで何度も繰り返すように表示 デフォルト */
	background-size: contain;
	/* 画像の幅と高さの比率は固定されたまま、背景の表示領域を覆うように表示 */
	background-size: cover;
	/* 表示領域の幅100%高さ100%で表示（縦横比は無視） */
	background-size: 100% 100%;
	/* pxを指定して表示 */
	background-size: 24px auto

### 背景色の透過
	- rgba色：0〜255までの色の濃さを示す数値を入力
	  rgb(0,0,0):black
	  rgb(255,255,255):white
	  a(Alpha値):透明0〜1不透明

### 文字の中央揃え
	text-align: center;
	＊垂直：paddingにて調整

### 任意の改行　<br>

## 確認問題
問1 3.
問2 color: red;
	color: #FF0000
	rgb(255,0,0)
問3 2.
