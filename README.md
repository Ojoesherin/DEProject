[README - md.md](https://github.com/Ojoesherin/DEProject/files/14763262/README.-.md.md)
# Data Pipeline for Sales Data Transformation and Analysis

This Python script implements a data pipeline to transform and analyze sales data, integrating information from JSONPlaceholder API and OpenWeatherMap API. The pipeline fetches user data from the JSONPlaceholder API, extracts relevant fields, and merges it with the sales data based on customer IDs. Additionally, it retrieves weather data for each sale location using fictional store addresses from the OpenWeatherMap API. The transformed data is stored in a relational database, and various aggregations and data manipulations are performed to derive valuable insights, such as total sales amount per customer, average order quantity per product, top-selling products or customers, sales trends over time, and analysis of sales amount per weather condition. The provided documentation includes setup instructions, data transformation steps, database schema description, suggested aggregations, and assumptions made during the development of the data pipeline.


##  API used in this project

#### JSONPlaceholder API - /users

``` https://jsonplaceholder.typicode.com/users
  GET /api/ users
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | requests.get(endpoint_users)

####  api.openweathermap.org 

```https://api.openweathermap.org/data/2.5/weather
  GET /api/city weathher data
```

| Parameter  | Description |
| :-------- | :------- | 
| api_key   | '2b598bb41ffba33da5ed132144c33448'

#### add(num1, num2)

Takes two numbers and returns the sum.


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Demo

https://gifer.com/en/UqE6#google_vignette


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

` API key `2b598bb41ffba33da5ed132144c33448'




## Installation

git clone https://github.com/your-joesherin/data-pipeline.git


```bash
cd data-pipeline
pip install -r requirements.txt

python data_pipeline.py
