# Kosha OpenAI Connector

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

To authenticate when provisioning the Kosha OpenAI connector, you need your OpenAI API key. 

## Kosha Connector Open Source Development

All connectors Kosha shares on the marketplace are open source. We believe in fostering collaboration and open development. Everyone is welcome to contribute their ideas, improvements, and feedback for any Kosha connector. We encourage community engagement and appreciate any contributions that align with our goals of an open and collaborative API management platform.

Refer to the contribution guidelines for details.


## Contributing

Pull requests and bug reports are welcome.

For larger changes, please create an issue in GitHub first to discuss your proposed changes and their possible implications.