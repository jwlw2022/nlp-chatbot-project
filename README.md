# nlp-chatbot-project

A lot of NLP research features dialogue systems and chatbots that can synthesize two-way conversations.
We took these conversations a step further to include three participants.
We trained a Seq2Seq model on the PERSONA-CHAT dataset and adapted it to train our chatbot for three-way conversations.
We improved our Seq2Seq model performance by adding attention and adjusting the embedding size and number of layers.
To evaluate the model's performance, we used perplexity as a quantitative measure and crowd-sourced ratings on qualitative metrics including engagingness, consistency, rationality, and creativity.
We discovered that validation perplexity decreases as embedding size increases, but an embedding size of 512 produced the most interesting, sensible, and original responses.
Increasing the number of hidden layers in the gated recurrent units (GRUs) in the encoder and decoder improved the performance of our chatbots.

We have separate Google Colab files for the non-attention (6864_NLP_Chatbot_Seq2Seq_Without_Attention.ipynb) and attention (Bastings_Attention_handout_sp21_6864_hw3_seq2seq.ipynb) chatbot models.
