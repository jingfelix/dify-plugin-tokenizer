## dify-plugin-tokenize

**Author:** jingfelix

**Version:** 0.0.1

**Type:** tool

### Description

Tokenizing text using various tokenizers from transformers.AutoTokenizer. Returns the token count.

### Usage

You can choose the tokenizer by specifying the `tokenizer` parameter. The default is `gpt2`. This plugin utilizes the `transformers` library to tokenize text. So please check https://huggingface.co/docs/transformers/v4.52.3/en/model_doc/auto#transformers.AutoTokenizer if the tokenizer you want to use is supported.

<img src="_assets/setup.png" alt="Screenshot" width="400">
