# Backups

## Tasks
- [ ] Configure backups
    * [x] Development - Completed 11/05/2021
    * [ ] Production
- [ ] Copy backups to offsite location

## Detail
|Environment|Frequency|Retention|    Encrypted   |
|:----------|:-------:|:-------:|:-------------:|
|Development|Daily    |30 days  |:material-check:|
|Staging    |Never    |Never    |-|
|Production |Daily    |60 days  |:material-check:|

## Implementation
Follow this [guide](https://firebase.google.com/docs/firestore/solutions/schedule-export#gcp-console).
