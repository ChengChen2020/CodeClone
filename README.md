### Code Clone Detection based on and Token Frequency and Multi-layer Perceptron

Software clone, means that software developers reuse existing codes by copy-and-paste, or implement functions very similar to existing ones. Code clone usually leads to software defects and infringement disputes. Therefore, it is necessary to design a system which can automatically detect whether two source code files are a clone pair. To achieve this goal, we have to employ a series of data mining algorithms. We first utilize a lexer to scan source codes and transfer code sequences into token sequences. Afterwards, we generate feature vectors for each source code using token frequency. Finally, by training on plenty of clone and non-clone pairs we build our MLP detection model, which can predict whether two source code files are a clone pair to some extent.



