# ShodhAI Workflow Reviewer
Running the accompanying Colab notebook top-to-bottom. CPU-only; core uses Python standard library.
Supported fields: category, urgent, waiting_minutes, vip, channel.
Supported conditions: nested AND/OR/NOT, missing, present, eq, neq, gt, gte, lt, lte, in.
Rules using ascending order; first match wins. Python is inspected with AST and never executed.
Limitations: bounded JSON language, restricted Python subset, finite ticket grid; not arbitrary prose/code verification.
The fake model is reproducibility scaffolding, not live-model performance evidence.

Colab Notebook Link - https://colab.research.google.com/drive/1vzMX0iZfusy9VKMT1XEkjHHebHNm0RCP?usp=sharing
