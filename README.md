# lip_reading_model

This model takes videos of people saying sentences, and attempts to lip-read them to output the correct label, which might be "lay three in five blue brown".

The model is built using a 3D CNN to process the salient video features, and then uses a bidirectional LSTM (long short term memory) network to predict the sequence of tokens. The loss used is CTC (Connectionist Temporal Classification)
which calculates the loss between a target sequence and a predicted sequence.
