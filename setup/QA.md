# QA

## 基础问题

### 为什么 我的 notebook 报告依赖包找不到?

动手一个安装一下, 挑战一下自己.

### 为什么 我的 huggingface_hub 报错?

参考我本地的 python 包版本

```shell
python --version
Python 3.10.9

pip show langchain
Name: langchain
Version: 0.0.348
Summary: Building applications with LLMs through composability
Home-page: https://github.com/langchain-ai/langchain
Author:
Author-email:
License: MIT
Location: /Users/fancn/anaconda3/lib/python3.10/site-packages
Editable project location: /Users/fancn/2023/2023-ai/source-code-projects/langchain/libs/langchain
Requires: aiohttp, async-timeout, dataclasses-json, jsonpatch, langchain-core, langsmith, numpy, pydantic, PyYAML, requests, SQLAlchemy, tenacity
Required-by: langchain-experimental

pip show huggingface_hub
Name: huggingface-hub
Version: 0.19.4
Summary: Client library to download and publish models, datasets and other repos on the huggingface.co hub
Home-page: https://github.com/huggingface/huggingface_hub
Author: Hugging Face, Inc.
Author-email: julien@huggingface.co
License: Apache
Location: /Users/fancn/anaconda3/lib/python3.10/site-packages
Editable project location: /Users/fancn/2023/2023-ai/source-code-projects/huggingface_hub
Requires: filelock, fsspec, packaging, pyyaml, requests, tqdm, typing-extensions
Required-by: sentence-transformers, transformers
```
