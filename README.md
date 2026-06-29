## Prompt Tuning CLIP for Fine-Grained Aircraft Classification

This project explores parameter-efficient prompt tuning techniques to improve the downstream performance of the CLIP vision-language model on the FGVC Aircraft dataset. The work compares zero-shot CLIP with handcrafted prompts, LLM-generated prompts (CuPL), learnable prompts (CoOp), conditional prompts (CoCoOp), and LoRA fine-tuning.

The repository includes data preprocessing, model training, hyperparameter tuning, and evaluation pipelines. Performance is measured using classification accuracy, with visual comparisons across prompting methods to analyse their effectiveness for fine-grained aircraft recognition.
