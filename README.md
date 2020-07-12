# Amazon Elastic Kubernetes Service (Amazon EKS)

Amazon Elastic Kubernetes Service (Amazon EKS) is a fully managed Kubernetes service. Customers such as Intel, Snap, Intuit, GoDaddy, and Autodesk trust EKS to run their most sensitive and mission critical applications because of its security, reliability, and scalability.

EKS is the best place to run Kubernetes for several reasons. First, you can choose to run your EKS clusters using AWS Fargate, which is serverless compute for containers. Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design. Second, EKS is deeply integrated with services such as Amazon CloudWatch, Auto Scaling Groups, AWS Identity and Access Management (IAM), and Amazon Virtual Private Cloud (VPC), providing you a seamless experience to monitor, scale, and load-balance your applications. Third, EKS integrates with AWS App Mesh and provides a Kubernetes native experience to consume service mesh features and bring rich observability, traffic controls and security features to applications. Additionally, EKS provides a scalable and highly-available control plane that runs across multiple availability zones to eliminate a single point of failure.

EKS runs upstream Kubernetes and is certified Kubernetes conformant so you can leverage all benefits of open source tooling from the community. You can also easily migrate any standard Kubernetes application to EKS without needing to refactor your code.

# Benefits of Amazon EKS


# High Availability
EKS runs the Kubernetes management infrastructure across multiple AWS Availability Zones, automatically detects and replaces unhealthy control plane nodes, and provides on-demand, zero downtime upgrades and patching.

# Serverless option
EKS supports AWS Fargate to provide serverless compute for containers. Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design.

# Secure
EKS automatically applies the latest security patches to your cluster control plane. AWS also works closely with the community to ensure critical security issues are addressed before new releases and patches are deployed to existing clusters.

# Built with the Community
EKS runs upstream Kubernetes and is certified Kubernetes conformant, so applications managed by EKS are fully compatible with applications managed by any standard Kubernetes environment. AWS actively works with the Kubernetes community, including making contributions to the Kubernetes code base that help you take advantage of AWS services and features.

# Use cases of Amazon EKS

# Hybrid Deployment
You can use EKS on AWS Outposts to run containerized applications that require low latencies to on-premises systems. AWS Outposts is a fully managed service that extends AWS infrastructure, AWS services, APIs, and tools to virtually any connected site. With EKS on Outposts, you can manage containers on-premises with the same ease as you manage your containers in the cloud.

# Machine Learning
You can use Kubeflow with EKS to model your machine learning workflows and efficiently run distributed training jobs using the latest EC2 GPU-powered instance types. You can also use AWS Deep Learning Containers for running training and inferences in TensorFlow on EKS.

# Batch Processing
You can run sequential or parallel batch workloads on your EKS cluster using the Kubernetes Jobs API. Using EKS, you can plan, schedule, and execute your batch computing workloads across the full range of AWS compute services and features, such as Amazon EC2, Fargate, and Spot Instances.

# Web Applications
You can build web applications that automatically scale up and down and run in a highly available configuration across multiple Availability Zones. By running on EKS, your web applications benefit from the performance, scale, reliability, and availability of the AWS. Additionally, your services get out-of-the-box integrations with AWS networking and security services, such as Application Load Balancers for load distribution of your web application and VPC for networking.
