---
name: 機能リクエスト
description: 新機能や改善の提案を行うためのテンプレート
title: "[提案] タイトルを記入してください"
labels: ["enhancement"]
assignees: []
---

body:
  - type: textarea
    attributes:
      label: 概要
      description: どのような機能が必要か簡潔に記載してください。
      placeholder: 例）CSV出力機能が欲しい
    validations:
      required: true

  - type: textarea
    attributes:
      label: 実現したいこと
      description: なぜその機能が必要なのか、どのような課題を解決できるのかを記載してください。
    validations:
      required: true

  - type: textarea
    attributes:
      label: 参考資料
      description: 参考になりそうな情報やURLがあれば記載してください。
    validations:
      required: false