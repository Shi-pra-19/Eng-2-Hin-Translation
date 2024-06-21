Machine translation is the task of automatically converting source text in one language to text in another language. Neural machine translation, or NMT for short, is the use of neural network models to learn a statistical model for machine translation.

NMT generally uses an Encoder-Decoder RNN structure. To increase the performance, Decoders also use something known as Attention mechanism which enables them to learn to focus on certain portions of the input sentence in order to predict the correct output word in the sequence.

The NMT Model implemented by me uses an Encoder + Attention-based Decoder to try and translate English sentences to Hindi.
