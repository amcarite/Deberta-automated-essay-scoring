# Deberta-automated-essay-scoring

Although research has shown that pre-trained
BERT models improve automated essay scoring
(AES), most earlier studies assessed quality with
a single “holistic” score. However, multidimensional
scoring is more valuable to teachers
and students because it better pinpoints
opportunities for writing improvement. This
paper examines the relative effectiveness of
BERT-based models across six different rubric
dimensions using a new dataset from Vanderbilt
University and the Learning Agency Lab which
contains essays written by 8th-12th Grade
English Language Learners (ELLs). While we
expected fine-tuned BERT models to outperform
more traditional AES methods and surpass our
baselines, we also found that models which
predicted individual rubric traits collectively
(all-in-ones) outperformed collections of siloed
models that focused on one rubric trait each
(one-for-each). Additionally, we found that
DeBERTa models, with the help of the enhanced
masked decoder, further strengthen all-in-one
and one-for-each models.


### Links
The final paper can be found in pdf format [here](https://github.com/amcarite/Deberta-automated-essay-scoring/blob/main/All%20for%20One%20and%20One%20for%20Each.pdf)


All notebooks used to generate and run experiments are in [this directory](https://github.com/amcarite/Deberta-automated-essay-scoring/tree/main/notebooks)

The original dataset can be found [here](https://github.com/amcarite/Deberta-automated-essay-scoring/tree/main/notebooks)
