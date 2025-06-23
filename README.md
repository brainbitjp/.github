# .github

## 初期設定

git subtree add --prefix=.github https://github.com/brainbitjp/.github.git main --squash

## 最新内容の取込

git subtree pull --prefix=.github github-templates main --squash

git fetch github-templates

## 最新内容の反映
git subtree push --prefix=.github https://github.com/brainbitjp/.github.git main
