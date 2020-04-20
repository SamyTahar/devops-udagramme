# Project 2 Cloudformation Script

Height available architecture using auto scaling and private S3 bucket to load the app to be deploy within the EC2 instance

### Todo
* Route 53
* Add custom DNS to load balancer


## Architecture AWS
![40% center](https://github.com/SamyTahar/devops-udagramme/blob/master/udacity_project2_archi.png )


### how to run the cloudformation script Run 
Use AWS CLI :
aws cloudformation create-stack --stack-name NameOfYouStack --region YourRegion --template-body file://yourFile.yml|json --parameters file://yourFile.json --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM"
