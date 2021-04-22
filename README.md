# python_django_drf_api_token_authentication_hello_2_client

python_django_drf_api_token_authentication_hello_2_client

[CLIENT SIDE]

TokenAuthentication HTTPie 

[mac]

http http://127.0.0.1:8000/hello/ 'Authorization: Token 3d6972c7f1d9d2a950c16fec6ca48b921ba253c4'

[win]

http GET http://127.0.0.1:8000/hello/ "Authorization: Token 3d6972c7f1d9d2a950c16fec6ca48b921ba253c4"


TokenAuthentication curl

[mac]

curl http://127.0.0.1:8000/hello/ -H 'Authorization: Token 3d6972c7f1d9d2a950c16fec6ca48b921ba253c4'

[win]

curl -H "Authorization: Token 3d6972c7f1d9d2a950c16fec6ca48b921ba253c4" http://127.0.0.1:8000/hello/


new API endpoint

http http://127.0.0.1:8000/api-token-auth/

http post http://127.0.0.1:8000/api-token-auth/ username=user1 password=k87654321

"token": "3d6972c7f1d9d2a950c16fec6ca48b921ba253c4"


