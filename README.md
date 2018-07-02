### Run development mode
At your terminal, run `docker-compose up -d`
Go to http://127.0.0.1:3000/admin/install  and add 
http://127.0.1.1:5000
http://127.0.1.1:3000
http://localhost:5000/
to the permitted domains lists. And add http://127.0.1.1:5000/index.css to the custom css URL.
Then, run `serve` and go to localhost:5000