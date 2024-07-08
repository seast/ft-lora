# ft-lora
Some FT test code

## News Classification
Fine-tuning Llama 2 for News Category Inspired by [Kshitiz Sahay's blog](https://medium.com/@kshitiz.sahay26/fine-tuning-llama-2-for-news-category-prediction-a-step-by-step-comprehensive-guide-to-fine-tuning-48c06dee28a9)

* New Training Data with 2k records in 5 categories.
```
Below is an instruction that describes a task. Write a response that appropriately completes the request.

### Instruction:
Categorize the news article into one of the 5 categories:

tech
business
sport
entertainment
politics

Input:
{NEWS_TEXT}

### Response:
politics

### End
```
