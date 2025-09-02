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
4. 労力と品質の相関
5. まとめ: AI時代のメンタルモデル

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
- 僕なりにもう一段分解してみる
  - <span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">検査的保証</span>: 問題がないことを検査すること
  - <span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">予防的保証</span>: 問題発生の予防に務めること
  - <span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">対処的保証</span>: 問題が起きた時に対処すること

---

# エンジニアリングにおける品質保証

より狭義な保証の定義

- **検査的保証**: 外部品質を満たしているか
- **予防的保証**: 内部品質を満たしているか
- **対処的保証**: 問題発生時に対処できるか

---
layout: section
---

# 誰が品質を保証するのか

AI時代の品質保証は誰が担う？

---
layout: fact
---

## 品質保証を担うのは...<br>AI？エンジニア？

---

# 誰が品質を保証するのか

エンジニアリングにおける品質保証（再掲）

- **検査的保証**: 外部品質を満たしているか
- **予防的保証**: 内部品質を満たしているか
- **対処的保証**: 問題発生時に対処できるか

---

# 検査的保証: 外部品質を満たしているか

事業・経営者・クライアントの要求を満たしていることの検査

- AIが担える
  - 言語化された要求を元にしたテストやテストケースの作成
- AIが担えない
  - 要求の<span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">言語化</span>（高度なエンジニアリング知識と作業者の時間が必要）
  - リリース可否<span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">判断</span>

---

# 予防的保証: 内部品質を満たしているか

内部品質の診断は高度な専門知識と組織的トレードオフ判断が必要

- AIが担える
  - 設計の壁打ちやルールに基づくチェック
- AIが担えない
  - 内部品質の<span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">評価</span>

---

# 対処的保証: 問題発生時に対処できるか

品質保証に限らずあらゆる契約は、信頼関係の上に成り立つ

- AIが担える
  - 原因の特定や対処方法の提案
- AIが担えない
  - 問題の発見や対処に対する<span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">主体性</span>
  - 「問題に対処できる能力を有する」という<span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">信頼関係</span>

---

# 品質を保証するのに必要な要素

_労力は外注できるが、能力は外注できない_ by t-wadaさん

- 外部品質を満たしているか -> **言語化、判断**
- 内部品質を満たしているか -> **評価**
- 問題発生時に対処できるか -> **主体性、信頼関係**

これらに必要なのは「労力」ではなく「**能力**」

---
layout: fact
---

## 品質保証はエンジニアが担う<br>AIは品質保証にまつわる労力を担う

---
layout: section
---

# AIの労力と品質の相関

AIとエンジニアの労力分担を考える

---

# AIの労力と品質の相関

AIの労力を駆使するには、指示労力が必要

- AIの労力が増えると品質は落ちがち
- スケールしつつ品質を保つのは丁寧な指示（プロンプトやコンテキスト）が必要
- 指示を丁寧にするほど、「指示労力」が必要になる

<div class="flex justify-center mt-10 gap-10">
  <img src="/quality-cost.png" class="w-90">
  <img src="/management-cost.png" class="w-90">
</div>

---
layout: fact
---

## 指示労力をケチると品質が低下する

---
layout: fact
---

## AIの労力 >>> 指示労力<br>でなければ生産的ではない

---
layout: fact
---

## 品質と生産性両方得るには<br>これらを意識しなければならない

---
layout: section
---

# まとめ

AI時代のメンタルモデル

---

# AI時代のメンタルモデル

品質と生産性のバランスが重要

- 「品質」にも「保証」にも色々あり、総じて品質保証は我々エンジニアの仕事
- 品質保証に関わる労力をAIに任せよう
- 「丁寧な指示」と「AIに委託する労力 >>> 指示労力」を意識しよう

<span class="font-bold" v-mark="{ type: 'underline', color: 'red' }">我々エンジニアはこれからも専門家であり続けなければならない</span>

---
layout: fact
---

我々が実現すべきこと:

_あなたは高い技術力を持ったテックリードです。<br>AI Agentを使いこなして高速な実装と高い品質を両立させて下さい。_

---
layout: section
---

# End
