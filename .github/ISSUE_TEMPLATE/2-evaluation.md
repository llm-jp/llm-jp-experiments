---
name: 評価
about: 評価用Issue Template
title: "[評価] - 簡単な説明"
labels: evaluation
assignees: ''

---

# Overview

1文程度で実験の概要を記載してください。

# Details

事前学習モデルIssue: https://github.com/llm-jp/pretrain-tasks/issues/{id}

数パラグラフ以内で実験に関する詳細を説明してください。
関連するリンクがあれば適宜してください。

# Resources

* **計算機**
  * クラスタ: **FIXME** Sakura (Ishikari)
  * ノード種別: **FIXME** gpu-small (H100x8)
  * ノード台数: **FIXME** 1
* **コード**
  * リポジトリ: **FIXME** https://github.com/{org}/{repo}
  * コミット: **FIXME** xxxxxx
* **入力データ**:
  * 評価データ: **FIXME** llm-jp-eval-v1.3.1
* **出力データ**:
  * 保存先: `{cluster}:/data/llm-jp-eval/logs/{model_id}/iter_{iter:07d}`
* **W&B ログ**:
  * https://wandb.ai/{team}/{project} **FIXME**
* **開始日**: YYYY-MM-DD
* **終了予定日**: YYYY-MM-DD
