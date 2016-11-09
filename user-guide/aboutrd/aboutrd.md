# About Redash

## <a name="whats_redash"></a>What's Redash?

Redash is an open source tool for teams to query, visualize and collaborate. Redash is quick to setup and works with any data source you might need so you can query from anywhere in no time.

Share your results and dashboards with other team members and empower your entire organization to be data driven with no-code filters and parameters that instantly adjust. Get alerts for pre-defined triggers to your email, Slack or Hipchat (you can setup a custom webhook as well).

Redash is our take on freeing the data within our company in a way that will better fit our culture and usage patterns. We tried to use traditional BI suites and discovered a set of bloated, technically challenged and slow tools/flows. What we were looking for was a more hacker’ish way to look at data, so we built one.

Redash was built to allow fast and easy access to billions of records, that we process and collect using Amazon Redshift (“petabyte scale data warehouse” that “speaks” PostgreSQL). Today Redash has support for querying multiple databases, including: Redshift, Google BigQuery,Google Spreadsheets, PostgreSQL, MySQL, Graphite and custom scripts.

## <a name="main_features"></a>Main Features

1. Query editor - enjoy all the latest standards like auto-complete and snippets. Share both your results and queries to support an open and data driven approach within the organization.
2. Visualization - once you have your dataset, select one of our /9 types of visualizations/ for your query. You can also export or embed it anywhere.
3. Dashboard - combine several visualizations into a topic targeted dashboard.
4. Alerts - get notified via email, Slack, Hipchat or a webhook when your query's results need attention.

## <a name="supported_data_sources"></a>Supported Data Sources

Redash plays nice with all data sources!

- Amazon Redshift
- BigQuery
- PostgreSQL
- MySQL
- TreasureData
- Microsoft SQL Server
- MongoDB
- ElasticSearch
- Hive
- Google Spreadsheets
- Impala
- InfluxDB
- Presto
- ScyllaDB
- Cassandra
- Amazon DynamoDB
- Python
- Vertica
- Graphite
- Stitch

Also, we added an option to query other query results - this way you can enjoy a dataset from multiple data sources (originally). Read more about [using datasets as data sources](../queries/using-datasets-as-data-sources.md)

## <a name="supported_browsers"></a> What Browsers Redash Works Best on?

We recommend using Chrome or Firefox.

If you encounter any issues that are browser specific, please let us know.

## <a name="privacy-security"></a> Privacy and Security

We're hosted on AWS and follow best practices:
1. All our servers are in a private network and are not accessible from the Internet, except for the load balancer and a bastion server for SSH (that does not have any credentials on it).
2. HTTPS/SSL for everything.
3. 2FA for our internal systems.

If you have any specific concerns, please contact us and we'll be happy to help.