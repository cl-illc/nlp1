---
layout: post
title: Thesis projects
date:   2019-09-03
author: Katia
categories: Info
mathjax: true
---

Hello everyone,

NLP researchers at UvA have proposed some exciting thesis projects for you! You can find them below If you are interested in any of the projects, please contact the prospective supervisor directly.


##Probing for typological properties in multilingual word and sentence representations 

Supervisor: Ekaterina Shutova 

Collaborators: Douwe Kiela (Facebook AI Research)

#Description

Languages may share universal features at a deep, abstract level, but the structures found in real-world, surface-level natural language vary significantly. This variation makes it challenging to transfer NLP models across languages or to develop systems that apply to a wide range of languages. As a consequence, the availability of NLP technology is limited to a handful of resource-rich languages, leaving many other languages behind. Understanding linguistic variation in a systematic way is crucial for the development of effective multilingual NLP applications, thus making NLP technology more accessible globally. 

In recent years, much NLP research has focused on the development of multilingual models, typically based on multilingual joint learning or zero-shot transfer learning across languages. Much of this research has utilized multilingual word or sentence representations, that project words or sentences in multiple languages into a shared multilingual semantic space. Such models abstract over language-specific features and represent words and sentences from multiple languages in a language-agnostic manner, such that words or sentences with similar meanings (regardless of an actual language) obtain similar representations. While this work has met with success, enabling effective model transfer across languages, little is known about the linguistic properties of individual languages that such representations encode. The goal of this project is to investigate to what extent multilingual word and sentence representations capture the patterns of cross-lingual similarity and variation. We will use techniques from the rapidly growing field of interpretation of neural networks (e.g. Tenney et al. 2019) to design methods for probing state-of-the-art multilingual contextualised word representations and sentence encoders, such as LASER (Artexte and Schwenk, 2018), multilingual BERT (Devlin et al., 2019) or XLM (Lample and Conneau, 2019), for a range of language characteristics. We will thus investigate to what extent the above models encode typological features pertaining to syntactic and semantic structure, how these are represented within the network and generalised across language families. We will also look at whether these models can be used to automatically induce the patterns of linguistic variation across language families.

This is an ambitious project, suitable for students with a background and interest in machine learning and keen to conduct novel research. We hope that it would lead to a publication.

What are our expectations of the student?

Independent and proactive attitude and an interest in artificial intelligence
Solid maths background: calculus, linear algebra, probability and statistics
Advanced programming skills (algorithms and data structures; ideally experience with Pytorch or other deep learning libraries)
Knowledge and skill in developing and applying machine learning algorithms (particularly, interest and experience in deep learning) 
Good familiarity with and experience in NLP; but don’t worry we will help you to fill in the gaps.

#Further reading:

Edoardo Ponti, Helen O'Horan, Yevgeni Berzak, Ivan Vulic, Roi Reichart, Thierry Poibeau, Ekaterina Shutova, Anna Korhonen. 2018. Modeling Language Variation and Universals: A Survey on Typological Linguistics for Natural Language Processing.  In arXiv e-prints, abs/1807.00914. 

Mikel Artetxe and Holger Schwenk. 2018. Massively Multilingual Sentence Embeddings for Zero-Shot Cross-Lingual Transfer and Beyond. ArXiv.

Tal Schuster, Ori Ram, Regina Barzilay, Amir Globerson. Cross-Lingual Alignment of Contextual Word Embeddings, with Applications to Zero-shot Dependency Parsing. In Proceedings of NAACL 2019.

Jacob Devlin, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. 2019. BERT: Pre-training of
deep bidirectional transformers for language understanding. In Proceedings of NAACL 2019.

Guillaume Lample and Alexis Conneau. 2019. Cross-lingual Language Model Pretraining. ArXiv.

Ian Tenney, Patrick Xia, Berlin Chen, Alex Wang, Adam Poliak, R. Thomas McCoy, Najoung Kim, Benjamin Van Durme, Samuel R. Bowman, Dipanjan Das, and Ellie Pavlick. 2019. What do you learn from context? Probing for sentence structure in contextualized word representations. Proceedings of ICLR 2019.


