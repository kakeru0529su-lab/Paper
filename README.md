# Paper

> **運用方針**：週報や研究のために実際に読み、内容を確認した論文を記録する。新着論文の紹介・候補に挙がっただけの論文は追加しない。今後の追加分は、論文名・URL、研究課題、手法・新規性、確認した実験結果・限界、SCRec研究との関連性を可能な範囲で簡潔にまとめる。未確認事項は推測で補わない。

### TALLRec: Tuning LLMs for Recommendation
・ LLMを推薦タスク向けにInstruction Tuningする手法。

・ 通常のLLMは推薦特有のユーザ嗜好を十分に学習していない。

・ 推薦データをYes/No形式に変換し，LLMを嗜好予測に適応させる。

### LoRA: Low-Rank Adaptation of Large Language Models
・ LLMを少ない追加パラメータで効率的にFine-tuningする手法。

・ LLM全体を更新すると計算コストとメモリ消費が大きい。

・ 低ランク行列のみを学習し，軽量にタスク適応を行う。

### MeTA-LoRA: Data-Efficient Multi-Task Fine-Tuning for LLMs
・ LoRAとメタ学習を組み合わせた少量データ適応手法。

・ 通常のLoRAでは複数タスク間の共通知識を活かしにくい。

・ メタ学習により，少数データで適応しやすいLoRAを学習する。

### ThinkRec
・ LLMに推論過程を持たせて推薦する手法。

・ 表面的な履歴だけではユーザ嗜好の理由を捉えにくい。

・ LLMに嗜好理由を考えさせ，より深い推薦判断を行う。

