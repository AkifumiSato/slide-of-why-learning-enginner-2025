---
theme: default
background: https://images.unsplash.com/photo-1530053969600-caed2596d242?q=80&w=2574&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
class: text-center
highlighter: shiki
lineNumbers: false
colorSchema: "dark"
drawings:
  persist: false
transition: slide-left
title: 「あなたは高い技術力を持ったテックリードです。AI Agentを使いこなして高速な実装と高い品質を両立させて下さい。」
mdc: true
---

## _あなたは高い技術力を持ったテックリードです。<br>AI Agentを使いこなして高速な実装と高い品質を<br>両立させて下さい。_

in LayerX event 202509

---

# Profile

<div class="pb-5">
  <img src="https://avatars.githubusercontent.com/u/25711332?v=4" width="100" height="100">
</div>

```jsonc
// profile.jsonc
{
  "name": "佐藤 昭文",
  "alias": ["akfm_sato", "あっきー"],
  "job": "フロントエンドエキスパート",
  "tags": ["Next.js", "React", "Test", "リーン開発"],
  "sns": {
    "x": "akfm_sato",
    "zenn.dev": "akfm",
  },
}
```

---

# Agenda

品質保証の観点から見た我々エンジニアの在り方について

1. 品質とは
2. 保証とは
3. 誰が品質を保証するのか
4. 生産性と品質のバランス
5. AI時代のエンジニアメンタルモデル

---
layout: section
---

# 品質とは

エンジニアリングにおける品質

---

# 品質とは

_品質とは誰かにとっての価値である_ by ワインバーグ氏

- 品質: 見る人によって定義が異なる
  - エンドユーザー、営業、企画、デザイナー、開発、QA...
- t-wadaさんの[質とスピード](https://speakerdeck.com/twada/quality-and-speed-2022-spring-edition?slide=13)が参考になる
  - SQuaREモデル
  - **外部品質**と**内部品質**で考えてみる

---

# 外部品質

ユーザーにとっての価値

- 外部品質: 安定性、ユーザビリティ、パフォーマンス、セキュリティ、etc...
- エンジニアだけでは達成できない。しかし<span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">エンジニアが尽力しなければ達成できない</span>

---

# 内部品質

エンジニア（の仕事）にとっての価値

- 内部品質: 変更容易性、可読性、拡張性、再利用性、etc...
- エンジニアが達成すべきもの。しかし<span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">達成が非常に難しい</span>
  - 高度な知見や熟達した経験が必要とされる
  - 問題になるまで投資されずらい

---
layout: section
---

# 保証とは

エンジニアリングにおける保証

---

# 保証とは

一般的な保証の定義

- [保証の定義](https://kotobank.jp/word/%E4%BF%9D%E8%A8%BC-12060)
  - > 間違いがない、大丈夫であると認め、責任をもつこと。
- 予防的意味: 問題が起きないよう予防に務めること
- 対処的意味: 問題が起きた時に対処すること

---

# エンジニアリングにおける保証

より狭義な保証の定義

- 予防的意味
  - 外部品質を常に満たすこと
  - 内部品質を満たし、高速な開発を実現・維持すること
- 対処的意味
  - 問題が発生した時に早期に解決すること

---
layout: section
---

# 誰が品質を保証するのか

AI時代の品質保証は誰が担う？

---

# 生成AIの本質

_労力は外注できるが、能力は外注できない_ by t-wadaさん

- 生成AIはあくまで確率的に確からしいことを予想するだけ
- 保証は人や仕組みに対して期待されるもの
- 社会はまだAIを人や仕組みとは一線を画すものとみなされてる

---

# 保証とは信頼関係の上に成り立つ

ビジネスにおけるあらゆる契約は、信頼の上に成り立つ

- 市場には、保証できそうな人・信頼できる人が必要
  - 現時点でAIはこれに見合わない
  - 一定リスクを背負っている人、信頼を得てる人
  - 信頼できる検査ができる人、信頼できる仕組みが作れる人

---
layout: fact
---

## エンジニアリングの品質保証は<br>エンジニアが担うことが期待されてる<br>（少なくとも今日時点では）

---
layout: section
---

# 生産性と品質のバランス

---
layout: section
---

# AI時代のエンジニアメンタルモデル

---

