This is a list of papers concerning the ethical issues in NLP. Updating... Any suggestion or issue are welcome.
* 💾 stands for releasing new dataset.


## Table of Contents
- [Survey and Framework](#survey)
- [Semantic Bias](#semantic-bias)
- [Bias in Language Generation](#generation)
- [Downstream Task](#downstream-task)
- [Hate Speech](#hate-speech)
- [Benchmarks](#benchmarks)

## Survey and Framework
- [Mitigating Gender Bias in Natural Language Processing: Literature Review](https://www.aclweb.org/anthology/P19-1159) (ACL 2019)
- [Language (Technology) is Power: A Critical Survey of “Bias” in NLP](https://www.aclweb.org/anthology/2020.acl-main.485/) (ACL 2020)
- [Predictive Biases in Natural Language Processing Models- A Conceptual Framework and Overview](https://www.aclweb.org/anthology/2020.acl-main.468/) (ACL 2020)
- [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](http://faculty.washington.edu/ebender/papers/Stochastic_Parrots.pdf) (FAccT 2021)

## Semantic Bias

### Word Embedding

- [Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings](https://arxiv.org/pdf/1607.06520.pdf) (NIPS 2016)
- [Semantics derived automatically from language corpora contain human-like biases](https://science.sciencemag.org/content/356/6334/183) (Science 2017)
- [Word embeddings quantify 100 years of gender and ethnic stereotypes](https://arxiv.org/pdf/1711.08412.pdf) (PNAS 2018)
- [Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them](https://www.aclweb.org/anthology/N19-1061/) (NAACL 2019)
- [Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings](https://www.aclweb.org/anthology/N19-1062/) (NAACL 2019)
- [Double-Hard Debias: Tailoring Word Embeddings for Gender Bias Mitigation](https://www.aclweb.org/anthology/2020.acl-main.484/) (ACL 2020)
- [Gender Bias in Multilingual Embeddings and Cross-Lingual Transfer](https://www.aclweb.org/anthology/2020.acl-main.260/) (ACL 2020) - 💾
- [Exploring the Linear Subspace Hypothesis in Gender Bias Mitigation](https://www.aclweb.org/anthology/2020.emnlp-main.232) (EMNLP 2020)
- [Unequal Representations: Analyzing Intersectional Biases in Word Embeddings Using Representational Similarity Analysis](https://www.aclweb.org/anthology/2020.coling-main.151) (COLING 2020)
- [Intrinsic Bias Metrics Do Not Correlate with Application Bias](https://arxiv.org/pdf/2012.15859.pdf) (arxiv)

### Contextual Embedding 

- [On Measuring Social Biases in Sentence Encoders](https://www.aclweb.org/anthology/N19-1063/) (NAACL 2019)
- [Gender Bias in Contextualized Word Embeddings](https://www.aclweb.org/anthology/N19-1064/) (NAACL 2019)
- [Measuring Bias in Contextualized Word Representations](https://www.aclweb.org/anthology/W19-3823/) (ACL 2019 Workshop)
- [Assessing Social and Intersectional Biases in Contextualized Word Representations](https://papers.nips.cc/paper/2019/file/201d546992726352471cfea6b0df0a48-Paper.pdf) (NeurIPS 2019)
- [Towards Debiasing Sentence Representations](https://www.aclweb.org/anthology/2020.acl-main.488/) (ACL 2020)
- [Interpreting Pretrained Contextualized Representations via Reductions to Static Embeddings](https://www.aclweb.org/anthology/2020.acl-main.431/) (ACL 2020)
- [Monolingual and Multilingual Reduction of Gender Bias in Contextualized Representations](https://www.aclweb.org/anthology/2020.coling-main.446/) (COLING 2020)
- [Unmasking Contextual Stereotypes: Measuring and Mitigating BERT’s Gender Bias](https://www.aclweb.org/anthology/2020.gebnlp-1.1/) (COLING 2020)
- [FairFil: Contrastive Neural Debiasing Method for Pretrained Text Encoders](https://openreview.net/forum?id=N6JECD-PI5w) (ICLR 2021)

## Language Generation
- [The Woman Worked as a Babysitter: On Biases in Language Generation](https://www.aclweb.org/anthology/D19-1339/) (EMNLP 2019)
- [SOCIAL BIAS FRAMES: Reasoning about Social and Power Implications of Language](https://www.aclweb.org/anthology/2020.acl-main.486/) (ACL 2020) - 💾
- [Mitigating Gender Bias for Neural Dialogue Generation with Adversarial Learning](https://www.aclweb.org/anthology/2020.emnlp-main.64/) (EMNLP 2020)
- [Queens are Powerful too: Mitigating Gender Bias in Dialogue Generation](https://www.aclweb.org/anthology/2020.emnlp-main.656/) (EMNLP 2020)
- [Towards Controllable Biases in Language Generation](https://www.aclweb.org/anthology/2020.findings-emnlp.291/) (EMNLP 2020 Findings)
- [Does Gender Matter? Towards Fairness in Dialogue Systems](https://www.aclweb.org/anthology/2020.coling-main.390) (COLING 2020)

## Downstream Task

### Coreference Resolution
- [Mind the GAP: A Balanced Corpus of Gendered Ambiguous Pronouns](https://www.aclweb.org/anthology/Q18-1042/) (TACL 2018) - 💾
- [Gender Bias in Coreference Resolution](https://www.aclweb.org/anthology/N18-2002/) (NAACL 2018) - 💾
- [Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods](https://www.aclweb.org/anthology/N18-2003/) (NAACL 2018) - 💾
- [Stereotype and Skew: Quantifying Gender Bias in Pre-trained and Fine-tuned Language Models](https://arxiv.org/pdf/2101.09688.pdf) (EACL 2021)

### Image Captioning
- [Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://www.aclweb.org/anthology/D17-1323/) (EMNLP 2017)

### Sentiment Analysis
- [Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems](https://www.aclweb.org/anthology/S18-2005/) (ACL 2018) - 💾

### Machine Translation
- [Towards Cross-Lingual Generalization of Translation Gender Bias](https://dl.acm.org/doi/pdf/10.1145/3442188.3445907) (FAccT 2021)

## Hate speech
- [The Risk of Racial Bias in Hate Speech Detection](https://www.aclweb.org/anthology/P19-1163/) (ACL 2019)
- [Social Biases in NLP Models as Barriers for Persons with Disabilities](https://www.aclweb.org/anthology/2020.acl-main.487/) (ACL 2020)
- [Latent-Optimized Adversarial Neural Transfer for Sarcasm Detection]() (NAACL 2021)

## Analysis

- [Investigating Gender Bias in Language Models Using Causal Mediation Analysis](https://proceedings.neurips.cc//paper_files/paper/2020/hash/92650b2e92217715fe312e6fa7b90d82-Abstract.html) (NeurIPS 2020)
- [Diverse Adversaries for Mitigating Bias in Training](https://arxiv.org/pdf/2101.10001.pdf) (arxiv)

## Benchmarks

- [StereoSet: Measuring stereotypical bias in pretrained language models](https://stereoset.mit.edu/) (arxiv 2020) - 💾
- [CrowS-Pairs: A Challenge Dataset for Measuring Social Biases in Masked Language Models](https://www.aclweb.org/anthology/2020.emnlp-main.154/) (EMNLP 2020) - 💾
- [BOLD: Dataset and Metrics for Measuring Biases in Open-Ended Language Generation](https://arxiv.org/abs/2101.11718) (FAccT 2021) - 💾