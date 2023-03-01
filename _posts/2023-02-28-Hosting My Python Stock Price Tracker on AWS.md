---
#layout: post
title: "Hosting My Python Stock Price Tracker on AWS"
#date: 2023-02-25
#author: [Alassiri MA]
#categories: [Blog Hosting]
#tags: [GitHub Pages, Jekyll, Blogging]
#image: [Insert an image if you have one that is relevant to the post]
---
## Introduction:
After successfully building my Python stock price tracker, I decided to take it to the next level by hosting it on Amazon Web Services (AWS). This would allow me to run the application on the cloud, rather than on my local machine, and make it accessible to a wider audience. In this post, I'll walk through the steps I took to set up the application on AWS and the challenges I faced along the way.

## Setting Up an AWS Account:
To get started, I created an AWS account and navigated to the EC2 service. I selected a pre-configured Amazon Machine Image (AMI) that was compatible with Python and contained the necessary libraries and dependencies for my application. After configuring the instance details, security groups, and storage, I launched the instance and connected to it using SSH.

## Transferring Files to the Instance:
To transfer my Python script and data files to the instance, I used the secure copy (SCP) command in the terminal. This allowed me to upload and download files securely between my local machine and the instance. I explained the syntax of the SCP command and the steps involved in transferring files.

## Installing Libraries and Dependencies:
Once I had transferred the necessary files to the instance, I installed the required libraries and dependencies using pip. I encountered some issues with package version compatibility, but was able to resolve them by updating the package configurations.

## Configuring the Application for AWS:
To run the application on AWS, I needed to configure it to run as a background process and make it accessible through a public IP address. I used the nohup command to run the Python script in the background and created a security group that allowed inbound traffic on the necessary ports.

## Testing and Troubleshooting:
After configuring the application for AWS, I tested it with various stock symbols and date ranges to ensure that it was functioning properly. I encountered issues with slow loading times and network latency, but was able to optimize the performance by adjusting the instance type and storage capacity.

## Conclusion:
Hosting my Python stock price tracker on AWS was a challenging but rewarding experience that allowed me to expand my knowledge of cloud computing and application deployment. By breaking down the steps and seeking help from online resources and forums, I was able to successfully set up and configure the application for AWS. Going forward, I plan to explore more applications of cloud computing and integrate them into my programming projects.