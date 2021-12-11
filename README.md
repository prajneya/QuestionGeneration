# QuestionGeneration

In the age of technology, it is natural to ingrain it with all possible fields, including education.  With theever  growing  amount  of  educational  content  it  is  becoming  more  and  more  difficult  to  generate  multiplequestions manually.  Hence, our project works on question generation based on educational content which will automatically generate questions based on text data as input

## Our Methodology

We aim to implement the following models:

* Baseline: LSTM + Attention + Linguistic Features Model
* Baseline+: The QG-Net Model (trained on GLoVe)


First part of our problem deals with basic Question Generation, and how well they can be generalised. We will explore how well you can generalise LSTM based encoder-decoder model trained on SQuAD dataset onto question generation based on Educational Data.\\
![lstm](https://user-images.githubusercontent.com/54315149/145692500-fb35b4c6-06d8-4824-9e28-dc21cfc157dc.png)\\

Second part of our project will be focussed on improving upon our baseline, both based on better word representations and better generalibility. We would use contextual word embeddings like BERT instead of basic ones like GloVE for the former, and for the latter we would try implementing QGNet, a SoTA generalizable model for question generation


![QGNET](https://user-images.githubusercontent.com/54315149/145692491-bfade8b4-8f5f-42d9-a135-6a82753d4bfe.png)
