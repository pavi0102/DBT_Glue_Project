Welcome to your new dbt project!

Project Overview
1. In this project, we are utilizing AWS Glue to extract data from an external API and store it in JSON format within an S3 bucket. 
2. After the data has been loaded into the S3 bucket, we will employ dbt (Data Build Tool) to transfer the data from the S3 bucket into a staging table in Snowflake, using dbt macros for automation. 
3. Additionally, we are taking advantage of dbt's modeling capabilities to create the necessary tables in Snowflake across different layers: raw, transform, and mart.

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [dbt community](https://getdbt.com/community) to learn from other analytics engineers
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
