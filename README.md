# prompt-engineering
ChatGPT Prompt Engineering for Developers - OpenAI, DeepLearning.AI

## Using OpenAI API
Install the OpenAI Python library:

```
    $pip install openai
```

Configure the library with your secret API key obtained from your OpenAI [account](https://platform.openai.com/account/api-keys).

Set the API key as an environment variable:

```
    $export OPEN_API_KEY='sk-...'
```

Or set `openai.api_key` directly:

```
    import openai
    openai.api_key = "sk-..."
```
