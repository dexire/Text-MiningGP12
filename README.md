# Text-MiningGP12

These are the files and data used for generation. 

Do note the order to run the files and some of their dependencies.
Depending on your current environment, there may be more packages required.

Dependencies
- seaborn
- sentencepiece
- textacy
- en_core_web_lg
- en_core_web_md
- openai (and an api key for the code to work)

<h1>Sequence</h1>
EDA<br>
T5_00_EDA_LO.ipynb (used for EDA of WebNLG Triplet Format) <br>

For Text Preprocessing <br>
covar_00_bbcBatch_LO.ipynb (used to batch preprocess documents, replace text with covariance resolution) <br>
triplets_01_clean_LO.ipynb (triple generation, greedy) <br>
triplets_02_tripleFormatting_LO.ipynb (triple generation, strict) <br>
<br>
For LLM Fine Tuning <br>
All these are Kaggle notebooks <br>
GPT_00_fineTuning.ipynb <br>
T5_01_train8epoch.ipynb <br>
T5_01_train16epoch.ipynb <br>
<br>
For Text Generation <br>
All export to a folder called “results” <br>
GPT_01_textGenDistil_LO.ipynb <br>
GPT_01_textGenDistilFiltered_LO.ipynb <br>
GPT_01_textGenGPT2med_LO.ipynb <br>
ChatGPT_01_promptedTextGen.ipynb <br>
T5_02_textGen8epoch.ipynb <br>
T5_02_textGen16Epoch_LO.ipynb <br>
<br>
For Evaluation <br>
scoring_BatchSimplicityIndex_LO.ipynb <br>
util_simplicityIndex.py (this is imported into other notebooks)  <br>
