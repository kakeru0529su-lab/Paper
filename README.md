# Paper

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

### PESO
・ 単一LoRAで過去嗜好の保持と新嗜好への適応を両立する手法。
・ 新しい嗜好に適応すると，過去の有用な嗜好を忘れやすい。 
・ Proximal regularizationにより，過去知識から離れすぎないように更新する。 
