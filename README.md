# POLI3115

This is a group project research proposal from POLI3115 Politics and public opinion, HKU. You can read the full version of the proposal [here](https://github.com/Yvonne27Jin/POLI3115/blob/main/Final%20Research%20Proposal.pdf).

## Data sources:

Original dataset：[Zhai, Yujia, 2020, "Weibo COVID dataset", https://doi.org/10.7910/DVN/DULFFJ, Harvard Dataverse, V1](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DULFFJ)

[Chinese emotional dataset](http://ir.dlut.edu.cn/info/1013/1142.htm) used for sentiment analysis, imported in code folder as [情感词汇本体.xlsx](https://github.com/Yvonne27Jin/POLI3115/blob/main/code/情感词汇本体.xlsx).



## Code

[1_datafile_stream_processing-jsonTocsv.ipynb](https://github.com/Yvonne27Jin/POLI3115/blob/main/code/1_datafile_stream_processing-jsonTocsv.ipynb): Convert .json datafile to pandas dataframe and store as .csv files.

[2.1_data_stream_processing-sampling.ipynb](https://github.com/Yvonne27Jin/POLI3115/blob/main/code/2.1_data_stream_processing-sampling.ipynb): Randomly sample 1% of the original sample for stage 1 explorative pilot analysis.

[2.2_sentiment_analysis_topic_modeling.Rmd](https://github.com/Yvonne27Jin/POLI3115/blob/main/code/2.2_sentiment_analysis_topic_modeling.Rmd): Text tokenisation, sentimentt analysis, topic modeling of the sampled data in R. Visualisation included.

[3.1_data_stream_processing-sub topic.ipynb](https://github.com/Yvonne27Jin/POLI3115/blob/main/code/3.1_data_stream_processing-subtopic.ipynb): Filter sub-datasets with key words from the original dataset.

[3.2_subtopic_sentiment_analysis.Rmd](https://github.com/Yvonne27Jin/POLI3115/blob/main/code/3.2_subtopic_sentiment_analysis.Rmd): An automated function conducting text processing and sentiment analysis for the sub-topic datasets. Results exported for visualisation in Tableau.



Sample data:

[word_freq.rds](https://github.com/Yvonne27Jin/POLI3115/blob/main/code/word_freq.rds): Cleaned word frequency by post and by date, from sampled data.



