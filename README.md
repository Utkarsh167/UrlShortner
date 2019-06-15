# UrlShortner
URL Shortner Assignment
To get Short Url open any client environment example postman and type in form raw (application/json)
{
"originalUrl":"https://www.google.com/search?client=firefox-b-d&q=Cannot+GET+%2Fapi%2Fitem",
"shortBaseUrl":"https://google"
}


will receive response like :

{
    "_id": "5d049f3f4d992206b4f2e096",
    "originalUrl": "https://www.google.com/search?client=firefox-b-d&q=Cannot+GET+%2Fapi%2Fitem",
    "shortUrl": "https://google/d8NfwmSks",
    "urlCode": "d8NfwmSks",
    "updatedAt": "2019-06-15T07:33:19.283Z",
    "createdAt": "2019-06-15T07:33:19.286Z",
    "__v": 0
}
