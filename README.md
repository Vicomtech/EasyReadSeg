# EasyReadSeg

EasyReadSeg is a corpus of Easy Read segmented text based on original content published in Irekia (https://www.irekia.euskadi.eus/), Inclusion Europe (https://www.inclusion-europe.eu/) and Plena Inclusión (https://www.plenainclusion.org). Its aim is to foster research on Easy Read text generation and covers three languages: Basque, English and Spanish.

For more details see the [**paper**](https://aclanthology.org/2024.findings-emnlp.694/).

**NOTE:** As of this writing, we have secured permission to publicly share only a subset of the data under the specified license, namely the Basque data subsets from Irekia. We have not yet been authorised to share the English and Spanish data from Inclusion Europe and Plena Inclusión, respectively. Contact us if you would like to use these datasets for your own private research.

The corpus was created during the development of project IRAZ (ZL-2024/00570), which received funding from the Department of Economic Development and Competitiveness of the Basque Government (Spri Group), within the Hazitek programme (2022-2024). 

## Format and usage

The data are provided as UTF-8 text files with one sentence per line. The original segmentation is indicated in the text with the inlined symbol *\_seg\_*.

EasyReadSeg can be requested from this [**REQUEST FORM**](TBD)


## Authors

The following researchers were involved in the EasyReadSeg dataset creation process:

 - Jesús Calleja Pérez
 - Thierry Etchegoyhen
 - David Ponce


## Contact

tetchegoyhen@vicomtech.org

## License

EasyReadSeg is distributed under the following license:

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

## Other relevant information

If you use this dataset in your work, please cite the following paper:

```
@inproceedings{calleja-etal-2024-automating,
    title = "Automating Easy Read Text Segmentation",
    author = "Calleja, Jes{\'u}s  and
      Etchegoyhen, Thierry  and
      Ponce, David",
    editor = "Al-Onaizan, Yaser  and
      Bansal, Mohit  and
      Chen, Yun-Nung",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2024",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.findings-emnlp.694/",
    doi = "10.18653/v1/2024.findings-emnlp.694",
    pages = "11876--11894",
    abstract = "Easy Read text is one of the main forms of access to information for people with reading difficulties. One of the key characteristics of this type of text is the requirement to split sentences into smaller grammatical segments, to facilitate reading. Automated segmentation methods could foster the creation of Easy Read content, but their viability has yet to be addressed. In this work, we study novel methods for the task, leveraging masked and generative language models, along with constituent parsing. We conduct comprehensive automatic and human evaluations in three languages, analysing the strengths and weaknesses of the proposed alternatives, under scarce resource limitations. Our results highlight the viability of automated Easy Read segmentation and remaining deficiencies compared to expert-driven human segmentation."
}
```

