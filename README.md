# MetaNews : A ‘do it all’ dataset of contemporary Metaphors in News headlines

## Metanews Dataset (ACL 2023)

* Metanews_git consists of the raw data. The candidates column consists of the top 200 candidates, literal_cands and metaphorical_cands consists of silver label candidates identified by the metaphor detection model, meaning_preserved_cands consists of the indentified gold label candidates -> if the sentence and verb are literal the candidates under this column would transform the sentence to metaphorical and vice versa.

* custom_test_sets directory holds test set 1 and test set 2 as mentioned in the paper.

* train_val_test_gold_plus directory consists of the standard splits. There is no overlap between the test set and other sets. Gold plus samples are indentified by the sample_type column.

