##ETL-sample-process
ETL pipeline and recommendation system that collects course ratings and aggregates that data to recommend DataCamp courses to a user.
1- Extraction: Reads the files in Customer and Ratings table and joins them on the Foreign key, course_id
2- Transformation: Takes the average of the ratings
3- Loads them into a Postgresql database
4- Recommends the highest rated courses

#Case Study DataCamp Data

- Fetch data from multiple sources
- Transform to form recommendations
- load into target database



