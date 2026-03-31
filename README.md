💻 「ボンアイエフ（Bon IF）」Webサイト クローン開発プロジェクト

🔗https://eunni0103.github.io/bon/

開発時期 : 2026.02

技術スタック : HTML5, CSS3, Vanilla JavaScript, JSON 

---

概要

韓国の飲食フランチャイズ「ボンアイエフ」の公式サイトを参考に、Webサイトのクローン開発を行いました。
フレームワークを使用せず、Vanilla JavaScriptによる動的なデータ制御とUI実装を行い、Web開発の基礎への理解を深めることを目的としています。

💡 ご確認方法 > 「ブランド ＞ 本弁当（ボンべんとう） ＞ メニュー紹介」の順に進んでいただくと、動的に実装されたメニュー詳細ページをご確認いただけます。

---

🛠 担当機能

メニュー詳細ページの動的レンダリングおよびUI実装

- URLのクエリパラメータ（?id=）を解析し、JSONデータを取得 
- Fetch APIを用いた非同期データ処理の実装 
- 取得データに基づいたDOM生成および画面への動的表示  

---

✨ 主な実装ポイント

動的レンダリング
- メニュー情報（画像・名称・構成・NEWバッジ）を条件に応じて表示  
- リアルタイム価格計算
- チェックボックス操作に応じて合計金額を即時更新  

UI/UX改善
- Flexboxによるレイアウト設計  
- タブ切り替え（詳細 / 原産地 / アレルギー情報）をクリックイベントで実装

---

🎨 プレビュー (Preview)

<img width="1250" height="860" alt="1" src="https://github.com/user-attachments/assets/5d264fb3-8b86-42f0-ba97-08c5d91841e5" />



<img width="1156" height="852" alt="2" src="https://github.com/user-attachments/assets/67a19be8-7a2b-49c7-bc6a-61cff67144cc" />


