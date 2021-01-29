# ThesisPublic

I plan to upload research that follows from my thesis.


Presentation note: I created the defense presentation with LibreOffice Impress and LaTeX. Some LaTeX images are blurry in Google Slides and perhaps software other than Impress.

# Abstract
This thesis gives a novel algorithm $\mathcal{N}$ that helps users understand neural networks (NNs) via abstraction to and-inverter graphs (AIGs). I find that AIGs are more comprehensible than NNs due to their conciseness. For small NNs, $\mathcal{N}$ consistently creates AIG abstractions with perfect accuracy. However, translating large NNs to AIGs introduces the memorization versus generalization problem. Memorization elicits noise and reduces the comprehensibility of the AIG. To improve generalization and comprehensibility, I consider only the most important weights (using a maximum depth for the binary decision tree $\mathcal{B}$). Furthermore, I survey the accuracy of the ensemble method for further noise mitigation. This work successfully creates a single AIG that is a concise, generalized, and accurate NN abstraction. However, the AIGs are not always as comprehensible as one would like. Future work can further investigate noise reduction techniques such as the ensemble method.
