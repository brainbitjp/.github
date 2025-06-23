---
name: 質問・相談
description: その他の質問や相談を行うテンプレート
title: "[質問] タイトルを記入してください"
labels: ["question"]
assignees: []
---

body:
  - type: textarea
    attributes:
      label: 質問内容
      description: わからない点や確認したい内容を記載してください。
      placeholder: 例）このAPIの認証方式について詳しく知りたいです
    validations:
      required: true

  - type: textarea
    attributes:
      label: 試したこと・調査内容
      description: 事前に自分で調べたことや試したことがあれば記載してください。
    validations:
      required: false