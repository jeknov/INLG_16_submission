# INLG_16_submission

This repository contains the dataset released with the submission of INLG 2016 paper "Crowd-sourcing NLG Data: Pictures Elicit Better Data" (https://aclweb.org/anthology/W/W16/W16-6644.pdf).

## File descriptions:

* INLG2016_dataset.csv - the dataset with textual meaning representations
* images.zip - images used as pictorial meaning representations 

## Data fields:

*mr* - textual meaning representation

*nl.utterance* - natural language utterance

*informativeness* - human rating of informativeness, collected on 1-6 Likert scale (crowd evaluation)

*naturalness* - human rating of naturalness, collected on 1-6 Likert scale (crowd evaluation)

*phrasing*- human rating of phrasing, collected on 1-6 Likert scale (crowd evaluation)

*attr.count* - number of attributes in a corresponding MR

*batch* - pic: pictorial MR presented to crowd workers, txt: textual MR presented to crowd workers

*mr.id* - id number of MR (used as the name of image for pictorial MR)

*min.length* - minimal length metric, used for automatic pre-validation (see the paper)

*utterance.length* - length of the utterance, in characters

*no.Of.Sentences* - number of sentences in the utterance

*len.Ratio* - utterance.length/min.length

*coll.channel* - the work channel that the crowd worker accessed the job through

*coll.country* - the country the crowd worker is from

*coll.region* - a region code for the area the crowd worker is from

*col.city* - the city the crowd worker is from

*col.inform* - self-evaluation on informativeness

*col.natur* - self-evaluation on naturalness

*col.phrasing* - self-evaluation on phrasing

*eval.inform* - crowd-evaluation on informativeness

*eval.natur* - crowd-evaluation on naturalness

*eval.phrasing* - crowd-evaluation on phrasing

*sem.coverage* -  semantic similarity score (see the paper)

*norm.sem.coverage* - normalised semantic similarity score

*coll.task.duration* - average duration of the task, sec

## Citing the dataset:

If you use or refer to the dataset, please cite [this paper](https://aclweb.org/anthology/W/W16/W16-6644.pdf):

Jekaterina Novikova, Oliver Lemon, Verena Rieser (2016). Crowd-Sourcing NLG Data: Pictures Elicit Better Data, in *Proceedings of the 9th International Natural Language Generation Conference INLG'16*. Edinburgh, UK