# Study+
自分に合った学びを支える、シンプルな学習ダッシュボード。

## 現在の機能
- 学習タスクの追加・完了管理
- 集中タイマー
- テスト得点の記録と教科別表示
- 志望校・週間学習目標
- ブラウザ内保存とJSONバックアップ/復元
- 学習の考え方を案内するサポートモード

## GitHub Pagesで公開
1. Repository Settings → Pages を開く
2. Build and deployment の Source を「GitHub Actions」に設定
3. Actions タブで「Deploy Study+ to GitHub Pages」の実行状況を確認
4. 成功後、Settings → Pages に表示されるURLからアクセス

## 現時点の制限
このバージョンはブラウザ内にデータを保存します。別端末との同期・ログイン・実際の生成AIによる問題解説はまだ接続されていません。APIキーや秘密情報をフロントエンドに埋め込まないでください。AI機能には、認証・利用制限を備えたサーバー側API（例：Supabase Edge Function）と、別途設定したAIプロバイダーの認証情報が必要です。
