# Hi there! I'm LineTeo 👋

現在、プログラミング訓練課程にて **Java** および **Python** を学習しています。
学んだ技術のアウトプットとして、以下の演習プログラムを公開しています。

## 🚀 習得スキル
- **Language:** Java / Python / HTML / CSS
- **Framework:** Java Servlet / JSP
- **Topics:** オブジェクト指向 / ファイル入出力 / Webアプリ開発 / 機械学習

## 📚 学習・演習カリキュラム

### 1. Webデザイン演習 (1/15 - 1/22)
Webサイトの構造とデザインの基礎を学習しました。
- [自己紹介ページ](https://github.com/LineTeo/WebDesign)


### 2. Javaプログラミング基礎・実践 (1/23 - 3/22)
文法からオブジェクト指向、Webアプリ（サーブレット・JSP）を学習しています。
- [Java基礎演習リポジトリ](https://github.com/LineTeo/java-practice2026)
  <table>
    <tr>
      <td>
        <b>献立プログラム</b>：基本構文の確認、ファイル入出力の実装<br>
        クラス、パッケージ等の演習
      </td>
      <td>
        関連ソース未アップロード
      </td>
    </tr>
    <tr>
      <td>
        <b>戦車戦ゲーム</b>：オブジェクト指向の概念を応用した開発<br>
        課外学習としてOptunaライブラリを使った機械学習によるアルゴリズム強化を実施
        （Python学習の項を参照）
      </td>
      <td>
        <img width="200" alt="戦車戦ゲーム" src="https://github.com/user-attachments/assets/81434947-8277-4ccf-a8c0-f4ae1284945d">
      </td>
    </tr>
  </table>

- [Java Servlet Webアプリ演習](https://github.com/LineTeo/servlet_and_JSP_2026.git)
  <table>
    <tr>
      <td>
        <b>実践編１Servlet</b>：Servletを用いた献立検索プログラムWebアプリケーション<br>Servletのみによる実装(init(),doGet(),doPost<br>
        <b>実践編２JSP</b>：ServletからJSPにforwardして表示のみをJSPで行う方式にアップデート。
      </td>
      <td>
        <img width="200" alt="献立検索プログラム" src="https://github.com/user-attachments/assets/03cf2fa8-ea62-4a2c-954d-526de8a80314">
      </td>
    </tr>
    <tr>
      <td>
        <b>市町村人口調査プログラム</b>：APIによる外部サーバーデータへの参照<br>上記演習の発展型<br>- e-Statからの市町村人口データの取得<br>- 取得データをサーバー上で加工
      </td>
      <td>
        <img width="250" alt="image" src="https://github.com/user-attachments/assets/c6300bd0-b22f-4a43-95b3-e665b8df07e2" />
      </td>
    </tr>
    <tr>
      <td>
        <b>実践編３ セッションスコープ</b>：セッションスコープを使った演習<br>ユーザー登録～ログイン～ユーザー情報表示前のミニアプリ作成<br>
        - データファイルの有無やユーザーの重複等をチェックして二重登録を回避<br>
        - データへのアクセスは、DAO介してのみ行う<br>
        - CSVデータの扱いをOpenCSVを使うことで、改行やカンマなどの問題を回避 
      </td>
      <td>
        <img width="140" alt="image" src="https://github.com/user-attachments/assets/fc047543-1e70-43a3-8dd2-32a2efaa98f7" />
        <img width="140" alt="image" src="https://github.com/user-attachments/assets/d3d1ab17-4a37-4128-8301-3bcb9d07e935" />
      </td>
    </tr>
    <tr>
      <td>
        <b>実践編４ JDBCプログラム</b>：MapTweetアプリの作成<br>
        - テキストの演習のつぶやきアプリを参考に、さらに場所を地図で示す機能を追加<br>
        - 前項のログインアプリと合体したアプリを作成<br>
        - 地図ライブラリに Leaflet.js + OpenStreetMap（無料・APIキー不要）を使用<br>
        - ツイートとユーザーデータをデータベースで管理するため、DAOをJDBC化<br>
        (初版はデータをXMLファイルに保存。JDBC化後も内部にXML用コードは残してある）<br>
        https://github.com/LineTeo/MapTweet
      </td>
      <td>
         <img width="140" alt="image" src="https://github.com/user-attachments/assets/43d49686-b937-4401-b007-16cdd10ee768" />
         <img width="140" alt="image" src="https://github.com/user-attachments/assets/45119ed7-9954-4da4-a5a8-d844bbebe1fb" />
      </td>
    </tr>
  </table>

### 3. Pythonプログラミング基礎・実践 (3/23 -)
<b>基礎編演習</b><br>
- [Pythonプログラム演習](https://github.com/LineTeo/Python_Practice1.git)<br>
<table>
  <tr>
    <td>
    <b>人口データ解析</b><br>
        1.JAVAの演習と同様に、eStatから、こんどは人口データのExcelファイルをダウンロードするプログラムを作成<br>
        2.ダウンロードした複数のExcelファイルから条件にあったデータ（市町村）を抽出し、グラフ化するプログラムを作成
    </td>
    <td>
        <img width="400" alt="image" src="https://github.com/user-attachments/assets/4bbb24ad-3372-4eaf-8e2f-566f18cb36f7" />
    </td>
 </tr>
 <tr>
   <td>
    <b>気象データ解析</b><br>
        1.過去25年の気象データから平均気温のトレンドを分析<br>
        - 季節による気温変動や日照時間などの天気依存成分をFFTやBPF、回帰分析で除去処理してグラフに表示する<br>
        2.バイブコーディング<br>
        - 1のプログラムから日照時間の季節変動補正を理論値ベースに変更し、回帰係数も月ごとに変えたプログラムをAIに対してゼロから式やコードを使わず、言葉だけのやり取りでコーディングまで実施
   </td>
   <td>
        <img width="400" alt="image" src="https://github.com/user-attachments/assets/32fc854b-10ec-4c17-8fd0-a894e2ca1270" />
   </td>
  </tr>
 <tr>
   <td>
    <b>Webアプリ演習</b><br>
        1.過日本語を表示して英単語を書かせる。tkinterと辞書の使い方演習<br>
        2.1をflaskを使ったWevアプリにする演習<br>
   </td>
   <td>
     <img width="400" alt="image" src="https://github.com/user-attachments/assets/c4244082-9238-4427-bd22-cfbdcd362204" />
   </td>
  </tr>
</table>  

<b>自主課題演習</b><br>
- [Pythonで機械学習](https://github.com/LineTeo/Python_ml-project.git)   
<table>
  <tr>
      <td>
        <b>自主課題</b><br>
        JAVA演習で作成した戦車ゲームのAIをOptunaによる機械学習で強化するプログラムを作成<br>
        　<b>JAVA側</b><br>
          行動判断基準のパラメータ化と、外部ファイルからそのパラメータを設定できるように構成を修正<br>
          指定回数ゲームを繰り返し、勝敗を記録して勝率を求めて返すような起動プログラムを作成<br>
          <b>Python</b><br>
          Optunaを使い、サンプラーはCMA-ESモデルとして算出したパラメータ候補値を外部ファイルに保存<br>
          そのファイル名を引数にしてJAVAプログラムを自動対戦モードで起動し、5000回対戦した時の敵側の勝率を取得<br>
          勝率をモデルにフィードバックし、新たなパラメータを算出するというループを1000回繰り返す。
      </td>
      <td>
        学習によって、同じ条件では勝率を劇的に改善（10%以下　→　ほぼ100％）でき、Optunaによる機械学習の流れも理解できた。
      </td>
    </tr>
</table>
### 4. データベース基礎 (5/23 -)
### 5. ソフトウエア開発演習 (6/8 -)

---
📫 **Contact:** [あなたのメールアドレスやSNSがあれば]
