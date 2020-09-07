## GitHub Label Study Research Data


### Files for Project Information

Basic project information obtained from GitHub API.  
**Header**: ProjectID,Name,URL,TotalIssues,Issues,PullReqs,Labels,Forks,Stars,Subscribers,Watchers,CreatedAt,UpdateAt,URL
- project_info.csv

Number of Total and Closed issues for label groups.  
**Header**: ProjectID,TotalIssues,Closed,NoLabelTotal,NoLabelClosed,SingleLabelTotal,SingleLabelClosed,MultiLabelTotal,MultiLabelClosed
- project_issue_close_stat.csv

### Files for Label Analysis Results

Label analysis results of [VS Code](https://github.com/microsoft/vscode) and [Dart-lang](https://github.com/dart-lang/sdk).  
In header, tag1 and tag2 indicate main and sub categories respectively.  
**Header**: tag1, tag2, label, description, color, #open issues, #closed issues, #total issues
- tagging-vs-code.csv
- tagging-dart-lang.csv

### Files for Label Category Information
*_full contains a full list, *_multi_only contains multiple labels only.  

Number of labels and label status for each label category.  
**Header**: Categories, #Labels, #LabelStates
- label_category_stat_full.csv
- label_category_stat_multi_only.csv

List of labels and their categories.  
Categories are sorted in alphabetical order (not in label order) for aggregation.  
**Header**: id, label, categories
- label_state_categories_full.csv
- label_state_categories_multi_only.csv

Manual label categorization results.  
**Header**: ID, Label, Category
- single_label_category.csv
