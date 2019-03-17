# neural-machine-translation
Neural Machine Translation with Attention
# Intro
# Neural Machine Translation

Welcome to your first programming assignment for this week! 

I have built a Neural Machine Translation (NMT) model to translate human readable dates ("25th of June, 2009") into machine readable dates ("2009-06-25"). You will do this using an attention model, one of the most sophisticated sequence to sequence models. 

- The model I built here could be used to translate from one language to another, such as translating from English to Hindi. However, language translation requires massive datasets and usually takes days of training on GPUs. To experiment with these models even without using massive datasets, I instead used a simpler "date translation" task.

#Conclusions
- Machine translation models can be used to map from one sequence to another. They are useful not just for translating human languages (like French->English) but also for tasks like date format translation.
- An attention mechanism allows a network to focus on the most relevant parts of the input when producing a specific part of the output.
- A network using an attention mechanism can translate from inputs of length  TxTx  to outputs of length  TyTy , where  TxTx  and  TyTy  can be different.
- You can visualize attention weights  α⟨t,t′⟩α⟨t,t′⟩  to see what the network is paying attention to while generating each output.
