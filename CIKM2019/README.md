# Data

Data is available to other researchers upon request. Please contact m2abuals@uwaterloo.ca for access.


### Format

The data is tab-seperated and includes the following:

 - **User**: the user id
 - **User type**: either *economic* or *exhaustive*. See paper for more details
 - **Task type**: 
	 - -1: Every item in the SERP is not relevant
	 - -2: Control task (the SERP is from the Bing API)
	 - -3: Subsequent Bing API queries
	 - \[1,..,10\]: Task where a single item is correct. The number indicates the rank of the correct item
-	**Action**: Either a click or an abandonment
-	**isRequery**: Boolean indicating whether the action from the user is an abandonment
-	**isAnswerFromSnippet**: Boolean indicating whether the user announced their answer after reading a snippet summary
-	**click_rank**: The rank of click, otherwise -1
-	**timelength**: Time to make action
-	**hit_[num]_total**: Total time spent fixating on an item
-	**total_fixations**: Total fixations for the task
-	**mean_fixation_length**: The mean fixation length
-	**query**: the submitted query
-	**question_type**: A tag indicating the question being asked. See paper for more details
-	**sequence**: The sequence of fixation and action
	-	Start(num): indicates where the correct answer is
	-	-> \[rank\](fixation duration):
	-	-> action

### Query types
The data is tab-seperated and includes the following:

- **query**: the submitted query
- **question_type**: A tag indicating the question being asked.
- **assessor1**: Assessor's one judgment (weak/strong). See paper for more details
- **assessor2**: Assessor's two judgment (weak/strong). See paper for more details

