# http2-cdn-gzip

Description:
  * Docker compose code for demo of http2, cdn and gzip compression using nginx and html page

Prerequisite:
  * Docker compose setup require

Working with code:
* Step 1: Download Code from https://github.com/GloballogicPractices/http2-cdn-gzip.git
* Step 2: Goto root directory
* Step 3: (Optional) upload testdata.txt file to s3 which mapped to CDN. Open Testpage.html file and update cdn address here. 
* Step 4: run command "docker-compose up --build -d" for building code
* Step 5: check running container using "docker ps" command
* Step 6: Open Network option in browser e.g.
![open network](https://user-images.githubusercontent.com/26079118/39236850-7e44fc30-4897-11e8-951a-0bb38b3d8f79.png)
* Step 7: Check Test page on browser
  * https://localhost:444/ for http2 (http2 only work with https)
  * http://localhost:82/ for gzip
  * http://localhost:83/ for cdn
