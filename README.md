# WSMF-presentation

This repository contains the code, some of the data, and the presentation for the III Studencko-Doktorancka Konferencja "Wrocławskie Spotkania Młodych Filologów" conference.

## MA thesis project
The MA thesis project that this presentation is a part of can be found [here](https://github.com/Turtilla/swe-ma-thesis)

## REPOSITORY STRUCTURE
* `code`: contains all the code for the project.
  * `stanza-lemmarizer-and-tagger-evaluation.ipynb`: the code and output for obtaining annotation and measures from Stanza.
  * `error-statistics.ipynb`: the code and output for calculating statistics of annotated errors.
* `data`: contains most of the data used in the project.
  * `memoirs_10k_corrected.conllu`: annotated data in a CoNLL-U format, annotation reliable for UPOS tags.
  * `memoirs_3k_corrected.conllu`: annotated data in a CoNLL-U format, annotation reliable for lemmatization, UPOS, and XPOS tags.
  * `mistakes`: contains output and annotated output.
    * `*.xlsx`: all of the erroneous Stanza annotations per type of annotation.
    * `annotated`: contains annotated errors.
      * `*.xlsx`: all of the annotated erroneous stanza annotations per type of annotation.
  * `results`: contains all of the output from Stanza.
    * `*.xlsx`: All of the Stanza output per type of annotation.
 *  `presentation`: contains the files for the presentation.
  * `WSMF_presentation.pdf`: a PDF version of the presentation.
  * `WSMF_presentation.pptx`: a PowerPoint version of the presentation. 
