This respitory includes the baseline model for the 10707 course project.

Dataset: https://drive.google.com/file/d/0BzQ6rtO2VN95a0c3TlZCWkl3aU0/view
Paper citation: https://arxiv.org/abs/1704.04368
Code citation: https://github.com/abisee/pointer-generator
Framework: Tensorflow

Run: python run_summarization.py --mode=train --data_path=/path/to/chunked/train_* --vocab_path=/path/to/vocab --log_root=/path/to/a/log/directory --exp_name=myexperiment

Eval: python run_summarization.py --mode=eval --data_path=/path/to/chunked/val_* --vocab_path=/path/to/vocab --log_root=/path/to/a/log/directory --exp_name=myexperiment

Evaluate with ROUGE: decode.py uses package pyrouge to get ROUGE values.