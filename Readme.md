# Cereal Letter

![Cereal Letter Logo](https://iili.io/HoICctS.md.jpg)

Cereal Letter is a daily newsletter featuring jokes, news, deep quotes, and music suggestions.

## Motivation

The motivation behind this project is to learn about ETL (Extract, Transform, Load) pipelines and gain experience with frameworks like Airflow and Argo.

## Stack

- Airflow
- MongoDB
- PostgreSQL
- Docker

## Working

![Airflow DAG](https://iili.io/HoIC0o7.md.jpg)

Cereal Letter utilizes Airflow to orchestrate the following tasks:
1. Fetching data from various open APIs.
2. Combining fetched data and storing it as JSON in MongoDB.
3. Generating a PDF using the stored data and sending it to users at scheduled times.

## PDFs

PDFs are stored in the `/temp` folder.

## Env

To enable email functionality, configure your [SendGrid](http://sendgrid.com) account:
- Add your email and API key in the `.env` file to ensure the email operator functions correctly.

## Future Scope

Future enhancements include:
- Allowing multiple users to subscribe, receiving newsletters customized based on their preferences.

