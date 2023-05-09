# Kosha OpenAI Connector

![OpenAI][images/openai-logo.png](https://raw.githubusercontent.com/Cisco-Kosha/openai-api-spec/main/images/openai-logo.png")

OpenAI allows you to work with various artificial intelligence models for a variety of tasks, including—but not limited to—content generation,semantic search and classification, translation, and data extraction.

The Kosha OpenAI connector enables you to perform REST API operations from the OpenAI API in your Kosha workflow or custom application. Using the Kosha OpenAI connector, you can directly access the OpenAI platform to:

* Create completions for provided prompts
* Transcribe audio into a the input language or translate audio into English
* Generate new images from prompts and inputs 

## Useful Actions

You can use the Kosha OpenAI connector to perform key actions from the OpenAI API.

Refer to the Kosha OpenAI connector [API specification](openapi.json) for details.

### Completions

Create completions from provided prompts and parameters

### Images

* Generate images
* Generate a variation of a given image
* Generate an edited or extended image given an original input and prompt

### Fine tunes

* Create a job that fine tunes a specified model from a given dataset
* List your org's fine-tuning jobs
* Get fine-grained status for a fine-tuning job

### Models

* List available models and provide basic information about each
* Retrive a model instance

### Moderation

Classify text that violates OpenAI's content policy

## Authentication

To authenticate when provisioning the Kosha OpenAI connector, you need your OpenAI API key. You can [retrieve your API key](https://platform.openai.com/account/api-keys) from the OpenAPI platform. 
