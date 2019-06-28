# How to access S3 Bucket using Athena - Demo ?

Amazon Athena is a service that enables a data analyst to perform interactive SQL queries in the Amazon Simple Storage Service (S3).

Athena is a serverless query service, an analyst doesn't need to manage any underlying compute infrastructure to use it.

It is not a Database service hence, you just pay for the queries you run. 

Easy Implementation: Athena doesn’t require installation. It can be accessed directly from the AWS Console also directly by AWS CLI.

Serverless: It is serverless, so the end-user doesn’t need to worry about infrastructure, configuration, scaling or failure. Athena takes care of everything on its own.

Pay per query: Athena charges you only for the query you run, i.e. the amount of data that is managed per query. You can save a lot if you can compress them and format your dataset accordingly.

Fast: Athena is a very fast analytics tool. It can perform complex queries in less time by breaking the complex queries into simpler ones and run them parallelly, then combine the results to give the desired output.

Secure: With the help of IAM policies and AWS Identity, Athena gives you complete control over the data set. As the data is stored in S3 buckets, IAM policies can help you manage control to users.

Highly available: With the assurance of AWS, Athena is highly available and the user can execute queries round the clock. As AWS is 99.999% available, so is Athena.

