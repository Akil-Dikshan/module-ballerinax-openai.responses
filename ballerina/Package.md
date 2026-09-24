## Overview

[OpenAI](https://openai.com/), an AI research organization focused on creating friendly AI for humanity, offers the [OpenAI API](https://platform.openai.com/docs/api-reference/introduction) to access its powerful AI models for tasks like natural language processing and image generation. The `ballerinax/openai.responses` package offers functionality to connect and interact with the [Responses API of the OpenAI REST API](https://platform.openai.com/docs/api-reference/responses), OpenAI's most advanced interface for generating model responses with agentic primitives such as built-in web search and file search tools. The package currently exposes the [create model response](https://platform.openai.com/docs/api-reference/responses/create) operation (`POST /responses`), covering text and image inputs, text and JSON outputs, function calling, and the built-in tools.

## Key Features

- Text and image inputs with text and JSON structured outputs
- Function calling to extend model capabilities with custom functions
- Built-in agentic tools including web search and file search
- Simple, single-operation interface for creating model responses
