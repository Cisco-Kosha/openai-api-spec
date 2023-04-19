# Kosha OpenAI Connector

![OpenAI](images/openai-logo.png)

OpenAI allows you to work with various artificial intelligence models for a variety of tasks, including—but not limited to—content generation,semantic search and classification, translation, and data extraction.

## Useful Actions

Using the Kosha OpenAI connector, you perform REST API operations such as create completions, create images, and convert audio into text. 

Refer to the Kosha OpenAI connector [API specification](openapi.json) for details.

* Chat: Given a list of messages describing a conversation, the model will return a response.
* Completions: Given a prompt, the model will return one or more predicted completions, and can also return the probabilities of alternative tokens at each position.
* Audio: Transcribe audio into a the input language or translate audio into English.
* Images: Given a prompt and/or an input image, the model will generate a new image.

## Example Usage

The following request creates a completion for the provided prompt:

```
curl https://api.openai.com/v1/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer $OPENAI_API_KEY" \
  -d '{
    "model": "text-davinci-003",
    "prompt": "Say this is a test",
    "max_tokens": 7,
    "temperature": 0
  }'
```
## Authentication

The OpenAI API uses API keys for authentication. You can [retrieve your API key](https://platform.openai.com/account/api-keys) from the OpenAPI platform. 

Include your API key in all requests in an Authorization HTTP header: `Authorization: Bearer OPENAI_API_KEY`.

