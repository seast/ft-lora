# ft-lora
Some FT test code

## 070824
* Update the News Classification code to torch version 2.1.0+cu122.
* Replace the usage of openlm-research/open_llama_3b_v2 with Qwen/Qwen2-0.5B.
* Evaluate the model's performance with Chinese news data. Even though we didn't train the model on Chinese data, it is capable of classifying Chinese texts.

New texts
```
On the first day of production on the New Zealand location of “Avatar: The Way of Water...
```
> ouput -> ***entertainment***


```
Xbox、ABathing Ape 將推聯乘產品？大家沒有看錯啊！早前美國 A Bathing Ape IG 已經 post 了 Xbox 與 A Bathing Ape 推出聯乘產品的預告短片，從中更可見當中有何產品推出的。.
```
> output -> ***tech***



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
