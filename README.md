## Current Work
I am currently working on three projects that directly follow from this thesis: 
1) weight sensitivity
2) real-valued inputs
3) multinomial classifications

I have also transitioned the explainable model from AIGs to OBDDs (Ordered Binary Decision Diagrams). Furthermore, I am recreating Chan and Darwhiche's algorithm in "Reasoning about Bayesian Network Classifiers" to improve the asymptotic run time from O(2<sup>n</sup>) to O(2<sup>0.5n</sup>n) where n is the number of in-weights for a given neural node.

## Thesis: Comprehending Neural Networks via Translation to And-Inverter Graphs

Presentation note: I created the defense presentation with LibreOffice Impress and LaTeX. Some LaTeX images are blurry in Google Slides and perhaps software other than Impress.

### Abstract
This thesis gives a novel algorithm N that helps users understand neural networks (NNs) via abstraction to and-inverter graphs (AIGs). I find that AIGs are more comprehensible than NNs due to their conciseness. For small NNs, N consistently creates AIG abstractions with perfect accuracy. However, translating large NNs to AIGs introduces the memorization versus generalization problem. Memorization elicits noise and reduces the comprehensibility of the AIG. To improve generalization and comprehensibility, I consider only the most important weights (using a maximum depth for the binary decision tree B. Furthermore, I survey the accuracy of the ensemble method for further noise mitigation. This work successfully creates a single AIG that is a concise, generalized, and accurate NN abstraction. However, the AIGs are not always as comprehensible as one would like. Future work can further investigate noise reduction techniques such as the ensemble method.

## Reducing the Neural Network Traversal Space for Boolean Abstractions
### Abstract
A reverse traversal (N) of the neural network is contrasted with a forward traversal (F). The Neural Constantness Heuristic, Neural Constant Propagation, shared logic, and negligible neural nodes are considered to reduce a neural layer's input space and reduce the amount of neural nodes approximated.

## Survey: Logic, Automata, and Game Theory

### Abstract
This paper surveys the relations among formal systems, decidability, finite automata, and game theory. An emphasis is placed on monadic second-order logic which Büchi used to create ω-regular automata. Extending Büchi’s work, Rabin found that the monadic second-order theory of the infinite complete binary tree was also decidable. Part of Rabin’s proof showed that ω-tree automata could be equally expressive to ω-regular automata. Complementing Rabin’s paper, a summary of Gurevich and Harrington’s game-theoretic proof for ω-tree automata’s closure under complementation is summarized.
