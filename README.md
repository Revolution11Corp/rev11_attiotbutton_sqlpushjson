# rev11_attiotbutton_sqlpushjson
A Lambda Function to write the JSON payload from an IOT button message to a external SQL database column.  This function requires an SQL Hosted database with the following Parameters:

PLATFORM - The SQL platform were the database is hosted, can be one of the following: 'mssql', 'mysql', 'pg', 'oracle', 'sqlite' or 'websql'

HOST - The URL of the server where the database is hosted.

PORT - The port to access the above server with.

NAME - Name of the SQL database where the button JSON will be saved.

TABLE - Name of the table where the button JSON will be saved.

COLUMN - Name of the column where the button JSON will be saved.

USER - Username of an account that has INSERT priveleges to the SQL database.

PASSWORD - The password for the USER above.

Made with ❤️ by Revolution11. Available on the [AWS Serverless Application Repository](https://aws.amazon.com/serverless)