# LLM-Zoo

# Backbones

| Model        | Version                        | Open-source | Size           | Backbone    | Languages | Domain  | Training Data                                                                                                                                                                                                                                                                     | GitHub                                              | Huggingface                                                       | Paper                                      | Demo                                | Official Blog                                                                                          | Release Time |
| :---: | :---: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| MOSS         | moss-moon-003-base             | ✅           | 16B            | CodeGen     | zh, en    | General | <details><summary><b>detail</b></summary>100B Chinese tokens and 20B English tokens </details>                                                                                                                                                                                                                                       | [[link](https://github.com/OpenLMLab/MOSS)]         | [[link](https://huggingface.co/fnlp/moss-moon-003-base)]          | \-                                         | [[link](https://moss.fastnlp.top/)] | [[link](https://txsun1997.github.io/blogs/moss.html)]                                                  | 2023.04.21   |
| LLaMA        | llama-7b/13b/33b/65b           | ✅           | 7B/13B/33B/65B | \-          | en        | General | <details><summary><b>detail</b></summary>1T tokens (English CommonCrawl, C4, Github, Wikipedia, Gutenberg and Books3, ArXiv, Stack Exchange) </details>                                                                                                                                                                              | [[link](https://github.com/facebookresearch/llama)] | [[link](https://huggingface.co/decapoda-research/llama-7b-hf)]    | [[link](https://arxiv.org/abs/2302.13971)] | \-                                  | [[link](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)]                             | 2023.02.27   |
| BloombergGPT | \-                             | ❌           | 50B            | BLOOM-style | en        | Finance | <details><summary><b>detail</b></summary>363B financial datasets (web, news, filings, press, bloomberg) and 345B public datasets (PILE, C4, wikipedia) </details>                                                                                                                                                                    | \-                                                  | \-                                                                | [[link](https://arxiv.org/abs/2303.17564)] | \-                                  | [[link](https://www.bloomberg.com/company/press/bloomberggpt-50-billion-parameter-llm-tuned-finance/)] | 2023.03.30   |
| Linly (伶荔)   | Linly-Chinese-LLaMA 7b/13b/33b | ✅           | 7B/13B/33B     | LLaMA       | zh        | General | <details><summary><b>detail</b></summary>Chinese-English parallel corpora [[link](https://statmt.org/wmt18/translation-task.html#download)], Chinese Wikipedia, community interaction, news data [[link](https://github.com/CLUEbenchmark/CLUECorpus2020)], scientific literature [[link](https://github.com/ydli-ai/CSL)] </details>| [[link](https://github.com/CVI-SZU/Linly)]          | [[link](https://huggingface.co/P01son/Linly-Chinese-LLaMA-7b-hf)] | \-                                         | \-                                  | \-                                                                                                     | 2023.03.28   |
