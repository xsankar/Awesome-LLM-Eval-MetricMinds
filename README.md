### Awesome-LLM-Eval-MetricMinds : All things for LLM Evaluation
#### _[Back to TOC](https://github.com/xsankar/Awesome-Awesome-LLM)_
> [About Me](https://www.linkedin.com/in/ksankar) [Blog](https://ksankar.medium.com)
***
| [Survey Paper Collection](#survey-papers) | [General Theory](#general-theory) | [Evaluation Experiments](#evaluation-experiments) | [Multi Benchmark Frameworks](#multi-benchmark-frameworks) |[Frameworks & Benchmarks by topic](#frameworks--benchmarks-by-topic) | [Datasets](#datasets) | [Other Repos](#other-repos) |
| :-: | :-: | :-: | :-: |:-: |:-: |:-: |
***
### Some Concepts
![OpenAI](./images/NPS-v07-p26.png)
***
![OpenAI](./images/NPS-v07-p27.png)
***
![OpenAI](./images/NPS-v07-p29.png)
***
![OpenAI](./images/NPS-v07-p30.png)
***
![OpenAI](./images/NPS-v07-p31.png)
***
| [Survey Paper Collection](#survey-papers) | [General Theory](#general-theory) | [Evaluation Experiments](#evaluation-experiments) | [Multi Benchmark Frameworks](#multi-benchmark-frameworks) |[Frameworks & Benchmarks by topic](#frameworks--benchmarks-by-topic) | [Datasets](#datasets) | [Other Repos](#other-repos) |
| :-: | :-: | :-: | :-: |:-: |:-: |:-: |
***
## Survey Papers 
[<img src="images/back_button_2.png" width="25" height="25">](#some-concepts)
| Year | Title | Notes | 
| -: | :- | :- |
| 10.2023 | [Cataloguing LLM Evaluations](https://aiverifyfoundation.sg/downloads/Cataloguing_LLM_Evaluations.pdf) | from [AI verify Foundation SIngapore](https://aiverifyfoundation.sg/) |
| 10.2023 | [Evaluating Large Language Models: A Comprehensive Survey](https://arxiv.org/abs/2310.19736) | |
| 7.2023 | [A Survey on Evaluation of Large Language Models](https://arxiv.org/abs/2307.03109) | |
| 11.2022 | [Holistic Evaluation of Language Models](https://arxiv.org/abs/2211.09110) |  |
***
## General Theory 
[<img src="images/back_button_2.png" width="25" height="25">](#some-concepts)
| Year | Title | Notes | 
| :-: | :-: | :-: |
|  |  | 
***
## Evaluation Experiments 
[<img src="images/back_button_2.png" width="25" height="25">](#some-concepts)
| Year | Title | Notes | 
| -: | :- | :- |
| 11.2021 | [A Systematic Investigation of Commonsense Knowledge in Large Language Models](https://arxiv.org/abs/2111.00607) | EMNLP/Dubai 2022 | 
***
## Multi Benchmark Frameworks 
[<img src="images/back_button_2.png" width="25" height="25">](#some-concepts)
| Year | Title | Notes | 
| :- | :- | :- |
| 2023 | [MosaicML Eval Gauntlet](https://www.mosaicml.com/llm-evaluation) | Good eval framework. Encompasses 34 different benchmarks, organized into 6 broad categories of competency that we expect good foundation models to have. Their categorization is very useful - I am borrowing some of their ideas !|
| 2023 | [OpenCompass](https://github.com/open-compass/opencompass) | Extensive dataset support, good dataset list |
| | [Language Model Evaluation Harness - EleutherAI](https://github.com/EleutherAI/lm-evaluation-harnes) | 200+ subtasks / evaluation settings implemented |
| | [Alpaca Eval](https://github.com/tatsu-lab/alpaca_eval) | An Automatic Evaluator for Instruction-following Language Models |
| 11.2023| [IFEval](https://arxiv.org/abs/2311.07911) | 25 types of verifiable instructions and constructed around 500 prompts |
***
## Frameworks & Benchmarks by topic 
[<img src="images/back_button_2.png" width="25" height="25">](#some-concepts)
---
| [Dialogue Kinetics](#dialogue-kinetics) | [Bias](#bias) | [Toxicity](#toxicity) | [Robustness](#robustness) | [Factuality](#factuality) | [Hallucination](#hallucination) | [Accuracy](#accuracy) |
| :- | :- | :- | :- |:- |:- |:- |
---
| [World Knowledge](#world-knowledge) | [Commonsense Reasoning](#commonsense-reasoning) | [Language Understanding](#language-understanding) | [Symbolic Problem Solving](#symbolic-problem-solving) | [Reading Comprehension](#reading-comprehension) | [Programming](programming) |
| :- | :- | :- | :- |:- |:- |
***
## Dialogue Kinetics
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> Manner in which an LLM is interacting with the users
> > a.k.a. _Interactional Dynamics_ - This term encompasses the various elements and factors that come into play during a conversation, including communication styles, tonality, responsiveness, and other aspects that contribute to the overall dynamics of the interaction.
> > Movement, energy, and interactive nature of communication within a conversation.
> 
> Problematic language generation (toxicity below), Bias (below)
> 
> Tonality, Fluency, Language Mismatch, Verbosity, Egregious Conversation Detector
> 
| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  |  |  |
---
## Bias
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> TBD

| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  |  |  |
---
## Toxicity
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> HAP (Hate,Abuse,Profanity)

| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  |  |  |
---
## Robustness
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> Emergent Behavior, Robustness
> 
| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  | DecodingTrust (Metrics : Adversarial Accuracy, Distributional Shift) |  |
---
## Factuality
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> Factuality, Relevance (Context/Question), Coherence, Groundedness, Comprehensiveness
> Dark Patterns _e.g., CFPB “Luring Test” a.k.a. Dark Patterns : design strategies used to trick consumers during their purchasing experience and guide them to decisions they would not make otherwise - ranging from manipulation to deception_
> 
| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  | HELM |  |
|  | BigBench |  |
|  | Eleuther Evaluation Harness |  |
|  | Factool |  |
|  |  | TruthfulQA |
---
## Hallucination
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> TBD
> 
| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  | Hallucination Evaluation Model | Vectara [Hugginface](https://huggingface.co/vectara/hallucination_evaluation_model), [Leaderboard](https://github.com/vectara/hallucination-leaderboard) | |
| | Generative Assessment Project | [Project Site - Arthur.ai](https://www.arthur.ai/gap) | [Interesting dataset - Databricks Dolly 15K](https://huggingface.co/datasets/databricks/databricks-dolly-15k)|
---
## Accuracy
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> TBD

| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  |  |  | Metrics : Perplexity, Entropy, BPC |

---
## World Knowledge 
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
| 2022 | Jeopardy | [Jeopardy Data at Higginface](https://huggingface.co/datasets/jeopardy) | Jeopardy consists of 2,117 Jeopardy questions separated into 5 categories: Literature, American History, World History, Word Origins, and Science. The model is expected to give the exact correct response to the question. (MosaicML has custom curated the larger Jeopardy set available on Huggingface for their evaluation framework)|
| 2022 | BIG-bench: wikidata | [Github Link](https://github.com/google/BIG-bench/tree/main/bigbench/benchmark_tasks/qa_wikidata) | BIG-bench wikidata consists of 20,321 questions regarding factual information pulled from wikipedia. Questions range from the native language of celebrities to the country that different regions belong to. Models are given a sentence such as “The country of citizenship of Barack Obama is” and are expected to complete the sentence with e.g. “the United States.” |
| 2022 | BIG-bench misconceptions | [Github Link](https://github.com/google/BIG-bench/tree/main/bigbench/benchmark_tasks/misconceptions) | Big bench misconceptions consists of 219 true or false questions regarding common misconceptions about a variety of topics including urban legends, stereotypes, basic science, and law |
| 2019 | MMLU (Measuring Massive Multitask Language Understanding) - World Knowledge + Problem Solving Ability | [Paper](https://arxiv.org/abs/2009.03300) | MMLU consists of 14,042 four-choice multiple choice questions distributed across 57 categories. The questions are in the style of academic standardized tests and the model is provided the question and the choices and is expected to choose between A, B, C, and D as its outputs. The subjects range from jurisprudence, to math, to morality |
| 2019 | ARC easy | [Leaderboard & Dataset - Allen Institute for AI](https://leaderboard.allenai.org/arc_easy/submissions/get-started) | ARC easy consists of 2,376 easy four-choice multiple choice science questions drawn from grade 3-9 science exams. The questions rely on world knowledge related to basic science |
| 2018 | ARC challenge | [Leaderboard & Dataset - Allen Institute for AI](https://allenai.org/data/arc) | ARC challenge consists of 1,172 hard four-choice multiple choice science questions drawn from grade 3-9 science exams. The questions rely on scientific world knowledge and some procedural reasoning |
---
## Commonsense Reasoning 
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> Commonsense reasoning tests the models’ ability to perform basic reasoning tasks that require commonsense knowledge of objects, their properties, and their behavior.
> 
| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
| 2022 | BIG-bench: Strategy QA | | BIG-bench strategy QA consists of 2,289 very eclectic yes/no questions on a wide range of commonsense subjec e.g “Can fish get Tonsilitis?” |
| 2022 | BIG-bench: Strange Stories | | BIG-bench strange stories consists of 174 short stories followed by a two-choice multiply choice question in which the model is asked to make commonsense inferences about the characters in the stories, how they might feel, and why they act in certain ways. Random baseline accuracy: 50% |
| 2022 | BIG-bench: Novel Concepts | | BIG-bench novel concepts consists or 32 find-the-common-concept problems in which the model is given 3 words and has to choose from among 4 possible concepts that they all have in common. Random baseline accuracy: 25% |
| 2019 | PIQA | | PIQA consists of 1,838 commonsense physical intuition 2-choice multiple choice questions. Random baseline accuracy: 50%|
| 2018 | OpenBook QA |  | OpenBook QA consists of 500 four-choice multiple choice questions that rely on basic physical and scientific intuition about common objects and entities. Random baseline accuracy: 25% |
| 2011 | COPA | | COPA consists of 100 cause/effect multiple choice questions in which the model is prompted with a premise and the model must choose correctly between two possible causes/effects of the premise. Random baseline accuracy: 50% |
---
## Language Understanding
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> Language understanding tasks evaluate the model’s ability to understand the structure and properties of languages, including determining which types of sentences are more likely than others, performing translations between languages, and identifying languages.
> 
| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
| 2022 | BIG bench conceptual combinations |  | BIG bench conceptual combinations consists of 103 four-choice multiple choice questions in which the model is presented with a made up word and its definition along with a multiple choice question regarding the meaning of a sentence using that made up word. The model is then expected to select the correct answer among the choices presented.Random baseline accuracy: 25%|
| 2022 | BIG bench conlang translation |  | BIG bench conlang translation consists of 164 example problems in which the model is given translations of simple sentences between English and some fake constructed language. The model is then tested for its ability to translate a complex sentence in the fake language into English.|
| 2019 | HellaSwag |  | HellaSwag consists of 10,042 multiple choice scenarios in which the model is prompted with a scenario and choose the most likely conclusion to the scenario from four possible options. Random baseline accuracy: 25% |
| 2016 | LAMBADA |  | LAMBADA consists of 5,153 passages take from books. The model is expected to read the first N-1 words of each passage and predict the final token.|
| 2012 | BIG bench language identification |  | BIG bench language identification consists of 10,000 four-choice multiple choice questions in which a sentence in some language besides english is presented and the model is prompted to identify the language of the sentence amongst four options. Random baseline accuracy: 25% |
| 2012 | Winograd Schema Challenge |  | The Winograd Schema Challenge consists of 273 scenarios in which the model must use semantics to correctly resolve the anaphora in a sentence. Two possible beginnings to a sentence are presented as well as an ending. Both involve some anaphora being resolved in a different way, only one of which would be semantically valid, and the model must choose which option produces the valid resolution. Random baseline accuracy: 50% |
| 2012 | Winogrande |  | The Winogrande consists of 1,267 scenarios in which two possible beginnings of a sentence are presented along with a single ending. Both combinations are syntactically valid, but only one is semantically valid, and the model must choose the one that is semantically valid. Random baseline accuracy: 50%|
---
## Symbolic Problem Solving 
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> Symbolic problem solving tasks test the model’s ability to solve a diverse range of symbolic tasks including arithmetic, logical reasoning, algorithms, and algebra.

| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  |  |  |
---
## Reading Comprehension 
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> Reading comprehension benchmarks test a model’s ability to answer questions based on the information in a passage of text. It includes a number of multiple choice benchmarks as well as some benchmarks that require the model to output an exact correct answer.

| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- |:- |
|  |  |  |
---
## Programming
[<img src="images/back_button.png" width="25" height="25">](#frameworks--benchmarks-by-topic)
> Programming tasks evaluate the model's ability to understand code, write functionally correct code given a specification, simulate code, and document code.

| Year | Title | Github/Dataset | Notes | 
| :- | :- | :- | :- |
| 2022 | [Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374)  | [Github](https://github.com/openai/human-eval) [Dataset](https://paperswithcode.com/dataset/humaneval) | HumanEval code generation - consists of 164 python programming challenges, in which the model is presented with the method signature and docstring comment for a python program and is expected to complete the program. We then test the resultant code’s functional correctness on a number of test input/output pairs. |
***
## Datasets 
[<img src="images/back_button_2.png" width="25" height="25">](#some-concepts)
| Year | Title | Notes | 
| :- | :- | :- |
|  | [Jeopardy Data at Higginface](https://huggingface.co/datasets/jeopardy) |  |
***
## Other Repos 
[<img src="images/back_button_2.png" width="25" height="25">](#some-concepts)
| Repo | Notes | 
| :-: | :-: |
|[Papers and resources for LLMs evaluation](https://github.com/MLGroupJLU/LLM-eval-survey) | Exhaustive list of benchmarks |

 
