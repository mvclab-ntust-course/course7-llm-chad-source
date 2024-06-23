## hw7_1
#### 設定 LoRA 參數：
#### r=8
#### lora_alpha=16
#### lora_dropout=0.05
#### task_type="SEQ_CLS"
#### 指定 LoRA 作用層：
#### target_modules=["q_lin", "k_lin","v_lin"]
![](img/7-1.png)
## hw7_2
#### 設定 LoRA 參數：
#### r=8
#### lora_alpha=16
#### lora_dropout=0.05
#### task_type="SEQ_CLS"
#### 指定 LoRA 作用層：
#### target_modules=["lin1", "lin2"]
![](img/7-2.png)
## hw7_3
#### 用 IA3 進行 finetuning，參數：
#### task_type=TaskType.SEQ_CLS,
#### target_modules=["q_lin", "k_lin", "v_lin", "out_lin", "lin1", "lin2"],
#### feedforward_modules=["lin1", "lin2"]
#### optimizer：adamw_hf
![](img/7-3.png)