##Abusive language detection in conversation

Supervisor: Ekaterina Shutova

Collaborators: Helen Yannakoudakis (University of Cambridge) and Pushkar Mishra (Facebook AI Research)

#Description

With the advent of social media, aggressive and abusive behaviour online has become one of its prominent features. The undesirable psychological effects of online abuse on individuals make it an important societal problem of our time. The term abuse encompasses hate speech, racism, sexism, derogatory language, personal attacks and cyber­bullying. In recent years, a new research effort on automated abuse detection has sprung up in the field of NLP. The community has experimented with a range of techniques such as recurrent and convolutional neural networks, character-based models and graph-based methods capturing the properties of the social network. While these methods have achieved substantial success, they have an important limitation in that they focus on modeling the linguistic properties of comments in isolation from other comments. Abuse is, however, inherently a situational and contextual phenomenon --- it can only be interpreted as part of a wider conversation between users on the Internet. This means that individual comments can be difficult to classify without modeling their respective contexts. For instance, Mishra et al. (2018) have pointed out that many comments in widely-used Twitter datasets do not contain sufficient lexical or semantic information to detect abuse even in principle and techniques for modeling discourse and elements of pragmatics are needed. In this project, we will address this problem and develop novel abuse detection methods that capture the history of the conversation and the behavior of the users as it develops over time. We will use techniques from the domain of discourse and dialogue modelling (such as memory networks, recurrent neural networks with attention etc), as well as graph-based methods (such as graph convolutional networks), to model interactions between the users. In addition, we will also incorporate insights from experimental research on conversational behaviour among individuals and groups in fields such as psychology and linguistics.

This is an ambitious project, suitable for students with a background and interest in machine learning and keen to conduct novel research. We hope that it would lead to a publication.

What are our expectations of the student?

Independent and proactive attitude and an interest in artificial intelligence
Solid maths background: calculus, linear algebra, probability and statistics
Advanced programming skills (algorithms and data structures; ideally experience with Pytorch or other deep learning libraries)
Knowledge and skill in developing and applying machine learning algorithms (particularly, interest and experience in deep learning) 
Good familiarity with and experience in NLP; but don’t worry we will help you to fill in the gaps.

#Further reading:

P. Mishra, M. Del Tredici, H. Yannakoudakis, and E. Shutova. Author profiling for abuse detection. In Proceedings of COLING 2018, pages 1088–1098. ACL, 2018. 

P. Mishra, E. Shutova, and H. Yannakoudakis. Neural character-­based composition models for abuse detection. In Proceedings of the EMNLP Workshop on Abusive Language Online, ACL, 2018. 

J. Pavlopoulos, P. Malakasiotis, and I. Androutsopoulos. Deep learning for user comment moderation. In Proceedings of the 1st Workshop on Abusive Language Online, pages 25–35. ACL, 2017.

Z. Waseem, T. Davidson, D. Warmsley, and I. Weber. Understanding abuse: A typology of abusive language detection subtasks. In Proceedings of the 1st Workshop on Abusive Language Online, pages 78–84. ACL, 2017. 

Justine Zhang, Jonathan P. Chang, Cristian Danescu-Niculescu-Mizil, Lucas Dixon, Yiqing Hua, Nithum Thain, Dario Taraborelli. 2018. Conversations Gone Awry: Detecting Early Signs of Conversational Failure. In Proceedings of ACL 2018.

Pushkar Mishra, Helen Yannakoudakis and Ekaterina Shutova. 2019. Tackling Online Abuse: A Survey of Automated Abuse Detection Methods. In ArXiv e-prints.

Pushkar Mishra, Marco del Tredici, Helen Yannakoudakis and Ekaterina Shutova. 2019. Abusive language detection with graph convolutional networks. In Proceedings of NAACL-HLT 2019. Minneapolis, USA.


##Modelling the structure and linguistic behaviour of online communities to detect misinformation

Supervisor: Ekaterina Shutova

