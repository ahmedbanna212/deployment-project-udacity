# pipeline documentation

## Integration step

### first step : frontend install dependinces
install all the npm packs required to run the frontend

### second step : api install dependinces
install all the npm packs required to run the api

### third step : api lint
runnig `ng lint` command to insure that the code is free from syntex errors

### fourth step : frontend build
runnig the frontend build command to make the frontend ready for deployment

## deployment

### fifth step : api deploy

deploy the backend part on AWS Elastic Beanstalk using eb cli


### sixth step : env variables
settting environment variables for the backend

### seventh step : frontend deploy
deploy the frontend part on AWS s3 bucket using aws cli