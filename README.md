# ai-content-moderator

Author: Chris Gian
Project Description: 
- Build an API that will determine whether content is appropriate where appropriate is defined as whether it violates a terms of service agreement you would see a typical social media company have. 

## Motivation / Value Proposition

### Sample Terms of Service

[Spotify® Support Community Terms!](https://www.spotify.com/us/legal/support-community-end-user-agreement/)
[Spotify® Support Community Guidelines !](https://community.spotify.com/t5/FAQs/Spotify-Support-Community-Guidelines/ta-p/4575166/redirect_from_archived_page/true)
```
8. Always use an appropriate and respectful language when you post information in the Community. Avoid racist, sexist, abusive, harassing, defamatory, pornographic, threatening, obscene, condescending or otherwise offensive language that could be considered detrimental to other users, or Spotify employees or moderators.

9. Do not post information or create threads for the promotion or advertisement of commercial products or services.
```

From the above, types of content that violate the following will be removed unilaterally: 
- racist, sexist, abusive, harassing, defamatory, pornographic, threatening, obscene, condescending, offensive

From this list, I will target the most discrete of these categories:
- Racism, sexism, threatening

## Datasets:

Given above objectives the following data sources will be used:
- General Resource:
    - [Catalog of Hate Speech Datasets](https://hatespeechdata.com/)
- Sexism: 
    - [Automatic Misogyny Identification](https://amiibereval2018.wordpress.com/important-dates/data/)
        - notes: need to get password from that team.
- Online Bullying: 
    - [Bullying](http://ub-web.de/research/)
- Fox News Hate Speech:
    - [Detecting Online Hate Speech Using Context Aware Models]()

## Evaluation:
- Internal Validity: Can the model moderate content within the confines of this experiment (train-test split / K-Folds)?
- External Validity: Can the model moderate content outside of the experiment (real-world data)?
- Measures: `TBD`

## Project Details
- `TBD`

## TODO
- identify quality datasets (one, two, three)
- create method to extract csv of ids and labels and pass through twitter api




