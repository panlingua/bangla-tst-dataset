# Multilingual Text Style Transfer (MTST) Datasets 
## Introduction
<p align="justify">
We present a novel <a href="https://github.com/panlingua/multilingual-tst-datasets">Bangla, Hindi, Magahi, Malayalam, Marathi, Odia, Punjabi, Telugu, and Urdu dataset</a> that facilitates text sentiment transfer, a subtask of Text style transfer (TST), enabling the transformation of positive sentiment sentences to negative and vice versa. To establish a high-quality base for further research, we <a href="https://github.com/panlingua/multilingual-tst-datasets"> refined and corrected an existing English dataset</a> of 1,000 sentences for sentiment transfer based on <a href="https://github.com/lijuncen/
Sentiment-and-Style-Transfer">Yelp reviews</a>, and we introduce a new human-translated Bangla dataset that parallels its English counterpart. For further read, please refer <a href="https://aclanthology.org/2023.banglalp-1.5"> our papers </a>.</p>

# Structure of the MTST datasets:
```
📂 multilingual-tst-datasets/
    📂  bengali/
        ├── bn_yelp_reference-0.csv
        ├── bn_yelp_reference-1.csv
        └── ..
    📂  hindi/
        ├── hi_yelp_reference-0.csv
        ├── hi_yelp_reference-1.csv
        └── ..
    📂  magahi/
        ├── mag_yelp_reference-0.csv
        ├── mag_yelp_reference-1.csv
        └── ..
    📂  malayalam/
        ├── ml_yelp_reference-0.csv
        ├── ml_yelp_reference-1.csv
        └── ..
    📂  marathi/
        ├── mr_yelp_reference-0.csv
        ├── mr_yelp_reference-1.csv
        └── ..
    📂  odia/
        ├── or_yelp_reference-0.csv
        ├── or_yelp_reference-1.csv
        └── ..
    📂  punjabi/
        ├── pa_yelp_reference-0.csv
        ├── pa_yelp_reference-1.csv
        └── ..
    📂  refined-english/
        ├── en_yelp_reference-0.csv
        ├── en_yelp_reference-1.csv
        └── ..
    📂  telugu/
        ├── te_yelp_reference-0.csv
        ├── te_yelp_reference-1.csv
        └── ..
    📂  urdu/
        ├── ur_yelp_reference-0.csv
        ├── ur_yelp_reference-1.csv
        └── ..
    ├── LICENSE.md
    ├── README.md
```

# License
Please read the [License](https://github.com/panlingua/multilingual-tst-datasets/blob/main/LICENSE) file.

# Acknowldegments
<p align="justify">This research was supported by the <a href="https://erc.europa.eu/homepage">European Research Council</a> (Grant agreement No. 101039303 NG-NLG) and by <a href="https://cuni.cz/">Charles University </a> projects GAUK 392221 and SVV 260575. We acknowledge of the use of resources provided by the <a href="https://ufal.mff.cuni.cz/">LINDAT/CLARIAH-CZ Research Infrastructure</a> (Czech Ministry of Education, Youth, and Sports project No. LM2018101). We would also like to acknowledge <a href="panlingua.co.in"> Panlingua Language Processing LLP </a> for this collaborative research project and for providing the dataset.
  
Atul Kr. Ojha would like to acknowledge the support of the <a href="https://www.sfi.ie/"> Science Foundation Ireland (SFI)</a> as part of Grant Number SFI/12/RC/2289_P2 Insight_2, <a href="https://www.insight-centre.org/">Insight SFI Research Centre for Data Analytics</a>. </p>
# References
If you use this data, please cite:
```
  @inproceedings{mukherjee-etal-2023-low,
    title = "Low-Resource Text Style Transfer for {B}angla: Data {\&} Models",
    author = "Mukherjee, Sourabrata  and
      Bansal, Akanksha  and
      Majumdar, Pritha  and
      Ojha, Atul Kr.  and
      Du{\v{s}}ek, Ond{\v{r}}ej",
    editor = "Alam, Firoj  and
      Kar, Sudipta  and
      Chowdhury, Shammur Absar  and
      Sadeque, Farig  and
      Amin, Ruhul",
    booktitle = "Proceedings of the First Workshop on Bangla Language Processing (BLP-2023)",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.banglalp-1.5",
    doi = "10.18653/v1/2023.banglalp-1.5",
    pages = "34--47",
}
```
</pre>

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) =====================================================
Data available since: Multilingual Text Style Transfer (MTST) Datasets@2023
License: See the <i>LICENSE.md</i>
=======
Includes text: Yes
Contact:info@panlingua.co.in or atulkumar.ojha@insight-centre.org/shashwatup9k@gmail.com 
Contributor/&copy; holder: Panlingua Language Processing LLP, India; Institute of Formal and Applied Linguistics, Faculty of Mathematics and Physics Charles University, Czech Republic; and Insight Centre for Data Analytics, Data Science Institue, University of Galway, Ireland
=======================================================================================================
</pre>