Collaborators: Helen Yannakoudakis (University of Cambridge) and Pushkar Mishra (Facebook AI Research)

#Description

The spread of misinformation online leads to undesirable consequences in many areas of societal life, most notably visible in the political arena and healthcare. Misinformation appears in many forms, from content that is outright false (known as “fake news”) to propaganda and highly opinionated content, presenting a biased view of the world or carefully selecting facts to reinforce a particular perspective. Recent years have seen a growing interest in automatic detection of false and misleading content in the field of NLP, with researchers typically defining the problem as a classification of articles as misleading or not. The majority of existing approaches in this area have focused on modelling the structure, style and content of the online documents and comments, paying less attention to ways in which misleading content is propagated online. This project aims to advance this line of research by modelling the structure of online communities within which misinformation spreads and the linguistic behavior of the users in these communities, which is indicative of their stance on a given issue. We will experiment with state-of-the-art methods for representation learning on graphs and networks, such as graph convolutional networks (Kipf and Welling, 2017) and GraphSAGE (Hamilton et al., 2017) among others.

This is an ambitious project, suitable for students with a background and interest in machine learning and keen to conduct novel research. We hope that it would lead to a publication.

What are our expectations of the student?
Independent and proactive attitude and an interest in artificial intelligence
Solid maths background: calculus, linear algebra, probability and statistics
Advanced programming skills (algorithms and data structures; ideally experience with Pytorch or other deep learning libraries)
Knowledge and skill in developing and applying machine learning algorithms (particularly, interest and experience in deep learning) 
Good familiarity with and experience in NLP; but don’t worry we will help you to fill in the gaps.

#Further reading:

Thomas N. Kipf and Max Welling. 2017. Semi-supervised classification with graph convolutional
networks. In Proceedings of the 5th International Conference on Learning Representations, ICLR 2017.

William L. Hamilton, Rex Ying and Jure Leskovec. 2017. Inductive Representation Learning on Large Graphs. In Proceedings of NIPS 2017.

Pushkar Mishra, Marco del Tredici, Helen Yannakoudakis and Ekaterina Shutova. 2019. Abusive language detection with graph convolutional networks. In Proceedings of NAACL-HLT 2019. Minneapolis, USA.

K. Xu, W. Hu, J. Leskovec, S. Jegelka. How Powerful Are Graph Neural Networks? In Proceedings of ICLR, 2019.

Fatemeh Torabi Asr, Maite Taboada. 2019. Big Data and quality data for fake news and misinformation detection. Big Data and Society.




##Lexical ambiguity and polysemy with density matrices

Supervisors: Martha Lewis (ILLC) and Ekaterina Shutova (ILLC)

#Description

Polysemy is the phenomenon that words adopt different meanings according to their contexts of use. This can range from clear-cut ambiguity such as `diamond' with the meaning `gemstone' or `shape' to more subtle polysemous meaning such as `window' in `Marcelle broke the window' (the glass) or `The bird flew out of the window' (the opening). Approaches to modelling polysemy in distributional semantics include building one representation that can represent all senses at once, or alternatively, representing different senses as separate vectors.

A recent extension to standard vector-based semantics uses the notion of a density matrix from quantum theory to encode a statistical ensemble of vectors. This has been posited to model lexical ambiguity (Piedeleu et al., 2016) and entailment (Sadrzadeh et al., 2018, Bankova et al., 2019, Lewis 2019). Since density matrices can encode a number of vectors within one representation, they form a middle ground between the two approaches described above.

Furthermore, density matrix representations can be understood within a tensor-based compositional distributional semantic model (Coecke et al., 2010, Baroni and Zamparelli 2010). The resolution of ambiguous terms in context can therefore be realised within the composition of strings of words into phrases.

