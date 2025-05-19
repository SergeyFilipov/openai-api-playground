# 🚀 OpenAI API Playground

A hands-on collection of Jupyter notebooks exploring key features of the OpenAI API.  
This repository covers practical examples across natural language processing, image generation/editing, audio transcription, and vector embeddings.

Whether you're experimenting with GPT prompts, generating images with DALL·E, or transcribing audio with Whisper — this is your starting point for building AI-powered apps.

📦 Tech stack: Python · OpenAI API · Jupyter

📌 Prerequisites: OpenAI API key + pip install of basic libraries


🔧 Block 1: using_openai_api.ipynb
🔧 Basic usage of the OpenAI Chat API.
This notebook demonstrates how to send prompts to the gpt-3.5-turbo model and receive responses using the openai.ChatCompletion.create() method. It shows the structure of the messages parameter and how to format system, user, and assistant roles.

📁 Contents:

Setting your API key (openai.api_key)

Sending a simple prompt to GPT

Structuring messages as a list of roles

Interpreting and printing the response

💡 Use case: Minimal working example to understand the core mechanics of interacting with the Chat API using Python.


🎙️ Block 2: transcription_api.ipynb
🎙️ Audio-to-text with Whisper API
This notebook demonstrates how to transcribe audio files (e.g., .mp3, .wav) into text using OpenAI's Whisper API. It includes both a code example and basic output parsing.

📁 Contents:

Uploading and reading an audio file

Sending it to openai.Audio.transcribe()

Getting the full transcript

Saving or printing the result

💡 Use case: Ideal for converting interviews, recordings, or voice notes into usable text via Python.


🌐 Block 3: translation_api.ipynb
🌐 Language translation using GPT
This notebook demonstrates how to perform text translation between different languages using the Chat API. It uses prompt-based translation with role-based messages and shows examples for English, French, Spanish, and more.

📁 Contents:

Prompting GPT to act as a translator

Examples with multiple language pairs

Customizing system instructions

Handling multi-line input

💡 Use case: Translate user input, articles, or interface text dynamically without relying on traditional translation APIs.


🎨 Block 4: create_image_api.ipynb
🎨 Text-to-image generation with DALL·E
This notebook shows how to generate unique images from text prompts using the OpenAI Image API. It demonstrates basic usage of openai.Image.create() and how to view and save generated images.

📁 Contents:

Sending a prompt to openai.Image.create()

Choosing image size (e.g., 256x256, 512x512)

Viewing image URLs

Downloading and saving images locally

💡 Use case: Create AI-generated visuals from textual ideas – useful for prototyping, concept art, or creative experiments.


🗂️ Block 5: text-classification-nlp-tasks.ipynb
🗂️ Prompt-based text classification
This notebook demonstrates how to classify text into predefined categories using GPT. It covers few-shot prompting, multi-class logic, and structured output parsing with Python.

📁 Contents:

Prompt engineering for classification

Category assignment using GPT

Examples with user reviews and custom labels

Optional post-processing with JSON parsing

💡 Use case: Automatically tag or label incoming text (emails, reviews, messages) with categories, sentiments, or intent — without training a model.


✂️ Block 6: text-summarization.ipynb
✂️ Summarize long text using GPT prompts
This notebook shows how to use GPT models to generate summaries of long input texts. It includes zero-shot and few-shot prompting, and lets you adjust the length and style of summaries.

📁 Contents:

Defining summary prompts (e.g., "Summarize the following…")

Examples with articles, reviews, and raw text

Parameters for controlling length and tone

Summary quality evaluation tips

💡 Use case: Automatically condense articles, emails, transcripts, or user input into short summaries for dashboards, previews, or quick reading.


🧭 Block 7: vector_embeddings.ipynb
🧭 Generate text embeddings for semantic tasks
This notebook demonstrates how to use OpenAI's text-embedding-ada-002 model to convert text into high-dimensional vectors. These embeddings can then be used for similarity search, clustering, or recommendation.

📁 Contents:

Using openai.Embedding.create()

Embedding multiple inputs (sentences, paragraphs)

Visualizing similarity via cosine distance

Saving and reusing embeddings

💡 Use case: Build search engines, group similar content, or power AI recommendations using semantic vector representations of text.


🖌️ Block 8: image_edit_api.ipynb
🖌️ Edit images with natural language prompts
This notebook demonstrates how to edit existing images using the OpenAI Image API. It supports modifications like object removal, replacement, or style change via simple text instructions.

📁 Contents:

Uploading and masking an image

Sending editing instructions to openai.Image.create_edit()

Receiving and displaying the edited image

Saving the result locally

💡 Use case: Modify visual assets directly from text descriptions — ideal for creative workflows, rapid iteration, or UI prototyping.

