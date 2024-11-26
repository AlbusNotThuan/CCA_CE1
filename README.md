# CCA_CE1

## Task allocation

| Task                 | Person           |
| -------------------- | ---------------- |
| Data cleaning        | daden            |
| Define Variable Sets | daden            |
| Perform CCA          | daden & duydink  |
| Significance Testing | duydink & mandat |
| Interpret Loadings   | duydink & mandat |
| Visualizations       | dyngx            |
| Report               | dyngx            |

## Documentation

### Data cleaning

The responses from the survey contains a lot of unnecessary strings - it is in human language and cannot be clean in bulks using python. Clean data case-by-case using excel. Remove any unnecessary columns and rows and human language. Add missing data or wrong data by mean of other inputs. Make sure that the data is in a tidy format.

### Labelings:

| Question                                                                                      | Labeling           | Unit   |
| --------------------------------------------------------------------------------------------- | ------------------ | ------ |
| How many hours do you spend studying each week?                                               | study_hrs          | hours  |
| How many hours do you spend on group study or collaborative projects per week?                | study_hrs_group    | hours  |
| Rate your academic stress levels on a regular basis (not including exams)                     | study_stress       | points |
| How would you feel about your academic workload per week?                                     | study_workload     | points |
| How effective do you feel your studies during lectures are?                                   | study_eff_lect     | points |
| How effective do you think your self-study or study sessions outside of class are?            | study_eff_self     | points |
| How satisfied are you regarding your academic performance?                                    | study_satis        | points |
| How many hours do you dedicate to leisure or hobbies each week?                               | leisure_hrs        | hours  |
| How many hours of sleep do you typically get each night?                                      | leisure_sleep_hrs  | hours  |
| How many hours per week do you spend on physical activities such as sport?                    | leisure_sport_hrs  | hours  |
| How much quality time do you spend together with your family and friends per week (in hours)? | leisure_social_hrs | hours  |
| How satisfied are you regarding your leisure?                                                 | leisure_satis      | points |
