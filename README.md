[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/) 

# <a href='https://link.springer.com/article/10.1007/s10579-018-9427-x'>ShEMO: a large-scale validated database for Persian speech emotion detection</a><br>

## Abstract
<div align="justify"> This paper introduces a large-scale, validated database for Persian called Sharif Emotional Speech Database (ShEMO). The database includes 3000 semi-natural utterances, equivalent to 3 hours and 25 minutes of speech data extracted from online radio plays. The ShEMO covers speech samples of 87 native-Persian speakers for five basic emotions including <i>anger</i>, <i>fear</i>, <i>happiness</i>, <i>sadness</i> and <i>surprise</i>, as well as neutral state. Twelve annotators label the underlying emotional state of utterances and majority voting is used to decide on the final labels. According to the kappa measure, 
the inter-annotator agreement is 64% which is interpreted as "substantial agreement". We also present benchmark results based on common classification methods in speech emotion detection task. According to the experiments, support vector machine achieves the best results for both gender-independent (58.2%) and gender-dependent models (female=59.4%, male=57.6%). The ShEMO is available for academic purposes free of charge to provide a baseline for further research on Persian emotional speech.

## ShEMO Database

<ul>
<li> Sharif Emotional Speech Database (ShEMO)</li> 

<li> Language: Persian</li>

<li> Duration: 3 hours and 25 minutes</li>

<li>Orthographic transcripts: Available</li>

<li>Phonetic transcripts: Available</li>
</ul>

Read our paper on <a href='https://link.springer.com/article/10.1007/s10579-018-9427-x'>Springer</a> or [arxiv](https://arxiv.org/pdf/1906.01155.pdf)

## Description of Labels
The characters used in the labels and their corresponding meaning:
- A : anger emotion
- F : female speaker (if used at the beginning of the label e.g. **F14A09**) or fear (if used in the middle of the label e.g. __M02F01__)
- H : happiness
- M : male speaker
- N : neutral
- S : sadness
- W : surprise

e.g. __F03S02__ means the speaker is __female (F)__, __speaker code is 03__, the underlying emotion of the utterance is __sadness (S)__,
and this is the __second utterance for this speaker in sad emotion__.

## Download Database
- [Link to female utterances](https://github.com/pariajm/sharif-emotional-speech-database/blob/master/female.zip?raw=true)
- [Link to male utterances](https://github.com/pariajm/sharif-emotional-speech-database/blob/master/male.zip?raw=true)
- [Link to transcripts](https://github.com/pariajm/sharif-emotional-speech-database/blob/master/transcript.zip?raw=true) 

## دادگان گفتار احساسی شریف (شمو) 
برای دریافت مقاله <a href='https://arxiv.org/pdf/1906.01155.pdf'>اینجا</a> کلیک کنید

## Citation
If you use this dataset, please cite the following paper:
~~~~
@Article{MohamadNezami2019,
author  = {Mohamad Nezami, Omid and Jamshid Lou, Paria and Karami, Mansoureh},
title = {ShEMO: a large-scale validated database for Persian speech emotion detection},
journal = {Language Resources and Evaluation},
year  = {2019},
volume  = {53},
number  = {1},
pages = {1--16},
issn  = {1574-0218},
doi = {10.1007/s10579-018-9427-x},
url = {https://doi.org/10.1007/s10579-018-9427-x}
}
~~~~

### Contact
Paria Jamshid Lou <paria.jamshid-lou@hdr.mq.edu.au>
