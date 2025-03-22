# 🎭 Formal & Sentiment-Constrained Poetry Generation with PPL-MCTS and GPT
This repository contains the work done for the course Research Project in Machine Learning, Data Science and Artificial Intelligence at Aalto University.
This project explores the generation of formal poetry with controlled sentiment using a fine-tuned GPT-2 language model and the PPL-MCTS (Perplexity-guided Monte Carlo Tree Search) algorithm. The goal is to produce high-quality, rhyming, and sentiment-specific poetry by combining powerful language modeling with constraint-aware generation techniques.
## ✨ Highlights
*	**Baseline:** Fine-tuned GPT-2 model on poetic corpora.
*	**Constraint Satisfaction:** Integration of PPL-MCTS for rhyme scheme adherence and sentiment control.
*	**Performance:**
  *	🪄 **+34%** improvement in rhyme generation over the baseline.
  *	❤️ **88.75%** accuracy in sentiment-constrained poetry generation.

## 📁 Repository Structure
| **File** |	**Description** |
| ----------- | ----------- |
| RML_report.py	| A detailed report script containing sections for introduction, methods, results, and conclusions—ideal for academic write-up or presentation. |
| experiments_rhyming.py |	Script to generate poems with rhyme constraints. |
| experiments_emotion.py | Script to generate poems with specific sentiment (e.g., joy, sadness). |
|models/ |	(You must specify or change the path to your fine-tuned GPT-2 model here) |
________________________________________
## 🚀 Getting Started
1. **Clone the Repository**
```
git clone https://github.com/MateoRuedaMolano/PoetryGeneration.git
cd PoetryGeneration
```

2. **Install Dependencies**
Ensure you have Python 3.8+ and install the required packages:
```
pip install -r requirements.txt
```

Make sure to also install HuggingFace's transformers library and nltk if not already installed.
3. **Update Model Path**
In both experiments_rhyming.py and experiments_emotion.py, change the model path to point to your fine-tuned GPT-2 model:
```
model_path = "path/to/your/fine_tuned_gpt_model"
```

________________________________________
## 🧪 Running Experiments
**Generate Rhyming Poems**
```
python experiments_rhyming.py
```

Generate Sentiment-Constrained Poems
```
python experiments_emotion.py
```

The defined categories are positive, negative, mixed and impartial.
________________________________________
## 📊 Results Summary
| **Metric**	| **Value** |
| **Rhyme Improvement** |	+34% over baseline |
| **Sentiment Accuracy**	| 88.75% |
| **Text Coherence & Quality** |	Similar perplexity |
________________________________________
## 📚 References
This project builds upon ideas from recent work in controllable text generation and constrained decoding strategies. For full methodology, see the RML_report.py.
________________________________________
## 📌 Notes
*	If you use this code or build on it, please consider citing the associated research/report.
*	Contributions and suggestions are welcome!

