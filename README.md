# FGVIrony

## Abstract

Verbal irony, identified as an incongruity between a speaker's intended meaning and their explicit linguistic expression, often manifests in nuanced forms such as irony, sarcasm, and satire. Current research often fails to differentiate among these fine-grained categories of verbal irony, primarily focusing on generic detection in texts.
Therefore, in this work, we introduce a new task for fine-grained verbal irony recognition, which aims not only to identify the presence of verbal irony but also to distinguish among its various types. Besides, a notable gap in existing research is the lack of datasets tailored to fine-grained verbal irony, particularly in the context of the Chinese language. To tackle this issue, we have developed the FGVIrony dataset. On the FGVIrony dataset, we explore the challenges of accurately identifying fine-grained verbal irony. Additionally, to investigate the limitations inherent in current methodologies, we propose a cascaded multi-prompt learning approach, CMP, designed to enhance recognition accuracy. 

## Dataset Description

Each entry in the dataset contains the following fields:
- `title`: The news title
- `comment`: The user comment
- `context`: The news content providing context
- `tag`: Additional tags (if any)
- `parent`: Parent comments information, including:
  - `content`: Content of the parent comment
  - `id`: Unique identifier of the comment
  - `parent_id`: ID of the parent comment
  - `reply_count`: Number of replies
  - `recommend_num`: Number of recommendations
  - `tread_num`: Number of negative reactions
- `category`: The irony category label

## Statistics

| Category | Train Comments | Train Titles | Test Comments | Test Titles |
|----------|---------------|--------------|---------------|-------------|
| **Total** | 8,279 | 577 | 1,973 | 143 |
| **Verbal Irony** | 2,851 | 577 | 611 | 143 |
| **Non-Irony** | 5,428 | 577 | 1,362 | 143 |
| **Irony** | 1,461 | 398 | 335 | 110 |
| **Sarcasm** | 327 | 199 | 35 | 29 |
| **Satire** | 483 | 275 | 94 | 58 |
| **Overstatement** | 150 | 95 | 42 | 24 |
| **Understatement** | 57 | 38 | 22 | 15 |
| **Rhetorical Question** | 373 | 118 | 83 | 29 |



## Citation

If you find this work useful, welcome to cite us.
```bib

```
