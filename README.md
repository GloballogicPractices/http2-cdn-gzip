# http2-cdn-gzip
Docker compose code for demo of http2, cdn and gzip compression using nginx and html page

Step 1: Download Code from https://github.com/GloballogicPractices/http2-cdn-gzip.git
Step 2: Goto root directory
Step 3: (Optional) upload testdata.txt file to s3 which already mapped to CDN. Open Testpage.html file and update cdn address here. 
Step 4: run command "docker-compose up --build -d" for building code
Step 5: check running container using "docker ps" command
Step 6: Check Test page on browser
      - https://localhost:444/ for http2
      - http://localhost:82/ for gzip
      - http://localhost:83/ for cdn
