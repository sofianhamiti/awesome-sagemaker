<div align="center">
  <a href="https://aws.amazon.com/sagemaker/">
  <img width="250" height="250"  src="img/awesome-sagemaker-intro.svg" alt="SageMaker"></a>
</div>
<h1 align="center">
	AWSome SageMaker
</h1>
<div align="center">
  <a href="https://github.com/sindresorhus/awesome">
  <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
</div>

> A curated list of awesome references for Amazon SageMaker.

## Contents
- [Getting Started](#getting-started) 
- [Core Functionalities](#core-functionalities)
- [ML Domains](#machine-learning-domains)
- [ML Lifecycle](#machine-learning-lifecycle)
- [Advanced Topics](#advanced-topics)
- [Enterprise & Architecture](#enterprise-architecture)
- [Training & Certification](#training-certification)  
- [Community](#community)  
- [Books](#books) 
- [What's New](#news) 
- [Contributions](#contributions)

<a name="getting-started"></a>
## Getting Started
- [Introduction to Amazon SageMaker](https://www.youtube.com/watch?v=Qv_Tr_BCFCQ)
- [SageMaker Example Notebooks](https://sagemaker-examples.readthedocs.io/en/latest/)
- [Amazon SageMaker 101 Workshop](https://catalog.us-east-1.prod.workshops.aws/workshops/0c6b8a23-b837-4e0f-b2e2-4a3ffd7d645b/en-US)
- [SageMaker Immersion Day (hands-on labs)](https://catalog.us-east-1.prod.workshops.aws/workshops/63069e26-921c-4ce1-9cc7-dd882ff62575/en-US)
- [Develop, Train, Optimize and Deploy Scikit-Learn Random Forest](https://github.com/aws/amazon-sagemaker-examples/blob/main/sagemaker-python-sdk/scikit_learn_randomforest/Sklearn_on_SageMaker_end2end.ipynb)

<a name="core-functionalities"></a>
## Core Functionalities
- ### Developer Experience
  - [Onboard Quickly to Amazon SageMaker Studio](https://www.youtube.com/watch?v=wiDHCWVrjCU)
  - [Hosting VS Code on SageMaker](https://towardsdatascience.com/hosting-vs-code-in-sagemaker-studio-f211385e25f7)
  - [Using RStudio on SageMaker](https://www.rstudio.com/sagemaker/)
- ### SDKs/Infrastructure-as-Code
  - [SageMaker Python SDK](https://sagemaker.readthedocs.io/en/stable/)
  - [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker.html)
  - [CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/AWS_SageMaker.html)
  - [CDK](https://docs.aws.amazon.com/cdk/api/v2/python/aws_cdk.aws_sagemaker.html)
  - [Terraform](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/sagemaker_domain)
- ### Containers/Frameworks
  - [Supported pre-built containers/frameworks (script mode)](https://sagemaker.readthedocs.io/en/stable/frameworks/index.html)
  - [Using Script Mode with Amazon SageMaker](https://www.youtube.com/watch?v=x94hpOmKtXM)
  - [Using custom training containers](https://github.com/aws/amazon-sagemaker-examples/tree/main/advanced_functionality/custom-training-containers)
  - [Training toolkit](https://github.com/aws/sagemaker-training-toolkit) and [Inference toolkit](https://github.com/aws/sagemaker-inference-toolkit)
- ### Jobs
  - [SageMaker Processing](https://sagemaker.readthedocs.io/en/stable/amazon_sagemaker_processing.html#amazon-sagemaker-processing)
  - [Local mode](https://github.com/aws-samples/amazon-sagemaker-local-mode)
  - [Debugging with Tensorboard](https://google.fr/)
- ### Inference
  - [Running Triton Inference Server with Amazon SageMaker](https://www.coursera.org/lecture/machine-learning-aws-nvidia/running-triton-inference-server-with-amazon-sagemaker-HwIki)

<a name="machine-learning-domains"></a>
## ML Domains
- ### Computer Vision
  - [Using the TensorFlow 2 Object Detection API with Amazon SageMaker](https://aws.amazon.com/blogs/machine-learning/training-and-deploying-models-using-tensorflow-2-with-the-object-detection-api-on-amazon-sagemaker/)
  - [Object detection with Detectron2 on Amazon SageMaker](https://aws.amazon.com/blogs/machine-learning/object-detection-with-detectron2-on-amazon-sagemaker/)
- ### Natural Language Processing
  - [Hugging Face on Amazon SageMaker](https://huggingface.co/docs/sagemaker/main)
  - [Hugging Face on Amazon SageMaker Tutorial - Part 1](https://www.youtube.com/watch?v=80ix-IyNnQI), [Part 2](https://www.youtube.com/watch?v=BqQ14SZ5tos), [Part 3](https://www.youtube.com/watch?v=oVIvXfeunv8) 
- ### AutoML
  - [Using AutoML to create high-quality models with just a few clicks](https://www.youtube.com/watch?v=f9aCwmVWvC8)
  - [Using AutoML for Common Financial Services Use Cases](https://www.youtube.com/watch?v=r2-VmuUh7jM)
- ### Low-Code/No-Code
  - [Amazon SageMaker Canvas - Generate accurate ML Predictions - No Code Required](https://www.youtube.com/watch?v=Sy3GDQT6Lnk)
  - [Canvas Immersion Day](https://catalog.us-east-1.prod.workshops.aws/workshops/80ba0ea5-7cf9-4b8c-9d3f-1cd988b6c071/en-US)

<a name="machine-learning-lifecycle"></a>
## ML Lifecycle
- ### Data Labeling
  - [Introducing Amazon SageMaker Ground Truth Plus](https://www.youtube.com/watch?v=Y3Lo63yiqsU)
  - [Labeling data with Label Studio on SageMaker](https://medium.com/geekculture/labeling-data-with-label-studio-on-sagemaker-e4b2d1b562f7)
- ### MLOps Foundations
  - [MLOps foundation roadmap for enterprises with Amazon SageMaker](https://aws.amazon.com/blogs/machine-learning/mlops-foundation-roadmap-for-enterprises-with-amazon-sagemaker/)
  - [Implementing MLOps practices with Amazon SageMaker, featuring Vanguard](https://www.youtube.com/watch?v=fuXUi_hoK78)
- ### SageMaker Pipelines
  - [Automate MLOps with SageMaker Projects](https://www.youtube.com/watch?v=3_cHnk9VSfQ)
  - [Introducing Amazon SageMaker Pipelines](https://www.youtube.com/watch?v=Hvz2GGU3Z8g)
  - [Building, automating, managing, and scaling ML workflows using Amazon SageMaker Pipelines](https://aws.amazon.com/blogs/machine-learning/building-automating-managing-and-scaling-ml-workflows-using-amazon-sagemaker-pipelines/)
  - [Create Amazon SageMaker projects using third-party source control and Jenkins](https://aws.amazon.com/blogs/machine-learning/create-amazon-sagemaker-projects-using-third-party-source-control-and-jenkins/)
  - [Build MLOps workflows with Amazon SageMaker projects, GitLab, and GitLab pipelines](https://aws.amazon.com/blogs/machine-learning/build-mlops-workflows-with-amazon-sagemaker-projects-gitlab-and-gitlab-pipelines/)
  - [MLOps with MLFlow and Amazon SageMaker Pipelines](https://towardsdatascience.com/mlops-with-mlflow-and-amazon-sagemaker-pipelines-33e13d43f238)
  - [Scaling MLOps with resilient pipelines](https://towardsdatascience.com/i-tried-scaling-sagemaker-pipeline-executions-and-this-happened-31279b92821e)
- ### Model Registry
  - [Managing your machine learning lifecycle with MLflow and Amazon SageMaker](https://aws.amazon.com/blogs/machine-learning/managing-your-machine-learning-lifecycle-with-mlflow-and-amazon-sagemaker/)
- ### Model Monitoring
- ### Explainability & Bias Detection
  - [Build trustworthy ML detection and monitor bias in ML models](https://www.youtube.com/watch?v=6BZropfX6hA)

<a name="advanced-topics"></a>
## Advanced Topics
- ### Large Scale Data Processing
  - [Using Apache Spark on Amazon EMR with SageMaker](https://www.youtube.com/watch?v=RxRENYQBxZU)
  - [Spark in Processing Jobs](https://sagemaker.readthedocs.io/en/stable/amazon_sagemaker_processing.html#data-processing-with-spark)
- ### Distributed Training
  - [Choose the best data source for your Amazon SageMaker training job](https://aws.amazon.com/blogs/machine-learning/choose-the-best-data-source-for-your-amazon-sagemaker-training-job/)
  - [Scalable Medical Computer Vision Model Training - Part 1](https://aws.amazon.com/blogs/industries/scalable-medical-computer-vision-model-training-with-amazon-sagemaker-part-1/) and [Part 2](https://aws.amazon.com/blogs/industries/scalable-medical-computer-vision-model-training-with-amazon-sagemaker-part-2)
- ### Hardware Acceleration
- ### Edge Deployments
  - [Industrial defect detection with computer vision using Amazon SageMaker ](https://www.youtube.com/watch?v=v6OHL3LTjkA)
  - [ML@Edge with SageMaker Edge Manager](https://github.com/aws-samples/amazon-sagemaker-edge-manager-workshop)
  - [Using Amazon SageMaker Edge Manager and AWS IoT Greengrass V2](https://aws.amazon.com/blogs/machine-learning/build-machine-learning-at-the-edge-applications-using-amazon-sagemaker-edge-manager-and-aws-iot-greengrass-v2/)
- ### Feature Store

<a name="enterprise-architecture"></a>
## Enterprise & Architecture
- ### Architecture Best Practices
  - [Architecture Best Practices for Machine Learning](https://aws.amazon.com/architecture/machine-learning/)
  - [AWS Well-Architected Machine Learning Lens](https://aws.amazon.com/blogs/architecture/introducing-the-new-aws-well-architected-machine-learning-lens/)
- ### ML Platform Setup
  - [Setting up secure, well-governed machine learning environments on AWS](https://aws.amazon.com/blogs/mt/setting-up-machine-learning-environments-aws/)
  - [Enabling self-service provisioning of Amazon SageMaker Studio resources](https://towardsdatascience.com/enabling-self-service-provisioning-of-amazon-sagemaker-studio-resources-7ac017925016)
  - [Industrializing an ML platform with Amazon SageMaker Studio](https://towardsdatascience.com/industrializing-an-ml-platform-with-amazon-sagemaker-studio-91b597802afe)
  - [Scaling Enterprise ML Platforms with Modern Cloud Operations](https://towardsdatascience.com/scaling-enterprise-mlops-delivery-with-modern-cloud-operations-6888d7218be5)
  - [AccessSageMaker Studio via an external identity provider](https://www.youtube.com/watch?v=9CnFrSqvXYM)
- ### Security
  - [Security in Amazon SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/security.html)
  - [Dive deep into Amazon SageMaker Studio Notebooks architecture](https://aws.amazon.com/blogs/machine-learning/dive-deep-into-amazon-sagemaker-studio-notebook-architecture/)

<a name="training-certification"></a>
## Training & Certification
- ### MOOCs
  - [Getting Started with AWS Machine Learning](https://www.coursera.org/learn/aws-machine-learning)
  - [Practical Data Science on the AWS Cloud Specialization](https://www.coursera.org/specializations/practical-data-science)
  - [Machine Learning University](https://aws.amazon.com/machine-learning/mlu/)
- ### Digital & Classroom
  - [AWS Certified Machine Learning - Specialty](https://aws.amazon.com/certification/certified-machine-learning-specialty/)
  - [Machine Learning Learning Plan](https://explore.skillbuilder.aws/learn/public/learning_plan/view/28/machine-learning-learning-plan)
  - [AWS Classroom Training](https://aws.amazon.com/training/classroom/?nc2=sb_tr_ct)
- ### Tutorials
  - [AWS hands-on tutorials](https://aws.amazon.com/getting-started/hands-on/?getting-started-all.sort-by=item.additionalFields.sortOrder&getting-started-all.sort-order=asc&awsf.getting-started-category=category%23machine-learning&awsf.getting-started-level=*all&awsf.getting-started-content-type=*all)

<a name="community"></a>
## Community
- [Amazon SageMaker Fridays](https://pages.awscloud.com/SageMakerFridays)
- [AWS Machine Learning Blog](https://aws.amazon.com/blogs/machine-learning/category/artificial-intelligence/sagemaker/)
- [AWS ML School](https://mlschool.splashthat.com/?sc_channel=sm&sc_campaign=Machine_Learning&sc_publisher=LINKEDIN&sc_geo=GLOBAL&sc_outcome=awareness&trk=machine_learning)
- [AWS events](https://aws.amazon.com/events/)
- [AWS re:Post](https://repost.aws/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/amazon-sagemaker)

<a name="books"></a>
## Books
- [Learn Amazon SageMaker: A guide to building, training, and deploying machine learning models for developers and data scientists, 2nd Edition](https://www.amazon.co.uk/Learn-Amazon-SageMaker-developers-scientists/dp/1801817952/ref=sr_1_1?crid=1BK45HRK8T7SE&keywords=sagemaker&qid=1657373160&sprefix=sagemake%2Caps%2C235&sr=8-1)

<a name="news"></a>
## News
- [What's New with Machine Learning?](https://aws.amazon.com/about-aws/whats-new/machine-learning/?whats-new-content.sort-by=item.additionalFields.postDateTime&whats-new-content.sort-order=desc&awsf.whats-new-products=general-products%23amazon-sagemaker)

<a name="contributions" /></a>
## Contributions
Maintainers 
- [Sofian Hamiti](https://github.com/SofianHamiti)
