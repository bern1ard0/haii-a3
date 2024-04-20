# Data Directory

The data for Assignment 3 is included here. `dates.csv` is a subset of `dates_large.csv` where some columns were removed for simplicity's sake. The columns are all described in this document. The data files originate from [Columbia University](http://www.stat.columbia.edu/~gelman/arm/examples/speed.dating/), although they have been lightly processed for this assignment.

## The Data 
The data files contain 8,378 entries from heterosexual speed dating events at Columbia University from 2002-2004 in a comma separated values file format. In these events, each participant met each of all opposite-gender participants for four minutes. The number of speed dates dates varied by the event, on average there were 15, but it could be as few as 5 or as many as 22. Afterward, each participant was asked if they would like to meet any of their speed dating partners again. They also provided ratings on six **attributes** about each speed date:

- Attractiveness
- Sincerity
- Intelligence
- Fun
- Ambition
- Shared Interests

The dataset also includes varying participants' perspectives on those attributes, along with other demographic information and hobbies as described below. 

Each row of the dataset is a speed date, and since participants have multiple dates, they appear in the dataset multiple times. Each column is described below:

| Column Header       | Description     |
| :------------- |  ----------: | 
|  iid | Numerical ID unique to this person   |
| gender   | This participant's self-reported gender (f = female)|
| age | Age in years of this participant |
| ageQuartile | Age quartile for this person, categorized as youngest/young/old/oldest |
| race | This person's race |
| white | Y is this person is White, N otherwise |
| field | This person's field of study |
| discipline | A more general version of field of study |
| income | The median household income of the zipcode where this person grew up |
| incomeQuartile | Which quartile the person's 'income' falls under, categorized as lowest/low/high/highest |
| from | Where this person is originally from |
| fromRegion | A more general version of from |
| fromUSA | Y if they are from the USA, N otherwise |
| tot_rounds | The total number of speed dating rounds (i.e., num speed dates)
| round_num | Index of which speed date of the event (first, second , third...)|
| pid | The partner's unique numerical ID |
| age_partner | The partner's age |
| race_partner | The partner's race |
| same_race | Whether this participant and the partner are the same race (y = yes)|
| request | This participant would like to meet this partner in a follow-up date |
| request_partner | The partner would like to meet this partner in a follow-up date |
| match | Both participants would like a follow-up meeting |
| like | How much this person liked this partner |
| prob_yes | This person's self-reported probability the partner will say yes to a 2nd date |
| like_partner | How much the partner liked this person |
| prob_yes_partner | The partner's probability this person will say yes to a 2nd date |

The next 17 columns all relate to the six attribute ratings listed above: how the participant rated each partner, themself, and how the partner rated the participant:

| Attribute Header       | Description     |
| :------------- |  ----------: | 
| attractive | Rating of Attractiveness this person gave to their partner |
| sincere | Rating of Sincerity this person gave to their partner |
| intelligence | Rating of Intelligence this person gave to their partner |
| fun | Rating of Fun this person gave to their partner |
| ambitious | Rating of Ambition this person gave to their partner |
| shared_interests | Rating of Shared Interests this person gave to their partner |
| attractive_partner | Rating of Attractiveness the partner gave to this person |
| sincere_partner | Rating of Sincerity the partner gave to this person |
| intelligence_partner | Rating of Intelligence the partner gave to this person |
| fun_partner | Rating of Fun the partner gave to this person |
| ambitious_partner | Rating of Ambition the partner gave to this person |
| shared_interests_partner | Rating of Shared Interests the partner gave to this person |
| attractive_self | Rating of Attractiveness this person gave them self |
| sincere_self | Rating of Sincerity this person gave them self |
| intelligence_self | Rating of Intelligence this person gave them self |
| fun_self | Rating of Fun the partner this person gave them self |
| ambitious_self | Rating of Ambition this person gave them self |

The next 17 columns are the participant's answer to the question _"How **interest**ed are you in the following activities, on a scale of 1-10?"_: sports (Playing sports/ athletics), tvsports (Watching sports), excercise, dining (Dining out), museums (Museums/galleries), art, hiking (Hiking/camping), gaming, clubbing (Dancing/clubbing), reading, tv (Watching TV), theater, movies, concerts (Going to concerts), music, shopping, and yoga (yoga/meditation). The numerical answers to these questions are recorded in the last 17 columns with the column head appended with `_num`. The low, moderate, high categories were determined based on quartiles: less than quartile 1 = `low`, less than quartile 3 = `moderate`, otherwise `high`. Please note that half the responses should be recoded as moderate.

