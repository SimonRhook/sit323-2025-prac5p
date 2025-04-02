# sit323-2025-prac5p

Simple docker file and docker compose file to initialise web calulator from previous tasks in a docker container.

To Run standalone image:

- Step 1: after downloading files, run command `docker build . -t web-calc`
- Step 2: run command `docker run -p 8080:8080 web-calc`
- Step 3: in broswer, navigate to any of the following

  - http://localhost:8080/add?n1=1&n2=2
  - http://localhost:8080/subtract?n1=1&n2=2
  - http://localhost:8080/multiply?n1=1&n2=2
  - http://localhost:8080/divide?n1=1&n2=2
  - http://localhost:8080/exponent?n1=1&n2=2
  - http://localhost:8080/root?n=1
  - http://localhost:8080/mod?n1=1&n2=2

- Step 4(Optional): For different number calculations, change the numbers in the URL after n1 and n2

To Run compose:

- Step 1: after downloading files, run command `docker-compose up --build`
- Step 2: in broswer, navigate to any of the following

  - http://localhost:8080/add?n1=1&n2=2
  - http://localhost:8080/subtract?n1=1&n2=2
  - http://localhost:8080/multiply?n1=1&n2=2
  - http://localhost:8080/divide?n1=1&n2=2
  - http://localhost:8080/exponent?n1=1&n2=2
  - http://localhost:8080/root?n=1
  - http://localhost:8080/mod?n1=1&n2=2

- Step 3(Optional): For different number calculations, change the numbers in the URL after n1 and n2
