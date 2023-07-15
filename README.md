[![<CricleCi>](https://circleci.com/gh/nguyentieuat/-JS_UDA-Full_Stack_Application.svg?style=svg)](https://app.circleci.com/pipelines/github/nguyentieuat/-JS_UDA-Full_Stack_Application?branch=master)

## Description
This application is provided from Udacity to be hosted into **AWS** with Pipeline using **CircleCI**.
The Project is for the **Advanced Full-Stack Web Development Nanodegree Program - Deploying & Hosting a Full-Stack Application**.

## Getting Started

### Project Setup local

1. Clone the project - `git clone https://github.com/nguyentieuat/-JS_UDA-Full_Stack_Application.git`
2. Go into the project directory - `cd udagram`
3. Install the evn - `source set_env.sh`
4. Go into the project directory frontend- `cd udagram-frontend`
5. Install dependencies the frontend - `npm install -f`
6. Build the frontend - `npm run build`
7. Start the frontend - `npm run start`
8. Install dependencies the backend - `npm install .`
9. Build the backend - `npm run build`
10. Start the backend - `npm run start`

### AWS Cloud Setup
- Environment Variables
Setup the following variables in the cloud environments:
```
- POSTGRES_USERNAME=postgresdb
- POSTGRES_PASSWORD=Anhnhoem220v3
- POSTGRES_HOST=postgres.cih3g0ltfxzr.us-east-1.rds.amazonaws.com
- POSTGRES_DB=postgres
- AWS_BUCKET=arn:aws:s3:::myprojectbucketz
- AWS_REGION=us-east-1
- AWS_PROFILE=default
- JWT_SECRET=mysecretstring
```

- RDS - Database Host: postgres.cih3g0ltfxzr.us-east-1.rds.amazonaws.com
- RDS - Database Port: 5432
- RDS - Database Name: postgres

- S3 Endpoint - Frontend: http://myprojectbucketz.s3-website-us-east-1.amazonaws.com/

- Elastic Beanstalk URL - Backend: http://myprojectv3-env.us-east-1.elasticbeanstalk.com/

### Evidences
Some images in folder Screenshot