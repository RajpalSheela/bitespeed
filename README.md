# bitespeed

service endpoint:- https://rajpal-bitespeed.onrender.com/ping

sample curl
```
curl --location 'https://https://rajpal-bitespeed.onrender.com/identify' \
--header 'Content-Type: application/json' \
--data-raw '{
    "email": "rajpal630@gamil.com",
    "phoneNumber": "123459"
}'
```
steps to test in postman:-
----------------------------
1. enter the url `https://rajpal-bitespeed.onrender.com/identify` in url bar.
2. select http method as `POST`
3. Goto body tab, select `none` and from dropdown select `json`. and provide body in json format sample:-
{
    "email": "rajpalgarg630@gamil.com",
    "phoneNumber": "123459"
}
4. hit `send` button

Note:-
------------
1. I have removed all data from table.
2. We can add validator to api for robust system. I didn't find any instruction to add so I skipped.

 I have deployed this instance to free tier renderer server. It will stop the instance incase of inactivity for some time. If you are facing any issue while calling the api, please let me know I will restart the instance. 
