# koenji_app

■ サービス概要
高円寺を楽しく回りたい方に
宝探しのような体験を提案する
「高円寺×ジオキャッシング」体験サービスです

■メインのターゲットユーザー
高円寺を楽しみたい人
探索好きな人
高円寺に初めて来る20〜30代くらいの男女、カップル、グループ

■ユーザーが抱える課題
- 高円寺を遊び尽くしたい
- 新たなお店や場所と出会いたい

■解決方法
高円寺にある、数々の素敵な場所。出会ったお店での素敵な料理などの
お宝（写真）をユーザーに投稿していただき、それらを探しながら巡るという体験を経て高円寺の色々な場所を発見したり、出会うことができる。

■実装予定の機能（以下の例は実際のアプリの機能から一部省略しています）
未ログインユーザー
- 新規ユーザー登録機能
- ログイン機能
- 利用規約
- プライバシーポリシー
- ジオキャッシング一覧機能
（お題の写真が見れる）

ログインユーザー
- ジオキャッシングの投稿機能
- 見つけた機能（誰かのお宝を見つけた時に押すボタン）
- コメント機能
- ログアウト機能
- パスワードリセット機能

管理ユーザー
- ユーザー管理（一覧、詳細、編集、削除、検索）
- 投稿管理（一覧、詳細、編集、削除）

■なぜこのサービスを作りたいのか？
私は高円寺に住んでみて、高円寺のことが好きになりました！
高円寺には風情のある街並み。情緒ある下町感。「純情通り商店街」をはじめたくさんの商店街。「高架下」に並ぶ赤提灯の灯る飲み屋などとにかくたくさんの素敵なスポットやお店があります！
中には隠れたようにひっそりと佇むお店もあったり、アングラ感もあり、宝探しのようにもっと色んなところを歩き回ったりして冒険のように楽しめたら面白いのではと思い、このサービスを思いつきました！

■スケジュール
企画〜技術調査：5/6〆切
README〜ER図作成：5/13 〆切
メイン機能実装：5/13-6/17 〆切
β版をRUNTEQ内リリース（MVP）：6/17〆切
本番リリース：6月末

■技術選定
【バックエンド】
- Rails7
【インフラ】
- fly.io
【データベース】
- PostgreSQL
【フロントエンド】
- React
- Tailwind CSS
- daisyUI

■画面遷移図
https://www.figma.com/file/hLMdCqvHwsF3PRn6pSZTEs/%E7%84%A1%E9%A1%8C?type=design&node-id=0%3A1&t=Z5FObEpGzAZUNS8q-1