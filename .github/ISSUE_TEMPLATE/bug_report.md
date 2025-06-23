---
name: バグ報告
about: バグを報告するためのテンプレート
title: '[バグ] タイトルを記入してください'
labels: ["bug"]
assignees: ''

---

body:
  - type: textarea
    attributes:
      label: 概要
      description: バグの内容を簡潔に記載してください。
      placeholder: 例）保存ボタンを押してもデータが保存されません
    validations:
      required: true

  - type: textarea
    attributes:
      label: 再現手順
      description: バグを再現する手順を記載してください。
      placeholder: |
        1. ○○画面を開く
        2. 「保存」ボタンをクリック
        3. エラーが表示される
    validations:
      required: true

  - type: input
    attributes:
      label: 使用環境
      description: バグが発生した環境を記載してください。
      placeholder: OS、ブラウザ、端末名など
    validations:
      required: false

  - type: textarea
    attributes:
      label: 期待される動作
      description: 本来どうなるべきだったかを記載してください。
    validations:
      required: false

  - type: textarea
    attributes:
      label: 補足情報
      description: スクリーンショットやログなど、参考になる情報があれば記載してください。
    validations:
      required: false