This project will investigate different ways of building density matrix representations of words, including designing novel neural network architectures inspired by the density matrix approach. Ways of composing the matrices to form phrase and sentence representations will also be a topic of research. Comparisons will be made with recent work on contextualised word representations (Peters et al, 2018, Devlin et al, 2019), and the project would contribute to this line of research by designing new models.  The representations and composition methods will be assessed against datasets that require disambiguation, such as for Mitchell and Lapata (2008), Grefenstette and Sadrzadeh (2011), or WiC: The Word-in-Context Dataset (https://pilehvar.github.io/).

Following on from this, the use of density matrices to encode polysemy can be investigated within the context of metaphor. Metaphor can be viewed as a type of polysemy (Peters and Peters, 2000), and the effectiveness of disambiguating literal and metaphorical senses of a word has been shown in Gutierrez et al., (2016). This part of the project will investigate the effectiveness of using density matrix representations in metaphor identification and/or interpretation. 

This is an ambitious project, suitable for students with a background and interest in mathematics and machine learning and keen to conduct novel research. We hope that it would lead to a publication.

What are our expectations of the student?
Independent and proactive attitude and an interest in artificial intelligence
Solid maths background: calculus, linear algebra, probability and statistics
Advanced programming skills (algorithms and data structures; ideally experience with Pytorch or other deep learning libraries)
Knowledge and skill in developing and applying machine learning algorithms (particularly, interest and experience in deep learning) 
Good familiarity with and experience in NLP; but don’t worry we will help you to fill in the gaps.


#Further reading:

Bankova, D., Coecke, B., Lewis, M., & Marsden, D. (2019). Graded hyponymy for compositional distributional semantics. Journal of Language Modelling, 6(2), 225-260. http://jlm.ipipan.waw.pl/index.php/JLM/article/view/230

Baroni, M., & Zamparelli, R. (2010). Nouns are vectors, adjectives are matrices: Representing adjective-noun constructions in semantic space. In Proceedings of the 2010 Conference on Empirical Methods in Natural Language Processing (pp. 1183-1193). Association for Computational Linguistics. https://www.aclweb.org/anthology/D10-1115

Coecke, B., Sadrzadeh, M., & Clark, S. (2010). Mathematical Foundations for a Compositional Distributed Model of Meaning. Lambek Festschrift, Linguistic Analysis, vol. 36. https://arxiv.org/abs/1003.4394

Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2019, June). BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. In Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers) (pp. 4171-4186). https://arxiv.org/abs/1810.04805

Grefenstette, E., & Sadrzadeh, M. (2011, July). Experimental support for a categorical compositional distributional model of meaning. In Proceedings of the Conference on Empirical Methods in Natural Language Processing (pp. 1394-1404). Association for Computational Linguistics. https://www.aclweb.org/anthology/D11-1129

Gutierrez, E. D., Shutova, E., Marghetis, T., & Bergen, B. (2016, August). Literal and metaphorical senses in compositional distributional semantic models. In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) (pp. 183-193). https://www.aclweb.org/anthology/P16-1018

Lewis, M., (2019). Compositional Hyponymy with Positive Operators. To appear at RANLP 2019. (preprint available on request)

Mitchell, J., & Lapata, M. (2008, June). Vector-based models of semantic composition. In proceedings of ACL-08: HLT (pp. 236-244). https://www.aclweb.org/anthology/P08-1028

Peters, W., & Peters, I. (2000, May). Lexicalised Systematic Polysemy in WordNet. In LREC. http://www.lrec-conf.org/proceedings/lrec2000/pdf/148.pdf

Peters, M. E., Neumann, M., Iyyer, M., Gardner, M., Clark, C., Lee, K., & Zettlemoyer, L. (2018). Deep contextualized word representations. In Proceedings of NAACL-HLT (pp. 2227-2237). https://arxiv.org/abs/1802.05365

Piedeleu, R., Kartsaklis, D., Coecke, B., & Sadrzadeh, M. (2015). Open System Categorical Quantum Semantics in Natural Language Processing. In 6th Conference on Algebra and Coalgebra in Computer Science (CALCO 2015). Schloss Dagstuhl-Leibniz-Zentrum fuer Informatik. https://arxiv.org/abs/1502.00831

Sadrzadeh, M., Kartsaklis, D., & Balkır, E. (2018). Sentence entailment in compositional distributional semantics. Annals of Mathematics and Artificial Intelligence, 82(4), 189-218.


