# tesi-data-science

This notebook aims to perform the Entity Resolution task.

The user should specify some variables (explained by the comments) that are necessary to run the script.

Sample datasets are provided.

In particular, the following variables need to be set:
* **brands_path**: path to the list of brands
* **sites_path**: path to the list of eCommerce sites
* **dataset_path**: path to the dataset containing s the offer comparisons that need to be evaluate
* **product_recognition_training_set**: training dataset for the SVM classifier used to extract notable trigrams for each offer
* **deepMatcher_model_path**: path to the trained deepMatcher model
* **n_sample**: sample size (of the main dataset) to evaluate
* **threshold**: matching threshold (score > thresholt ==> the two offers refer to the same product)

Run all the cells to execute the process.
