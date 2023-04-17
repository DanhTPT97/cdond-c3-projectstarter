### Project Submission

- Including:
  1. Public Url to GitHub repository (not private) [URL01](https://app.circleci.com/pipelines/github/DanhTPT97/cdond-c3-projectstarter)
  1. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02](http://udapeople-c809635.s3-website-us-east-1.amazonaws.com/)
  1. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03](d2gzeu8x328ps5.cloudfront.net)
  1. Public URLs to deployed application back-end in EC2 [URL04](http://ec2-34-203-189-89.compute-1.amazonaws.com:3030/api/status)
  1. Public URL to your Prometheus Server [URL05](http://ec2-3-92-133-178.compute-1.amazonaws.com:9090/targets)
- screenshots listed in the instructions.
  1. Job failed because of compile errors. [SCREENSHOT01](./screenshots/SCREENSHOT01.png)
  1. Job failed because of unit tests. [SCREENSHOT02-BE](./screenshots/SCREENSHOT02-BE.png) and [SCREENSHOT02-FE](./screenshots/SCREENSHOT02-FE.png)
  1. Job that failed because of vulnerable packages. [SCREENSHOT03-BE](./screenshots/SCREENSHOT03-BE.png) and [SCREENSHOT03-FE](./screenshots/SCREENSHOT03-FE.png)
  1. An alert from one of your failed builds. [SCREENSHOT04](./screenshots/SCREENSHOT04.png)
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05](./screenshots/SCREENSHOT05.png)
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06](./screenshots/SCREENSHOT05.png)
  1. Successful rollback after a failed smoke test. [SCREENSHOT07](./screenshots/SCREENSHOT05.png)  
  1. Successful promotion job. [SCREENSHOT08](./screenshots/SCREENSHOT08.png)
  1. Successful cleanup job. [SCREENSHOT09](./screenshots/SCREENSHOT09.png)
  1. Only deploy on pushed to `master` branch. [SCREENSHOT10](./screenshots/SCREENSHOT10.png)
  1. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11](./screenshots/SCREENSHOT11.png)
  1. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12](./screenshots/SCREENSHOT12.png)

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool
