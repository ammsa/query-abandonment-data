# Data

Data is available to other researchers upon request. Please contact m2abuals@uwaterloo.ca for access.


### Format

The data is comma-seperated and includes the following:

 - **task_type**: Either Bing, A, C, or E. See paper for more details
 - **user**: the user id
 - **isEffectQuery**: indicates whether the SERP for the query is manipulated
 - **query**: The query submitted
 - **query_number_of_terms**: The number of 
 - **qid**: the query id
-	**action**: Either a click or an abandonment
-	**first_action_time**: Time to first action
-	**click_more_count**: The number of times a user clicked on the request more results button
-	**time_to_click_more_1**: Time to click the button for the 1st time
-	**time_to_click_more_2**: Time to click the button for the 2nd time
-	**time_to_click_more_3**: Time to click the button for the 3rd time
-	**time_to_click_more_4**: Time to click the button for the 4th time
-	**time_to_click_more_5**: Time to click the button for the 5th time
-	**clickURL**: the url of the document clicked
-	**doc_clicks**: number of documents clicked in this SERP
-	**unique_doc_clicks**: number of unique documents clicked in this SERP
-	**next_query**: The next query issued
-	**next_query_id**: the id of the next query


## Citation

If you use the data in any way, please cite:

```
@inproceedings{10.1145/3498366.3505770,
author = {Abualsaud, Mustafa and Smucker, Mark},
title = {The Dark Side of Relevance: The Effect of Non-Relevant Results on Search Behavior},
year = {2022},
isbn = {9781450391863},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3498366.3505770},
doi = {10.1145/3498366.3505770},
pages = {1–11},
numpages = {11},
keywords = {user behavior, user study, Non-relevant documents},
location = {Regensburg, Germany},
series = {CHIIR '22}
}
```
