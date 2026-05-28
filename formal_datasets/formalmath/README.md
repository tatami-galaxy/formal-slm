---
dataset_info:
  features:
  - name: q_nl
    dtype: string
  - name: answer
    dtype: string
  - name: solution
    dtype: string
  - name: subject
    dtype: string
  - name: level
    dtype: int64
  - name: q_fl
    dtype: string
  - name: header
    dtype: string
  - name: judge_faithfulness
    dtype: string
  - name: judge_answer_matches
    dtype: bool
  - name: judge_reasoning
    dtype: string
  - name: judge_major_issues
    list: 'null'
  splits:
  - name: test
    num_bytes: 316042
    num_examples: 195
  download_size: 114603
  dataset_size: 316042
configs:
- config_name: default
  data_files:
  - split: test
    path: data/test-*
---
