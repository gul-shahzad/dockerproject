# dockerproject
This project creates docker flow which I have created by using AWS Cloud9

## Setup 
1. Add app.py, Dockerfile, Makefile, requirements.txt into the project - Done
2. RUN: chmod +x app.py
3. sudo wget -O /bin/hadolint https://github.com/hadolint/hadolint/releases/download/v1.17.6/hadolint-Linux-x86_64 && \ chmod +x /bin/hadolint
4. docker build --tag=app .