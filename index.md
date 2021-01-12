---
layout: page
title: How Can Findings About The Brain Improve AI Systems?
hide_footer: true
hero_image: img/vienna.jpg
---

## How Can Findings About The Brain Improve AI Systems?
[ICLR 2021](https://iclr.cc/Conferences/2021/) Workshop, Taking place virtually
##### May 8, 2021

{% comment %} 
## Google Group
[https://groups.google.com/d/forum/context-comp](https://groups.google.com/d/forum/context-comp)
{% endcomment %} 

## About
The brain comprises billions of neurons organized into an intricate network of highly specialized functional areas. This biological cognitive system can efficiently process vast amounts of multi-modal data to perceive and react to its ever-changing environment. Unlike current AI systems, it does not struggle with domain adaptation, few-shot learning, or common-sense reasoning. However, it also differs from artificial neural networks in many ways. For instance, there is evidence that the brain sparsely encodes information (e.g. the famous `Jennifer Aniston' neuron [1]). Deep neural networks, on the other hand, are dense and redundant. While learning is reward- and feedback-based in both biological and artificial networks, it is not clear that the brain is implementing anything analogous to backpropagation. Further, evidence suggests that biological neurons can replicate recurrence [2] but their ability to do convolution or operations similar to dot-product attention is unclear. 
However, inspiration from neuroscience has benefited AI in the past: dopamine reward signals inspired TD learning [3], modern convolutional networks mimic the deep, nested information flow in visual cortex [4], and hippocampal replay of previous experiences has brought about experience replay in reinforcement learning [5]. Recent work at the intersection of neuroscience and AI has made progress in directly integrating neuroscientific data with AI systems and has led to learned representations that are more robust to label corruptions [6,7], allow for better generalization in some language tasks [8,9], and provide new ways to interpret [8,10,11,12,13,14] and evaluate [15,16,17,18,19,20,21,22] what domain-relevant information is learned by deep neural networks. In this workshop, we aim to examine the extent to which insights about the brain can lead to better AI. 

## Important Dates

|---
| Name | Date
|:------ |:------
| Paper Submission Deadline | March 10th, 2021
| Final Decisions | March 24th, 2021
| Camera Ready Deadline | April 16th, 2021
| Workshop Date | May 8th, 2021


## Schedule

Date: Saturday May 8th, 2021

Taking place virtually, Vienna Time (GMT+1)

|---
| Time | Event
|:------ |:------
|08:45 AM | Opening Remarks
|09:00 AM | Invited Speaker 1 with Discussion
|10:00 AM | Invited Speaker 2 with Discussion
|11:00 AM | Coffee Break
|11:30 AM | Spotlights/Contributed Talks 1
|12:00 AM | Lunch Break
|12:45 AM | Invited Speaker 3 with Discussion
|01:45 PM | Spotlights/Contributed Talks 2
|02:15 PM | Coffee Break
|02:45 PM | Invited Speaker 4 with Discussion
|03:45 PM | Invited Speaker 5 with Discussion
|04:45 PM | Panel Discussion
|06:15 PM | Closing Remarks
|---


{% include people.html name="speakers" %}


{% include people.html name="organizers" %}



## Call for Papers

Submit at: [https://cmt3.research.microsoft.com/BRAIN2AI2021/Submission/Index](https://cmt3.research.microsoft.com/BRAIN2AI2021/Submission/Index)

We will consider the following (non-exhaustive) list of topics for contribution:
- What areas of AI can most benefit from neuroscientific insight (e.g. commonsense reasoning, symbol grounding, architecture search and learning rules, continual learning, interpretability, few-shot learning)?
- What are the current bottlenecks in integrating neuroscientific data with AI systems (e.g. limited amount of data, amount of noise, mismatch in experimental tasks)?
- Which granularities of neuroscientific data are best suited to integrate with AI systems (e.g. recordings from cells of non-human species, multi-unit recordings from local neuron populations, neuroimaging recordings)?
- What are the benefits and limits of data-driven approaches that integrate neuroscientific data into the training process of AI systems?
- How can neuroscientific data benefit AI systems that perform tasks at which humans excel (e.g. natural language processing, vision)?

**Formatting Instructions:**  All submissions must be in PDF format. Submissions are limited to four content pages, including all figures and tables; additional pages containing only references are allowed. You must format your submission using the [ICLR 2021 LaTeX style files](https://github.com/ICLR/Master-Template/raw/master/archive/iclr2021.zip). Submissions that meaningfully violate the ICLR style (e.g., by decreasing margins or font sizes) or page limits may be rejected without further review. All submissions should be anonymous.

The workshop itself will be geared towards more dynamic and interactive discussion focused on Q&A sessions, with less time devoted to speakers giving one-sided talks to attendees.
Invited speakers will give live talks but will be asked to devote as much time to audience questions as to the presentation. Accepted abstracts and papers will result in, at minimum, a spotlight talk. Contributed spotlight talks will be pre-recorded to ensure that time traditionally allotted to posters will be used to foster discussion and participant questions from the contributed talks. 

All presenters, whether invited or contributed, will be given live virtual "coffee break" rooms during all breaks in the conference schedule to engage in small group discussions with participants.
Discussions around talks will be organized in live virtual ``breakout'' rooms with similar topic and themes so that workshop attendees and presenters can get the chance to interact with each other in a less formal, discussion-centric setting.
We intend to encourage spotlight talk applicants to fully leverage the didactic benefits of the digital medium by including elements of animation or interactivity into their presentations. The themes for the breakout rooms will be changed for
each break to give speakers, panelists and participants a chance to focus on different aspects of their work and to interact with different groups.

The review process is double-blind. We also welcome published papers that are within the scope of the workshop (without re-formatting). Already-published papers do not have to be anonymous. They are eligible for poster sessions and will only have a very light review process.

Please redirect questions and all future correspondence to [rjantonello@utexas.edu](mailto:rjantonello@utexas.edu).


## Program Committee

TBA


## References


1. Quiroga, R. Quian, et al. "Invariant visual representation by single neurons in the human brain." Nature 435.7045 (2005): 1102-1107.
2. Kietzmann, Tim C., et al. "Recurrence is required to capture the representational dynamics of the human visual system." Proceedings of the National Academy of Sciences 116.43 (2019): 21854-21863.
3. Glimcher, Paul W. "Understanding dopamine and reinforcement learning: the dopamine reward prediction error hypothesis." Proceedings of the National Academy of Sciences 108.Supplement 3 (2011): 15647-15654.
4. Hassabis, Demis, et al. "Neuroscience-inspired artificial intelligence." Neuron 95.2 (2017): 245-258.
5. Davidson, Thomas J., Fabian Kloosterman, and Matthew A. Wilson. "Hippocampal replay of extended experience." Neuron 63.4 (2009): 497-507.
6. Li, Zhe, et al. "Learning from brains how to regularize machines." Advances in Neural Information Processing Systems. 2019. Vishwanathan, and R. Garnett, editors,Advances in Neural Information ProcessingSystems 30, pages 5998–6008. Curran Associates, Inc., 2017.
7. Federer, Callie, et al. "Improved object recognition using neural networks trained to mimic the brain’s statistical properties." Neural Networks 131 (2020): 103-114.
8. Toneva, Mariya, and Leila Wehbe. "Interpreting and improving natural-language processing (in machines) with natural language-processing (in the brain)." Advances in Neural Information Processing Systems. 2019.
9. Schwartz, Dan, Mariya Toneva, and Leila Wehbe. "Inducing brain-relevant bias in natural language processing models." Advances in Neural Information Processing Systems. 2019.
10. Fyshe, Alona, et al. "Interpretable semantic vectors from a joint model of brain-and text-based meaning." Proceedings of the conference. Association for Computational Linguistics. Meeting. Vol. 2014. NIH Public Access, 2014.
11. Søgaard, Anders. "Evaluating word embeddings with fMRI and eye-tracking." Proceedings of the 1st Workshop on Evaluating Vector-Space Representations for NLP. 2016.
12. Eickenberg, Michael, et al. "Seeing it all: Convolutional network layers map the function of the human visual system." NeuroImage 152 (2017): 184-194.
13. Kell, Alexander JE, et al. "A task-optimized neural network replicates human auditory behavior, predicts brain responses, and reveals a cortical processing hierarchy." Neuron 98.3 (2018): 630-644.
14. Jain, Shailee, and Alexander Huth. "Incorporating context into language encoding models for fmri." Advances in neural information processing systems. 2018.
15. Xu, Haoyan, Brian Murphy, and Alona Fyshe. "Brainbench: A brain-image test suite for distributional semantic models." Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing. 2016.
16. Feather, Jenelle, et al. "Metamers of neural networks reveal divergence from human perceptual systems." Advances in Neural Information Processing Systems. 2019.
17. Schrimpf, Martin, et al. "Integrative benchmarking to advance neurally mechanistic models of human intelligence." Neuron (2020).
18. Schrimpf, Martin, et al. "Artificial Neural Networks Accurately Predict Language Processing in the Brain." BioRxiv (2020).
19. Hashemzadeh, Maryam, et al. "From Language to Language-ish: How Brain-Like is an LSTM's Representation of Nonsensical Language Stimuli?." arXiv preprint arXiv:2010.07435 (2020).
20. Bender, Emily M., and Alexander Koller. "Climbing towards NLU: On meaning, form, and understanding in the age of data." Proc. of ACL. 2020.
21. Martin, Andrea E., and Leonidas AA Doumas. "Tensors and compositionality in neural systems." Philosophical Transactions of the Royal Society B 375.1791 (2020): 20190306.
22. Fyshe, Alona, et al. "A compositional and interpretable semantic space." Proceedings of the 2015 conference of the north american chapter of the association for computational linguistics: Human language technologies. 2015.
