# AWS-PhotoAlbum-Project
This project is a highly available photo album website developed using Amazon Web Services (AWS). It includes features like photo uploading, metadata storage, image resizing using Lambda, and load balancing across multiple EC2 instances.

## Features

- **VPC Configuration**: Set up with two Availability Zones, each with public and private subnets.
- **EC2 Instances**: Deployed for the web server and NAT gateway.
- **S3 Bucket**: Used for storing uploaded photos and resized images.
- **Lambda Function**: Automatically resizes images and stores them in the S3 bucket.
- **RDS MySQL Database**: Stores metadata for each uploaded photo.
- **Load Balancing**: Application Load Balancer used for distributing incoming requests across multiple EC2 instances.
- **Auto Scaling**: Automatically scales the number of EC2 instances based on traffic.

## Technologies Used

- **AWS Services**: VPC, EC2, S3, RDS, Lambda, Elastic Load Balancer, Auto Scaling.
- **Programming Languages**: PHP, Python (for Lambda function).
- **Database**: MySQL hosted on Amazon RDS.
- **Security**: IAM roles, Security Groups, Network ACLs.

## Getting Started

1. Clone this repository.
2. Ensure you have access to AWS services.
3. Follow the steps outlined in the `Assignment2_report.pdf` for a detailed deployment walkthrough.

## Author

- **M Anzor Yousuf** - [LinkedIn Profile](https://www.linkedin.com/in/m-anzor-yousuf/)

## Disclaimer
This project was completed as part of my coursework for the Cloud Computing Architecture unit at Swinburne University of Technology. It is shared here for educational purposes and to showcase my work in cloud computing.

## Note
The website associated with this project was hosted on a university server and is no longer accessible online. This repository contains the code and documentation related to the project.

