# Intensive-Cloud-Training-Project [(Link)](https://thecloudbootcamp.com/en/pc-multicloud-event-icp2/?utm_source=youtube&utm_campaign=icp7-organic&utm_medium=linknadescricao&utm_content=cpl1&sck=&hl=)
*The data will not be provided here since all rights are reserved by @The Cloud Bootcamp. And this is just for learning and documenting only.
© The Cloud Bootcamp. All rights reserved (Created for educational purporses only - prohibited production)

## Preface
A few weeks ago, I passed the AWS Certified Cloud Practitioner (CCP) exam. The certificate is worth a lot to me and can help me go further in my career path since there is a trend for using cloud service to better maintain the company's application securely and costlessly. I highly recommend this exam for every cloud beginner since it would tell and illustrate how the cloud services work to achieve their purposes(ex: low latency, highly available, and so on). Don't worry, it's definitely related to the data science area that you and I are pursuing. Yes, I'm referring to the MLOps, deploying and maintaining machine learning models to production reliably and efficiently. Everything is relevant and works with each other, so don't be afraid to learn the cloud service!

Let's back to the topic of [multi-cloud](https://www.juniper.net/us/en/research-topics/what-is-multicloud.html#:~:text=For%20example%2C%20a%20multicloud%20could,stack%20on%20either%20public%20or). Before I took the intensive cloud training from [@thecloudbootcamp](https://www.youtube.com/@thecloudbootcamp). I think maybe it's enough to just specialize in a specific cloud service depending on the requirement of the company, such as AWS, GCP, Azure, and Oracle. However, a multi-cloud strategy can bring more flexibility for a company to select the best solution to meet its business need and requirement. In other words, multi-cloud is an expansion or upgraded version of one cloud platform service, which can provide higher availability and lower cost across multiple cloud hosting providers. Maybe I will not have a chance to apply all of the techniques used here in the future, but it can broaden my horizon and help me consider more when making decisions. In the end, I'm definitely not a professional in the cloud field but it's a good chance to start! 

Please don't worry about the expense of this project! You will not spend any money on this project! When signing up for new accounts of AWS and GCP, you will be on the free tier for AWS and have $300 credits for GCP to start your first cloud project. Sounds great? Let's start it! The cloud hosting providers and tools we will use are listed below:

- Cloud Platform: AWS, GCP
- Development Tools: Terraform, Docker, Kubernetes, Container Registry
- Data Storage: AWS S3
- Database: Google Cloud SQL

## Hands-on Practice Before the Start
Before we go deep into the project, if you are not familar with the technologies, we can start with hands-on practice. This section can help you better understand how to apply these development tools and technologies in practice. 

*Note: To use the cloud service, we need to sign up for the accounts of AWS and GCP. 
- [Hands-on with AWS and Terraform](https://github.com/TeKaiChou/Intensive-Cloud-Training-Project/blob/main/Hands-on%20Practice/Hands-on%20with%20AWS%20and%20Terraform.pdf)
- [Hands-on with Docker and Cloud](https://github.com/TeKaiChou/Intensive-Cloud-Training-Project/blob/main/Hands-on%20Practice/Hands-on%20with%20Docker%20and%20Cloud.pdf)
- [Hands-on with Kubernetes on Cloud](https://github.com/TeKaiChou/Intensive-Cloud-Training-Project/blob/main/Hands-on%20Practice/Hands-on%20with%20Kubernetes%20on%20Cloud.pdf)

## Case Study - Luxxy Covid Testing System (Define the problem)
Thanks to intensive cloud training with real world case study information and data, we have the opportunity to use the most modern technologies and tools mentioned in practice to migrate real applications of luxury hotel chains to the cloud environment. Due to the covid-19 pandemic, hotels are required to keep testing records of customers' testing status to safely manage the hotel. The ever-increasing demand for network application traffic and data storage requires hotels to prepare more resources to deal with this situation. In this case, migrating the entire application and data to the cloud environment is a good solution, because the hotel does not have to worry about provisioning and managing instances and hardware itself, and the required resources can be scaled automatically based on demand. We will follow the instruction provided by the intensive cloud training step by step to understand the details of this project. I believe the real-world case does help us better understand how that knowledge and technologies were used in the market. Let's take a look at the solution architecture below: (You can also find the info of the project in the [link](https://thecloudbootcamp.com/en/pc-multicloud-event-icp2/?utm_source=youtube&utm_campaign=icp7-organic&utm_medium=linknadescricao&utm_content=cpl1&sck=&hl=).)


![image](https://user-images.githubusercontent.com/61730268/218293155-c0cfb94b-8c0c-48be-96e9-5f4aaa1b53f7.png)
![image](https://user-images.githubusercontent.com/61730268/218292567-ccc8ad53-c80a-4a82-bed1-5690e85a6298.png)

## [Mission 1: Resources Provision](https://github.com/TeKaiChou/Intensive-Cloud-Training-Project/blob/main/Hands-on%20Project/Mission1/Steps%20to%20implement%20Hands-on%20Project%20-%20Mission%201.pdf)
You'll learn how to enable a MultiCloud architecture deployment through Terraform, with resources running in AWS and Google Cloud Platform. To be specific, you will know how to:

- Create new IAM user with its credentials (access keys and secret access keys) via AWS console
- Use terraform to provision infrastructure resources across multiple cloud platform (multi-cloud conept) on Google Cloud Shell, including AWS S3, Google Container Registry (GCR),  Google Kubernetes Engine (GKE), and Google Cloud SQL 


## [Mission 2: Application Deployment](https://github.com/TeKaiChou/Intensive-Cloud-Training-Project/blob/main/Hands-on%20Project/Mission2/Steps%20to%20implement%20Hands-on%20Project%20-%20Mission%202.pdf)
You'll learn the process to convert a database and an application to run on the MultiCloud architecture (AWS and Google Cloud), including Docker and Kubernetes on this path. To be specific, you will know how to:

- Setup and connect to MySQL database on Google Cloud SQL instance that we provision in mission 1
- Build the Docker image and push it to GCR (images storage)
- Connect to the GKE cluster and deploy the application Luxxy in the cluster

When you land here, your application successfully runs on the cloud!

## [Mission 3: Database Migration](https://github.com/TeKaiChou/Intensive-Cloud-Training-Project/blob/main/Hands-on%20Project/Mission3/Steps%20to%20implement%20Hands-on%20Project%20-%20Mission%203.pdf)
For the final phase, you'll learn how to professionally migrate the application files and data from a database, an essential skill required by several companies in the Cloud migration process. To be specific, you will know how to:

- Migrate database to google cloud SQL with MySQL database
- Migrate pdf files through AWS Cloud Shell (CLI)

You're done! 

## [Final Step: Resources Deletion](https://github.com/TeKaiChou/Intensive-Cloud-Training-Project/blob/main/Hands-on%20Project/How%20to%20delete%20the%20Multiple%20Cloud%20Providers%20resources.pdf)
Remember to delete all resources that you will not use anymore to stop being charged by cloud service!!!
