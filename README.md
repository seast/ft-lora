# ft-lora
Some FT test code

## 070824
* Please update the News Classification code to torch version 2.1.0+cu122.
* Replace the usage of openlm-research/open_llama_3b_v2 with Qwen/Qwen2-0.5B.
* Evaluate the model's performance with Chinese news data. Even though we didn't train the model on Chinese data, it is capable of classifying Chinese texts.

## 070624
### News Classification
Fine-tuning LLMs for News Category Inspired by [Kshitiz Sahay's blog](https://medium.com/@kshitiz.sahay26/fine-tuning-llama-2-for-news-category-prediction-a-step-by-step-comprehensive-guide-to-fine-tuning-48c06dee28a9)

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
