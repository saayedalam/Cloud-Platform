
Fall 2019 DATA 622 # hw3

Assigned on October 16, 2019 Due on Nov 3rd 2019 11:59 PM EST

17 points possible, worth 17% of your final grade

Instructions:

Get set up with free academic credits on both Google Cloud Platform (GCP) and Amazon Web Services (AWS). Instructions were sent in 2 separate emails to your CUNY inbox a couple of weeks ago, please reach out to me if you did not get them.

Research the products that AWS and GCP offer for storage, computing and analytics. A few good starting points are: 
- GCP product list 
- AWS product list 
- GCP quick-start tutorials 
- AWS quick-start tutorials 
- Mapping GCP to AWS products 
- Mapping GCP to MS Azure 
- Evaluating GCP against AWS

Critical Thinking (5 points total)

Design one way of migrating homework 2's outputs to GCP. Evaluate the strength and weakness of each method using the Agile Data Science framework. Design and discuss the method (2.5 points).

**Migration: Create a new project > set up a virtual machine instance > update network settings for jupyter notebook to access virtually > install anaconda in the created instance > run the jupyter notebook > upload the homework 2 files from local folders.**

**Strength: Very easy to deploy > A Virtual Machine (VM) also called "an instance" is an on-demand server. The underlying hardware is shared among other users in a transparent way. >  A VM is defined by the type of persistent disk and the operating system (OS), such as Windows or Linux, it is built upon. The persistent disk is the virtual slice of hardware. > An image is the physical combination of a persistent disk and the operating system. > GCP provides a feature called snapshot. A snapshot is a reflection of the content of a VM (disk, software, libraries, files) at a given time and is mostly used for instant backups. > All of this combined GCP makes a strong case for agile data science framework for iteration, ship intermediate output, get meta or climb up and down the data pipeline.** 

**Weakness: Compared to AWS, GCP offers fewer services. They also offer less region. Which would make it costly for a team member if they are far from their nearest region.**

Design one way of migrating homework 2's outputs to AWS. Evaluate the strength and weakness of each method using the Agile Data Science framework. Design and discuss the method (2.5 points).

**Migration: Setup user privilege > Setup an EC2 (VM) instance > Setup SSH to connect to the instance > Update and install necessary applications on the instance > Setup a virtual environment within python for reproducibility > Upload data into the instance > run the jupyter notebook > upload the homework 2 code and change the data directory.**

**Strength: AWS does everything GCP does. But what sets it apart is the high number of services and regions that they provide. They are an industry leader. EC2 allows us to increase or decrease storage as needed. AWS allows choosing the operating system, programming language, web application platform, database, and other services.**

**Weakness: AWS deployment process is not easy and very lengthy which can take up to 15 to 20 minutes for a simple project.
AWS is not an ideal option for start-ups that are not tech-savvy. The number of services and options can be confusing to those who may not speak the language of technology.**

 Fill out the critical thinking section by modifying this README.md file. If you want to illustrate using diagrams, check out draw.io, which has a nice integration with github. 

Applied (12 points total) 

Choose one of the methods described above, and implement it using your work from homework 2. Submit screenshots in the screenshot folder on this repo to document the completion of your process.

*Resources:*
*https://tudip.com/blog-post/run-jupyter-notebook-on-google-cloud-platform/*
