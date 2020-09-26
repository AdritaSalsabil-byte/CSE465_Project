# CSE465_Project
<h2>Sec-3</h2>
<h2>Project Title</h2>
  <p>Machine Translation on Bengali text to English text.</p>
  
  <h4> Member1:Mysa Salsabil Chowdhury       ID: 1632233642 </h4>
 <h4>Member2:Bakhtiyar Habib                ID:1531038642</h4>
 
 
 <h2> Machine Translation</h2>
 <p>Machine Translation means both the input and output are sentences. In other words, these sentences are a sequence of words going in and out of a model. </p>
  <br>
   <h4>We used seq to seq RNN model for translating our text</h4>
   
   
   <br>
   <h2>Bahdanau Attention Mechanism </h2>
   <p> Attention mechanism was used to pay attention to specific words in the input sequence for each word in the output sequence. We used Bahdanau attention mechanism which learn to align and translate jointly.It is also known as Additive attention as it performs a linear combination of encoder states and the decoder states. It helps to pay attention to the most relevant information in the source sequence.</p>
   <br>
  <h4>We used Tensorflow’s SparseCategoricalCrossentropy to compute the loss.</h4>
   <br>
   <h2> Teacher Forcing Algorithm</h2>
   <p> We used teacher forcing to decide the next input to the decoder.
  <br>
  Teacher forcing is a method for quickly and efficiently training recurrent neural network models that use the ground truth from a prior time step.It is the technique where the target word is passed as the next input to the decoder. The final step is to calculate the gradients and apply it to the optimizer and backpropagate.</p>
  <br>
  <h4>We used various tools from Python libraries such as numpy and keras, and the tensorflow platform to manipulate the data to get better results
</h4>
  <br>
  <h4>we used keras Tokernizer to split our texts into words.</h4>
  <br>
  <h2> Reference</h2>
  <p>https://www.tensorflow.org/tutorials/text/nmt_with_attention</p>
  


