# Data

### Format (firstAction.csv)

 - **user**: The user id
 - **task**: The task id
 - **action**: The action user made (click or immediate requery)
 - **time**: Time to action
 - **click_rank**: If click, the click rank
 - **num_nonrel_top**: The number of non-relevant documents before the correct item
 - **irequery**: 1 if user has abandon the query (immediate requery), else 0


### Format (time_to_requery.csv)

The data is comma-separated and includes the following:

 - **task_num**: The task number
 - **user**: the user id
 - **effectQuery**: indicates whether the SERP for the query is manipulated
 - **goodRank**: The rank of the correct item. -1 is for NoCorrect tasks, and -2 is for Bing.
 - **time_to_requery**: The time to abandonment
 - **time_to_first_keystroke**: The time to the first keystroke before submitting the query
 - **user_type**: Either high/low. See paper for more details



## Citation

If you use the data in any way, please cite:

```
@inproceedings{10.1145/3176349.3176400,
author = {Zhang, Haotian and Abualsaud, Mustafa and Smucker, Mark D.},
title = {A Study of Immediate Requery Behavior in Search},
year = {2018},
isbn = {9781450349253},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3176349.3176400},
doi = {10.1145/3176349.3176400},
booktitle = {Proceedings of the 2018 Conference on Human Information Interaction & Retrieval},
pages = {181–190},
numpages = {10},
keywords = {query abandonment, user study, immediate requery},
location = {New Brunswick, NJ, USA},
series = {CHIIR '18}
}
```
