---
dataset_info:
  features:
  - name: q_nl
    dtype: string
  - name: answer
    dtype: string
  - name: solution
    dtype: string
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
    num_bytes: 1610693
    num_examples: 886
  download_size: 524368
  dataset_size: 1610693
configs:
- config_name: default
  data_files:
  - split: test
    path: data/test-*
---
