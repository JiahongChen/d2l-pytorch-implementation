# L19 Recurrent Neural Networks

As I am not able call the ```load_data_time_machine()``` in ```d2l``` package, I tried to rewrite the data preprocessing API that loads ```timemachine.txt``` according their source code. However, it took me a long time but in the end I failed to fix the bug regarding ```SeqDataLoader``` class. So, I'll skipping the training language models used in the textbook. Instead, I will try to implement RNN/GRU/LSTM using built-in PyTorch models.
