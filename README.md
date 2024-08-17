# Multilingual-Text-Chatbot

Summary of Fine-Tuning Llama 2
QLoRA Parameters:

LoRA attention dimension: 64

Alpha: 16

Dropout: 0.1

Training Setup:

Use Google Colab with limited resources.

Implement parameter-efficient fine-tuning (PEFT) techniques like LoRA or QLoRA.

Fine-tune in 4-bit precision to reduce VRAM usage.

Process Steps:

Load preprocessed dataset.

Configure bitsandbytes for quantization.

Load Llama 2 model and tokenizer.

Set training parameters and start training.
