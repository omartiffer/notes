# Few-Shot Prompting

Few-shot prompts involve a few examples to improve the model's output quality. You're giving it more context and background for a specific task. This works when you want to achieve specific output that the model might not be able to produce based on its general training alone.

## Example

```
Classify the following data as people or company.

Data: ACME Co.
Category: company
Data: John Doe
Category: people
Data: Jane & John Doe
Category: people
Data: ABC LLC
Category: company

Data: Jane and John Doe
Category:
```
