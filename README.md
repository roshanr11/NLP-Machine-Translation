# Machine Translation with Natural Language Processing

Built a deep neural network that functions as part of an end-to-end machine translation pipeline, using Keras. The pipeline accepts English text as input and return the French translation.

---

## Main Steps:
<ol>
<li>Preprocess - Convert text to sequence of integers</li>
<li>Models - Create models which accept a sequence of integers as input and returns a probability distribution over possible translations. Experimented with different model types and techniques. 
<li>Prediction Run the model on English text.</li>
</ol>

---

### High-Level Overview of Models Implemented:
- Model 1 is a simple RNN
- Model 2 is a RNN with Embedding
- Model 3 is a Bidirectional RNN
- Model 4 is an optional Encoder-Decoder RNN

