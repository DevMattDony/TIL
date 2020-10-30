### Microsoft Azure 핵심 서비스 구분(AZ-900)																						Date: 30th Sep 2020	

#  Identify Azure solutions

## Learning objectives 

> - Explore the many different Azure solutions.



## Define Internet of Things

- __IoT Central__
  - IoT Central is a fully managed global IoT software as a service (SaaS) solution that makes it easy to connect, monitor, and mange your IoT assets at scale.
  - You can bring your connected products to market faster while staying focused on your customers.

- __Azure IoT Hub__
  - Azure IoT Hub is a managed service hosted in the cloud that acts as a central message hub for bi-directional communication between your IoT application and the devices it manages.
  - You can use Azure IoT Hub to build IoT solutions with reliable and secure communications between millions of IoT devices and a cloud-hosted solution backend. You can connect virtually any device to your IoT Hub.



## Explore big data nad analytics

- __Azure Synapse Analytics (formerly Azure SQL Data Wharehouse)__
  - Azure Synapse Analytics is a limitless analytics service that brings together enterprise data warehousing and big data analytics.

- __Azure HDInsight__
  - Azure HDInsight is as fully managed, open-source analytics for enterprises. It is a cloud service that makes it easier, faster, and more cost-effective to process massive amounts of data.
  - HDInsight allows you to run popular open-source frameworks and create cluster types such as Apache Spark, Apache Hadoop, Apache Kafka, Apche HBase, Apache Storm, Machine Learning Services.
  - HDInsight also supports a broad range of scenarios such as ETL, data warehousing, machine learning and IoT.

- __Azure Data Lake Analytics__
  - Azure Data Lake Analytics is an on-demand analytics job service that simplifies big data.
  - Instead of deploying, configuring, and tuning hardware, you write queries to transform your data and extract valuable insights.
  - You only pay for your job when it is running, making it more cost-effective.



## Explore artificial intelligence

- __Azure Cognitive Services__
  - Cognitive services are a collection of domain-specific pre-trained AI models that can be customized with your data.
  - They are categorized broadly into vision, speech, language, and search.
    - __Vision__ : Vision makes it possible for apps and services to accurately identify and analyze content within images and videos.
    - __Speech__ : Speech services can convert spoken language into text or produce natural-sounding speech from text using standard (or customizable) voice fonts.
    - __Language__ : Language service can understand the meaning of unstructured text or recognize the speaker's intent.
    - __Knowledge__ : Knowledge services create rich knowledge resources that integrate into apps and services.
    - __Search__ : Enable apps and services to harness the power of a web-scale, ad-free search engine. Use search services to find information across billions of web pages, images, videos, and news search results.

- __Azure Machine Learning Service__
  - The Azure Machine Learning service provides a cloud-base environment you can use to develop, train, test, deploy, manage, and track machine learning models.
  - It fully supports oepn-source technologies, so you can use tens of thousands of open-source Python packages with machine learning components such as _TensorFlow_ and _scikit-learn_.



## Define serverless computing

> Serverless computing is a cloud-hosted execution environment that runs your code but abstracts the underlying hosting environment.

- __Azure Functions__
  - Azure Functions are ideal when you're only concerned with the code running your service and not the underlying platform or infrastructure.
  - Azure Functions are commonly used when you need to perform work in response to an event and when that work can be completed quickly, within seconds or less.
  - Azure Functions scale automatically, and charges accrue only when a function is triggered, so they're a solid choice when demand is variable.

- __Azure Logic Apps__
  - Logic Apps is a cloud service that helps you automate and orchestrate tasks, business processes, and workflows when you need to integrate apps, data, systems, and services across enterprises or organizations.

- __Azure Event Grid__
  - Event Grid allows you to easily build applications with event-based architectures. It's fully managed, intelligent event routing service that uses a publish-subscribe model for uniform event consumption.
  - Event Grid has built-in support for events coming from Azure services, such as storage blobs and resource groups.
  - You can use Event Grid to support your own non-Azure-based events in near-real time, using custom topics.



## Explore DevOps

- __Azure Lab Services (formerly Azure DevOps Test)__
  - Lab Services is a service that helps developers and testers quickly create environments in Azure, while minimizing waste and controlling cost.



## Exlpore Azure App Service

- __Key features of Azure App Services__
  - __Multiple languages and frameworks__ : App Service has first-class support for ASP.NET, ASP.NET Core, Java, Ruby, Node.js, PHP or Pyhton. You can also run PowerShell and other scripts or executables as background services.
  - __DevOps optimization__ : Set up continuous integration and deployment with Azure DevOps, GitHub, BitBucket, Docker Hub, or Azure Container Registry. Promote updates through test and staging environments. Manage your apps in App Service by CLI.
  - __Global scale with high availability__ : Scale up or out manually or automatically. Host your apps anywhere in Microsoft's global datacenter infrastructure, and the App Service SLA promises high availability.
  - __Connections to SaaS platforms and on-premises data__ : Choose from more than 50 connectors for enterprise systmes (such as SAP), SaaS services (such as Salesforce), and internet services(such as Facebook). Access on-premises data using Hybrid Connections and Azure Virtual Networks.
  - __Security and compliance__ : App Service is ISO, SOC, and PCI compliant. Authenticate users with Azure Active Directory or with social login (Google, Facebook, Twitter, and Microsft). Create IP address restrictions and manage service identities.
  - __Application templates__ : Choose from an extensive list of application templates in the Azure Marketplace, such as WordPress, Joomla, and Drupal.
  - __Visual Studio intergration__ : Dedicated tools in Visual Studio streamline the work of creating, deploying, and debugging.
  - __API and mobile features__ : App Service provides turn-key CORS soupport for RESTful API scenarios, and simplifies mobile app scenarios by enabling authentication, offline data sync, push notifications, and more.
  - __Serverless code__ : Run a code snippet or script on-demand without having to explicitly provision or manage infrastructure and pay only for the compute time your code actually uses.

