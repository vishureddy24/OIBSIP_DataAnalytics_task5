# OIBSIP_DataAnalytics_task5

# Autocomplete and Autocorrect System 

# Objective 

To develop simple Natural Language Processing (NLP) tools for text input assistance : spelling correction and word completion.

# key Steps

-- Loaded a dataset of misspelled and correct words 

-- Implemented Levenshtein Distance for autocorrection.

-- Built dictionary-based autocomplete logic

-- Comapred accuracy and performance of different models  like simple autocorrect and Norvig-style autocorrect 

# Tools and Libreries 

-- Regular Expressions (re)

-- collections.counter and defaultdict 

# outcome 

Dictionary-based :



| Typo     | Predicted | Actual  | Feedback   |
|----------|-----------|---------|------------|
| sloger   | slogger   | slogger | satisfied  |
| liina    | lina      | lina    | satisfied  |
| curaate  | curate    | curate  | satisfied  |





Probabilistic-Based :


| Typo   | Predicted | Actual   | Feedback       |
|--------|-----------|----------|----------------|
| liina  | liina     | lina     | not satisfied  |
| sloger | sloger    | slogger  | not satisfied  |



