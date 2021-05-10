# collab

1. docker build . -t collab:1
2. docker run -p 8888:8888 collab:1

Note: If running on wsl(2) you'll need to get your IP (`ip address`) and then put that IP in your browser, followed by `:8888` and then get the token that the docker run command splatted into your wsl(2) terminal. The final url should look something like this:

`<your ip>:8888/lab?token=<your token>`
