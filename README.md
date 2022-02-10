# Summary of Sakura Editor settings.

サクラエディタの各種設定  

**ダウンロード**  
[https://sakura-editor.github.io/](https://sakura-editor.github.io/)  
最新版ダウンロードの「インストーラ、パッケージダウンロード」ページに飛ぶ。  
latest(2022/02/11時点ではv2.4.1)のsakura-tag-v2.4.1-build2849-ee8234f-Win32-Release-Installer.zipをダウンロード  
ダウンロードしたら解凍して中身の.exeファイルを実行する。  
※事前に解凍ソフトインストール必要  
※事前にWindowsのエクスプローラーのオプションで拡張子を表示させる設定にする  
　  

**インストール時**  
<img src="https://evofan.github.io/test_sakura_editor/screenshot/pic_sakura_install.jpg" width="50%">  
デスクトップにサクラエディタのアイコンを置きたい場合はチェックする。  
（タスクバーにピン留めするした後は削除しても可）  

またファイルを右クリックして「SAKURA Editorで開く」が出来るようにする。  
（.htmlファイルをダブルクリックすると通常Chromeで立ち上がるため）  
　  
   
**インストール後**  
設定を変えて.htmlファイルや.cssファイルを編集する時に、より見易くなるようにする。  

上部メニューから「設定」→「タイプ別設定一覧」を選択する。  
<img src="https://evofan.github.io/test_sakura_editor/screenshot/pic_sakura1.jpg" width="50%">  

新しく開いた設定画面で「HTML」を選択し、右の「設定変更」を押す。
<img src="https://evofan.github.io/test_sakura_editor/screenshot/pic_sakura2.jpg" width="50%">  

「スクリーン」タブのレイアウト→折り返し方法「右端で折り返す」を選択する。  
右側のファイル拡張子の入力欄に、既に入力してある項目に追加で「`,css,js`」を追加する（半角）。  
（ピリオドでなく、カンマで区切る）  
<img src="https://evofan.github.io/test_sakura_editor/screenshot/pic_sakura3.jpg" width="50%">  

先ほどのスクリーンタブの右の「カラー」タブを選択する。  
右側のコメントスタイルで、  
ブロック型(F)欄に　`<!--`  その右の(T)欄に `-->`  を入力する（半角）。  
ブロック型(A)欄に　`/*`  その右の(Z)欄に `*/`  を入力する（半角）。  
行型(M)欄に `//` を入力する（半角）。  
<img src="https://evofan.github.io/test_sakura_editor/screenshot/pic_sakura4.jpg" width="50%">  
　  

**サンプルのtest.htmlのダウンロード方法**  
このページ上部のtest.htmlを開いた後に、  
RAWボタンを押してコードが表示されたら右クリック→「名前を付けて保存」でデスクトップに保存する。   

又はtest.htmlを開いて1～32行目までをコピーして、サクラエディタを新規で立ち上げ「編集」→「貼り付け」後、  
「ファイル」→「名前をつけて保存」でtest.htmlの名前でデスクトップに保存する。  

サンプルのtest.htmlをサクラエディタで開いてコメント3カ所が緑色になっていればok。  
<img src="https://evofan.github.io/test_sakura_editor/screenshot/pic_sakura5.jpg" width="50%">  

