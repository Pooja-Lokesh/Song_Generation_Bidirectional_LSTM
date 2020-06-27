# Text Generation

## Text generation using bidirectional LSTMs on a datset of 250 songs. 

- Bidirectional LSTMs are formed by putting two independent LSTMs together. 
- This structure allows the networks to have both backward and forward information about the sequence at every time step.
- Using bidirectional LSTMs will run the inputs in two ways, one from past to future and one from future to past.
- In this way, it is able to preserve information from both past and future in any point in time.
- This helps the network to understand the context better, and generate better sequences of text. 
