# StackOverFlow-Project

## Data Source
https://archive.org/download/stackexchange/stackoverflow.com-Badges.7z<br>
https://archive.org/download/stackexchange/stackoverflow.com-Posts.7z<br>
https://archive.org/download/stackexchange/stackoverflow.com-Users.7z<br>

## Schema and The Entity Relationship Diagram
https://meta.stackexchange.com/questions/2677/database-schema-documentation-for-the-public-data-dump-and-sede

## Questions 

What is the percentage of questions that have been answered over the years?

What is the reputation and badge count of users across different tenures on StackOverflow?

What are 10 of the “easier” gold badges to earn?

Which day of the week has most questions answered within an hour?

## Steps for Execution

1. Download the data into HDFS file system
```bash
  wget <link>
  7z e <file-name>
```
2. Move the data to HDFS
```bash
 hadoop fs -put <source-path> <hdfs-destination-path>
```

### Note

The Outputs shown are the result of processing Partial Data as the complete
