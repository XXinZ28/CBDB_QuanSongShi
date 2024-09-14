# About the Project
This NLP research project aims to seek the best methodology to extract names from Quan Song Shi's poem titles, as one of the sub-project in China Biographical Database Project (CBDB) at Harvard University. This project is mainly conducted by me, with the guidance of Hongsu Wang and supervision of Professor Bol. 

# Methodology and Procedure
62 ground truths were set by hand as the entity reference for the first stage of the research. Next, 7 popular Name Entity Recognition (NER) models from Hugging Face were being evaluated in the Jupyter Notebook. The best model shows approximately 54% accuracy rate of extraction. Furthermore, experiments of using prompt engineering in Large Language Moodels (LLMs) were conducted to do the same task, using ChatGPT4o and Claude3.5 as examples. The initial experiment shows an accuracy rate of approximately 87%. The second experiment is still under the conduction.

# About Files
1) `QuanSongShi_training_data` contains all the data entries in Quan Song Shi for the use of training purpose. (Note this was done by me and mostly by other RAs).
1) Under the file `HuggingFace_Model_Evaluation`, all the files and materials of doing NER model evaluations can be retrieved.
3) Under the file of `LLMs_Experiments`, all the materials, files, and reports of conducting LLMs experiments can be found. 
