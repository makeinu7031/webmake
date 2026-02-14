ホームページ作成、公開用のリポジトリです

【フォルダ構成】
website/
├── index.html
├── aboutme.html
├── something.html
├── readme.txt
└── assets/           # 静的アセットを一元管理
    ├── css/          # スタイルシート
    │   ├── main.css      (トップページ)
    │   ├── about.css     (自己紹介ページ)
    │   └── something.css   (雑多ページ)
    ├── js/           # JavaScript
    │   └── menu.js
    └── images/
        ├── icons/    # ナビゲーション用アイコン
        └── content/  # コンテンツ用画像

【About me ページの構成】
・プロフィール画像 … .profile-section__img 内の img の src / alt を変更
・保有スキル 9 アイコン … assets/images/content/ にアイコン画像を置き、
  .skill-icons__item の各 img の src / alt を変更（9個）
・写真グリッド（Instagram風）… .photo-grid__item をコピーして src / alt を書き換え。
  枚数は自由（3列で自動的に並びます）