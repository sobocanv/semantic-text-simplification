<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Semantic Text Simplification

Buliding AI course project.

## Summary

This project aims to simplify complex sentences into more readable versions without losing the core meaning. It uses AI techniques to assist with comprehension, making complex texts more accessible for students, non-native speakers, and others.

## Background

Understanding dense or complex language is a challenge for many, including students, non-native speakers, and individuals with cognitive difficulties. Manually simplifying text is time-consuming and requires very specific lingustic skills. This project aims to automate this process using AI, making all information more accessible.

## How is it used?

The tool can be used in educational settings, legal or medical contexts, or by anyone reading dense, technical materials. Users input a piece of text, and the model simplifies it while preserving its meaning. Ideally, this could be integrated into a web app, browser extension, or word processor plugin.

## Example of text simplification

### Example 1

original_text = "The committee's decision to postpone the meeting was predicated on the inclement weather forecast."
simplified_text = simplify_text(original_text)
print(simplified_text)

Desired output: "The committee decided to pospone the meeting, because of the forecast bad weather."

In this case, the tool:
* Removes the more formal phrase "was predicated on" and replaces it with "because of."
* Changes "inclement" to "bad," a simpler, more common word.

### Example 2

original_text = "The novel's protagonist exhibited an insatiable thirst for knowledge, which often led to self-destructive tendencies."
simplified_text = simplify_text(original_text)
print(simplified_text)

Desired output: "Simplified: The main character of the novel had a constant desire to learn, which sometimes made them harm themselves."

Here, the simplification includes:
* Changing "protagonist" to "main character."
* Swapping "insatiable thirst for knowledge" with "constant desire to learn."
* Simplifying "self-destructive tendencies" to "sometimes made them harm themselves."

## Data sources and AI methods

The project's success depends on high-quality datasets and robust AI models. Some key resources to be used:

### Data Sources:

* **Wikipedia Simple English Corpus**: This dataset contains sentences from Wikipedia articles in both their original and simplified forms. It is an excellent source for training models on text simplification.
* **Newsela Corpus**: Newsela is a platform providing news articles rewritten at different reading levels, making it a valuable resource for training simplification models, especially for educational purposes.
* **TURK Corpus**: A dataset specifically created for evaluating English sentence simplification tasks. It contains a set of complex sentences with multiple simplified versions, making it useful for fine-tuning models on semantic consistency.
* **WikiLarge**: A large-scale dataset derived from Wikipedia for text simplification tasks. It contains over 400,000 pairs of complex and simplified sentences.

### AI Methods:

* **Sequence-to-Sequence Models**: The core AI approach involves models like T5, BART, and BERT-based architectures. These models are pre-trained on vast corpora and fine-tuned to handle simplification by learning the mapping between complex and simplified sentence pairs.
* **Transformers**: Using models from Hugging Face’s Transformers library, like BART or T5, allows for applying pre-trained weights for tasks like summarization and fine-tuning them on simplification data.
* **Reinforcement Learning**: For evaluating the quality of simplified text, reward functions could be designed to encourage the model to preserve meaning while minimizing the complexity.

## Challenges

The project doesn't solve the issue of oversimplifying text or losing important context. It also may not handle highly technical or specialized language accurately. Ethical considerations include ensuring the simplified text does not lose essential nuances, especially in critical fields like law or medicine.

## What next?

The project could evolve by allowing users to customize the degree of simplification, expanding to multilingual support, or even incorporating real-time text simplification in browsers. Additional skills in user interface design and collaboration with linguists would help enhance the tool.

## Acknowledgments

The following resources served as inspiration for this project:

* **Wikipedia Simple English**: For providing access to paired complex and simplified sentences that serve as the backbone for the model's training data.
* **Hugging Face's Transformer Library**: For the ready-to-use transformer models, such as T5 and BART, that are fundamental to the architecture of this simplification task.
* **Newsela**: For the corpus of educational-level adjusted news articles that greatly enhance the capability to simplify text with different levels of readability.
* **Prior Work in Text Simplification**: Inspiration was drawn from research projects in text summarization and simplification, including work by Saggion et al. and Zhao et al., which emphasized the importance of balancing semantic preservation with linguistic accessibility.
