---
home: true
heroImage: /logo.svg
actionText: はじめる
actionLink: /guide/

altActionText: 詳しく見る
altActionLink: /guide/why

features:
  - title: 💡 高速なサーバーの起動
    details: ネイティブESMを介したオンデマンドにファイル配信。バンドルが不要。
  - title: ⚡️ 軽量・高速なHMR
    details: ホットモジュール置換（Hot Module Replacement、HMR）によりアプリサイズに依存せずに高速。
  - title: 🛠️ リッチな機能
    details: デフォルトでTypeScript、JSX、CSSなどをサポート。
  - title: 📦 ビルドの最適化
    details: 複数ページとライブラリモードをサポートする設定済みのRollupビルド。
  - title: 🔩 ユニバーサルなプラグイン
    details: 開発とビルドでRollup-supersetプラグインインターフェイスを共有。
  - title: 🔑 完全に型付けされたAPI
    details: 完全に型付けされたTypeScriptにより柔軟なプログラム可能なAPIを提供。
footer: MIT Licensed | Copyright © 2019-present Evan You & Vite Contributors
---

<div class="frontpage sponsors">
  <h2>Sponsors</h2>
  <a v-for="{ href, src, name } of sponsors" :href="href" target="_blank" rel="noopener" aria-label="sponsor-img">
    <img :src="src" :alt="name">
  </a>
  <br>
  <a href="https://github.com/sponsors/yyx990803" target="_blank" rel="noopener">GitHubでスポンサーになる</a>
</div>

<script setup>
import sponsors from './.vitepress/theme/sponsors.json'
</script>
