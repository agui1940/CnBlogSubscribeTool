# CnBlogSubscribeTool
CnBlogSubscribeTool can crawl blog home page data at regular intervals.

## Config

- /Config/Mail.json

````
{
  "Name": "CnBlogSubscribeTool",
  "Address": "",
  "Host": "",
  "Port": 25,
  "Password": "",
  "ReceiveList": [
    "test1@test.com",
    "test2@test.com",
  ] 
}
````

## Email

9 o'clock every day will send yesterday's blogs

## Data

Get the data once every five minutes
