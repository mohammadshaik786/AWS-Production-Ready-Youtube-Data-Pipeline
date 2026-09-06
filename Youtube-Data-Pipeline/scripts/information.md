Bronze Bucket Name - yt-data-pipeline-bronze-us-east-2-dev
Silver Bucket Name - yt-data-pipeline-silver-us-east-2-dev
Gold Bucket Name - yt-data-pipeline-gold-us-east-2-dev

Script Bucket - yt-data-pipeline-script-us-east-2-dev 

sns - arn:aws:sns:us-east-2:061616980374:yt-data-pipeline-alerts-dev

Glue Bronze - yt_pipeline_bronze_dev
Glue Silver - yt_pipeline_silver_dev
Glue Gold - yt_pipeline_gold_dev

--bronze_database yt_pipeline_bronze_dev 
--bronze_table raw_statistics 
--silver_bucket yt-data-pipeline-silver-us-east-2-dev --silver_database yt_pipeline_silver_dev 
--silver_table clean_statistics

--silver_database yt_pipeline_silver_dev 
--gold_bucket yt-data-pipeline-gold-us-east-2-dev --gold_database yt_pipeline_gold_dev

