# Evaluating and Selecting Sources

When you are doing an extensive literature search and using the different techniques suggested, chances are that you will end up with a large list of sources to go through. You will have to decide which ones you will select to study in more detail.

::::{grid}
:gutter: 1

:::{grid-item-card} Standard Practice <br>
[Title-Abstract Reading](#recap-standard-practice-title-abstract-reading)<br>
Quickly scan if an article is relevant for your research by looking at its title and abstract
:::

::::

::::{grid}
:gutter: 2

:::{grid-item-card} AI Assist 1<br>
[Sorting Results of Initial Search](#ai-assist-1-sorting-results-of-initial-search)<br>
Use general tools to sort the order of your results before you go through the titles and abstracts
:::

:::{grid-item-card} AI Assist 2<br>
[Dynamically Sort Results while Selecting](#ai-assist-2-dynamically-sort-results-while-selecting)<br>
Train an AI-model to dynamically change the order of your results as you select based on titles and abstracts
:::

::::

## Recap Standard Practice: Title-Abstract Reading

A common way to select academic literature is by doing title-abstract reading. Watch this video to learn more about the practice. This strategy works well because you can quickly scan whether an article is relevant for your research.

<iframe width="560" height="315" src="https://collegerama.tudelft.nl/Mediasite/Play/ed24f15b2a8d4f43bbe62a4573f341531d" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><br>
"Selecting Resources" by TU Delft Library Education Support is licensed CC-BY

## AI Assist 1: Sorting Results of Initial Search

AI can help by sorting the order of papers to go through, based on relevancy ranking of the found papers. You can do this by uploading an RIS or csv-overview of your sources into a general model, asking it to sort it in the order most relevant to your research question. You will then get an ordered list with articles most related to your research question so it might be easier to go through the list and make the selection process easier. 

When using sources from multiple databases, it can be helpful to use a reference manager to generate a list of all sources in one single file.

```{admonition} Example Prompt
:class: dropdown note

I am a [x year] student in [study]. I am writing a literature review on [topic] with the following research question: [research question]. Attached is a file with all the sources that I found. Read the attached file, then make an organised list in their order of relevance to this question. Finally, make a table of this list including the name, authors, relevancy score and url leading directly to the location of the article.<br>
[attach a list from reference manager or specific database into tool]

```

```{admonition} Guided Activity: Use General Tools to Sort Your Initial Results for Screening
:class: dropdown tip

**Suggested Tools**: Copilot, Claude, Gemini, ChatGPT

**Step 1: Ask General AI Tool to Sort Your Results**
Use the following example prompt in a general AI chatbot and to sort your articles before starting selection:

Example Prompt:

_I am a [x year] student in [study]. I am writing a literature review on [topic] with the following research question: [research question]. Attached is a file with all the sources that I found. Read the attached file, then make an organised list in their order of relevance to this question. Finally, make a table of this list including the name, authors, relevancy score and url leading directly to the location of the article.<br>
[attach a list from reference manager or specific database into tool]_

**Step 2: Reflect on the Output**
1. Did the AI’s ranking of articles match your own idea of which items were the most relevant to your research question? 
2. Were there any highly relevant articles that were ranked lower than you expected?
```

## AI Assist 2: Dynamically Sort Results while Selecting

There are AI-tools that actively learn what articles are relevant to your research based on your own choices during the review process. This can be especially helpful if you are working with a large amount of sources, both in a literature review and in a systematic literature review. 

Watch an explainer of one of the most commonly used tools for this process, ASreview, to learn more about how this process works:

<iframe width="560" height="315" src="https://www.youtube.com/embed/k-a2SCq-LtA?si=2FUXki8CjHgeiC6k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><br>
"ASReview LAB explained" by ASReview TV is licensed CC-BY

```{admonition} Guided Activity: Try out ASReview
:class: dropdown tip

Install and try out ASReview: 
Installation of ASReview requires some basic Python knowledge. You can find more information on how to install ASreview and what files you can upload in the <a href="https://asreview.readthedocs.io/en/stable/lab/index.html" target="_blank">ASReview Lab Guide</a>

```

## Summary and Prompts

| Task | Standard Practice | AI Assist | Tools | Example Prompts |
|-|-|-|-|-|
| Sort results from an initial search | Organise based on relevance score database | Make an initial relevance ranking of found papers to improve selection | General tools, e.g. Copilot, Claude, Gemini | I am a [x year] student in [study]. I am writing a literature review on [topic] with the following research question: [research question]. Attached is a file with all the sources that I found. Read the attached file, then make an organised list in their order of relevance to this question. Finally, make a table of this list including the name, authors, relevancy score and url leading directly to the location of the article. [attach a list from reference manager or specific database into tool] |
| Select articles to study | Title-abstract reading | Train AI to dynamically aid the review process | ASReview, Covidence | n/a |

## References

- ASReview LAB developers. (n.d.). _ASReview LAB guide_. Retrieved August 29, 2025, from <a href="https://asreview.readthedocs.io/en/stable/lab/index.html" target="_blank">https://asreview.readthedocs.io/en/stable/lab/index.html</a>
- ASReview TV. (2022, June 3). _ASReview LAB explained_ [Video]. <a href="https://www.youtube.com/watch?v=k-a2SCq-LtA" target="_blank">https://www.youtube.com/watch?v=k-a2SCq-LtA</a>