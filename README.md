# Vue 3 + Vite

- 構築
  - プロジェクト作成
    - npm init vite@latest
  - sass インストール
    - npm install sass
  - storybook インストール
    - npm install @storybook/vue3

- コーディングルール
    - 命名規則
        - html, css
            - id: ケバブ
            - class: スネーク&ケバブ（全小文字）
                - 単語はスネークで繋げる
                - サイズ、色等のオプション的な意味合いのものはケバブで繋げる
                - 例: radio_list-vertical, radio_list-horizontal
            - 定数: スネーク（全大文字）
        - js
            - 関数: キャメル（頭大）
            - 変数: キャメル（頭小）
            - 定数: スネーク（全大文字）