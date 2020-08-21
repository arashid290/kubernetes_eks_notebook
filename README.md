
<h2> Notebooks will not render correctly in GitHub </h2>
<h1> Welcome to Kubernetes on EKS </h1>

![Cloudformation](https://adnanstudyimages.s3.amazonaws.com/a4.png)
 

This repository consists of the following notebooks:
<ol>
    
<li>Setup
<li>Create EKS Cluster
<li>Deploy Official Kubernetes Dashboard
<li>Deploy Example MicroServices
<li>Helmv3
<li>Health Checks
<li>Implement AutoScaling with HPA and CA
<li>Intro To RBAC
<li>Using IAM Groups to Manage Kubernetes Cluster Access
<li>IAM Roles for Service Accounts
<li>Securing Your Cluster With Network Policies
<li>Exposing a Service
<li>Assigning Pods to Nodes
<li>Using Spot Instances with EKS
<li>Advanced VPC Networking with EKS
<li>Stateful Containers using StatefulSets
<li>Deploying Microservices to EKS Fargate
<li>Deploying Microservices with AWS EFS
<li>Encrypting Kubernetes Secrets
<li> Deploying Jenkins
<li> CI/CD with CodePipeline
<li>Final Cleanup
</ol>


<br><br>

<h1> 4 Steps to Begin </h1>

<ol>
 <li> Log into your AWS Account

  ![Console](https://adnanstudyimages.s3.amazonaws.com/a1.png)

 <li> Launch SageMaker using the following template: https://eu-west-1.console.aws.amazon.com/cloudformation/home?region=eu-west-1#/stacks/quickcreate?templateURL=https://adnanstudyimages.s3-eu-west-1.amazonaws.com/Sagemaker-eks.yml&stackName=EKS-Notebook&param_SageMakerNotebookGitRepository=https://github.com/arashid290/kubernetes_eks_notebook.git
 <br><br>

 ![Cloudformation](https://adnanstudyimages.s3.amazonaws.com/a2.png)

 <li>This template will launch SageMaker with the above downloaded and tools installed. Click on 'JupyterLab' <br><br>

 ![SageMaker](https://adnanstudyimages.s3.amazonaws.com/a3.png)

 <li> Set dark theme in Jupyter

 ![SageMaker](https://adnanstudyimages.s3.amazonaws.com/a6.png)

 <li> Start Learning! 
</ol>

<h1> Pricing </h1>
<ol>
 <li> SageMaker is free for 2 months </li>
 <li> https://aws.amazon.com/sagemaker/pricing/
</ol>

<h1> Information </h1>
<ol>
    <li> SageMaker will auto shutdown if idle for more than 1 hour
    <li> EKS Cluster costs 0.10$ per hour 
    <li> We spin up 3 t3.medium instances which cost $0.0418 each 
    <li> Average daily cost if running all day will be approximately $2.4 (Cluster) + $3.0096 (3 instances) = $5.4 
    <li> It is possible to reduce the cost by reducing the number of instances and also the size of the instance within the playbooks
    <li> Alternatively you can destroy the cluster after each lab, creating and destroying the cluster is a single command.
</ol>

<h1> About Me </h1>

<ol>
 <li>Adnan Study Website: https://adnan.study 
 
 ![HomePage](https://adnanstudyimages.s3.amazonaws.com/a5.png)
 
 <li>LinkedIn: https://www.linkedin.com/in/adnanrashid1/ 
 <li>Instagram: https://www.instagram.com/adnans_techie_studies/ 
 <li>Reference: https://eksworkshop.com/
</ol>   
