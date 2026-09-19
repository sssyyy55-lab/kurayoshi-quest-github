倉吉クエスト アプリアイコン

・apple-touch-icon.png：iPhoneホーム画面用（180×180px）
・icon-512.png：Webアプリ／PWA用（512×512px）
・app-icon-1024.png：保管・App Store素材用（1024×1024px）

iPhoneホーム画面用の設定：
apple-touch-icon.pngをindex.htmlと同じ場所へ置き、
HTMLの<head>内に次の1行を追加します。

<link rel="apple-touch-icon" href="apple-touch-icon.png">

iPhoneのSafariでWebサイトを開き、共有ボタンから
「ホーム画面に追加」を選ぶと、このアイコンが表示されます。
