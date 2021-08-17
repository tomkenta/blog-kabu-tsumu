# 設計


## 要件
- ブログが投稿できること
- ブログが閲覧できること
- ブログのリストができること
  - 新規投稿順に並ぶこと
- プロフィールが表示されること
  - Twitter へのリンク
- 広告が表示されること
- カテゴリ毎に分けられること

### データ設計
- Post
  - id
  - title
  - top_image
  - body
  - created_date
  - modified_date
- Post_Category (不定)
  - id
  - post_id
  - category_id
- nCategory
  - id
  - name
- Profile (single)
  - id
  - name
  - twitter_link
  - biography
  - comment
- Advertise
  - id
  - title
  - image
  - body
  - link

### 画面設計

- 管理画面
  - 各データごとの画面を作る