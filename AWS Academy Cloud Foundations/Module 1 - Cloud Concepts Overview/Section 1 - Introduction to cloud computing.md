# Section 1: Introduction to cloud computing

Cloud computingis the on-demand delivery of compute power, database, storage, applications, and other IT resources via the internet with pay-as-you-go pricing. These resources run on server computers that are located in large data centers in different locations around the world. When you use a cloud service provider like AWS, that service provider owns the computers that you are using. These resources can be used together like building blocks to build solutions that help meet business goals and satisfy technology requirements.

## Infrastructure as a Software

Cloud computing enables you to stop thinking of your infrastructure as hardware, and instead think of (and use) it as software. 

### Traditional Computing Model

In the traditional computing model, infrastructure is thought of as hardware. Hardware solutions are physical, which means they require space, staff, physical security, planning, and capital expenditure. 

In addition to significant upfront investment, another prohibitive aspect of traditional computing is the long hardware procurement cycle that involves acquiring, provisioning, and maintaining on-premises infrastructure. 

With a hardware solution, you must ask if there is enough resource capacity or sufficient storage to meet your needs, and you provision capacity by guessing theoretical maximum peaks. If you don’t meet your projected maximum peak, then you pay for expensive resources that stay idle. If you exceed your projected maximum peak, then you don’t have sufficient capacity to meet your needs. And if your needs change, then you must spend the time, effort, and money required to implement a new solution.

For example, if you wanted to provision a new website, you would need to buy the hardware, rack and stack it, put it in a data center, and then manage it or have someone else manage it. This approach is expensive and time-consuming.

### Cloud Computing Model

By contrast, cloud computing enables you to think of your infrastructure as software. Software solutions are flexible.You can select the cloud services that best match your needs, provision and terminate those resources on-demand, and pay for what you use. You can elastically scale resources up and down in an automated fashion. With the cloud computing model, you can treat resources as temporary and disposable. The flexibility that cloud computing offers enables businesses to implement new solutions quickly and with low upfront costs. 

Compared to hardware solutions, software solutions can change much more quickly, easily, and cost-effectively. 

Cloud computing helps developers and IT departments avoid undifferentiated work like procurement, maintenance, and capacity planning,thusenabling them to focus on what matters most. 

As cloud computing has grown in popularity, several different service models and deployment strategies have emerged to help meet the specific needs of different users. Each type of cloud service model and deployment strategy provides you with a different level of control, flexibility, and management. Understanding the differences between these cloud service models and deployment strategies can help you decide what set of services is right for your needs.

## Cloud Service as Model

There are three main cloud service models. Each model represents a different part of the cloud computing stack and gives you a different level of control over your IT resources:

<b>• Infrastructure as a service (IaaS): </b>

Services in this category are the basic building blocks for cloud IT and typically provide you with access to networking features, computers (virtual or on dedicated hardware), and data storage space. IaaS provides you with the highest level of flexibility and management control over your IT resources. It is themost similar to existing IT resources that many IT departments and developers are familiar with today.

<b>• Platform as a service (PaaS): </b>

Services in this category reduce the need for you to manage the underlying infrastructure (usually hardware and operating systems) and enable you to focus on the deployment and management of your applications. 

<b>• Software as a service (SaaS): </b>

Services in this category provide you with a completed product that the service provider runs and manages. In most cases, software as a servicerefers to end-user applications. With a SaaS offering, you do not have to think about how the service is maintained or how the underlying infrastructure is managed. You need to think onlyabout how you plan to use that particular piece of software. A common example of a SaaS application is web-based email, where you can send and receive email without managingfeature additions to the email product or maintainingthe servers and operating systems that the email program runson.


## Cloud computing deployment models

There are three main cloud computing deployment models, which represent the cloud environments that your applications can be deployed in:

• Cloud: 

A cloud-based application is fully deployed in the cloud, and all parts of the application run in the cloud. Applications in the cloud have either been created in the cloud or have been migrated from an existing infrastructure to take advantage of the benefits of cloud computing. Cloud-based applications can be built on low-level infrastructure pieces or they can use higher-level services that provide abstraction from the management, architecting, and scaling requirements of core infrastructure.

• Hybrid: 

A hybrid deployment is a way to connect infrastructure and applications between cloud-based resources and existing resources that are not located in the cloud. The most common method of hybrid deployment is between the cloud and existing on-premises infrastructure. Thismodel enables an organizationto extend and grow theirinfrastructure into the cloud while connecting cloud resources to internal systems. 

• On-premises: 

Deploying resources on-premises, using virtualization and resource management tools, is sometimes called private cloud. While on-premises deployment does not provide many of the benefits of cloud computing, it is sometimes sought for its ability to provide dedicated resources. In most cases, this deployment model is the same as legacy IT infrastructure, but itmight also use application management and virtualization technologies toincrease resource utilization

## Similarities between AWS and traditional IT

There are many similarities between AWS and the traditional, on-premises IT space:

• AWS security groups, network access control lists (network ACLs), and AWS Identity and Access Management (IAM) are similar to firewalls, access control lists (ACLs), and administrators.

• Elastic Load Balancing and Amazon Virtual Private Cloud (Amazon VPC) are similar to routers, network pipelines, and switches.

• Amazon Machine Images (AMIs) and Amazon Elastic Compute Cloud (Amazon EC2) instances are similar to on-premises servers.

• Amazon Elastic Block Store (Amazon EBS), Amazon Elastic File System (Amazon EFS), Amazon Simple Storage Service (Amazon S3), and Amazon Relational Database Service (Amazon RDS) are similar to direct attached storage (DAS), storage area networks (SAN), network attached storage (NAS), and a relational database management service (RDBMS).

With AWS services and features, you can do almost everything that you would want to do with a traditional data center

Some keytakeaways from this section of the module include:

• Cloud computing is the on-demand delivery of IT resources via the internet with pay-as-you-go pricing.

• Cloud computing enables you to think of (and use) your infrastructure as software.

• There are three cloud service models: IaaS, PaaS, and SaaS.

• There are three cloud deployment models: cloud, hybrid, and on-premises or private cloud.

• There are many AWS service analogs for the traditional, on-premises IT space.
