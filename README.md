<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Semantic Text Simplification

Buliding AI course project.

## Summary

This project aims to simplify complex sentences into more readable versions without losing the core meaning. It uses AI techniques to assist with comprehension, making complex texts more accessible for students, non-native speakers, and others.

## Background

Understanding dense or complex language is a challenge for many, including students, non-native speakers, and individuals with cognitive difficulties. Manually simplifying text is time-consuming and requires specific skills. This project automates the process using AI, making information more accessible.

This is how you make a list, if you need one:
* Problem: Complex sentences can be hard to understand
* Problem: Manual simplification is time-consuming
* Problem: Not everyone has the skills to simplify texts correctly

## How is it used?

The tool can be used in educational settings, legal or medical contexts, or by anyone reading dense, technical materials. Users input a piece of text, and the model simplifies it while preserving its meaning. This could be integrated into a web app, browser extension, or word processor plugin.

## Example of text simplification
original_text = "The committee's decision to postpone the meeting was predicated on the inclement weather forecast."
simplified_text = simplify_text(original_text) print(simplified_text)

## Data sources and AI methods

Data sources include parallel corpora like the Wikipedia Simple English dataset, which contains paired complex and simplified sentences. The project uses AI techniques such as sequence-to-sequence models (e.g., T5, BART) that are trained to map complex text to simplified counterparts.

[Wikipedia Simple English](https://simple.wikipedia.org/wiki/Main_Page)  
[Hugging Face Transformers](https://huggingface.co/transformers/)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

The project doesn't solve the issue of oversimplifying text or losing important context. It also may not handle highly technical or specialized language accurately. Ethical considerations include ensuring the simplified text doesn't lose essential nuances, especially in critical fields like law or medicine.

## What next?

The project could evolve by allowing users to customize the degree of simplification, expanding to multilingual support, or even incorporating real-time text simplification in browsers. Additional skills in user interface design and collaboration with linguists would help enhance the tool.

## Acknowledgments

* Inspiration from existing text summarization and simplification projects
* Data from the Wikipedia Simple English corpus
* Models built using Hugging Face's Transformer library
  <br>For example: [Wikipedia Simple English](https://simple.wikipedia.org/wiki/Main_Page) / [Hugging Face Transformers](https://huggingface.co/transformers)
