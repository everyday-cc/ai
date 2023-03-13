---
category: news
title: "Using Amazon SageMaker with Point Clouds: Part 1- Ground Truth for 3D labeling"
excerpt: "In this two-part series, we demonstrate how to label and train models for 3D object detection tasks. In part 1, we discuss the dataset we’re using, as well as any preprocessing steps, to understand and label data. In part 2, we walk through how to train a model on your dataset and deploy it to […]"
publishedDateTime: 2023-03-10T18:20:54Z
originalUrl: "https://aws.amazon.com/blogs/machine-learning/using-amazon-sagemaker-with-point-clouds-part-1-ground-truth-for-3d-labeling/"
webUrl: "https://aws.amazon.com/blogs/machine-learning/using-amazon-sagemaker-with-point-clouds-part-1-ground-truth-for-3d-labeling/"
type: article
quality: 85
heat: -1
published: false

provider:
  name: AWS
  domain: aws.amazon.com
  images:
    - url: "https://everyday-cc.github.io/ai/assets/images/organizations/aws.amazon.com-50x50.jpg"
      width: 50
      height: 50

topics:
  - AI
  - AWS AI

images:
  - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2023/03/10/sagemaker-cloud-points-ground-truth.jpg"
    width: 1565
    height: 778
    isCached: true

related:
  - title: "Architect personalized generative AI SaaS applications on Amazon SageMaker"
    excerpt: "The AI landscape is being reshaped by the rise of generative models capable of synthesizing high-quality data, such as text, images, music, and videos. The course toward democratization of AI helped to further popularize generative AI following the open-source releases for such foundation model families"
    publishedDateTime: 2023-03-09T18:57:09Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/architect-personalized-generative-ai-saas-applications-on-amazon-sagemaker/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 102
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2023/03/06/ML-13166-arc-1-1120x630.png"
        width: 1120
        height: 630
        isCached: true
  - title: "Use a data-centric approach to minimize the amount of data required to train Amazon SageMaker models"
    excerpt: "As machine learning (ML) models have improved, data scientists, ML engineers and researchers have shifted more of their attention to defining and bettering data quality. This has led to the emergence of a data-centric approach to ML and various techniques to improve model performance by focusing on data"
    publishedDateTime: 2023-03-09T18:04:56Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/use-a-data-centric-approach-to-minimize-the-amount-of-data-required-to-train-amazon-sagemaker-models/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 89
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2023/03/09/data-centric-approach-sagemaker.jpg"
        width: 1565
        height: 781
        isCached: true
  - title: "Accelerate time to insight with Amazon SageMaker Data Wrangler and the power of Apache Hive"
    excerpt: "Amazon SageMaker Data Wrangler reduces the time it takes to aggregate and prepare data for machine learning (ML) from weeks to minutes in Amazon SageMaker Studio. Data Wrangler enables you to access data from a wide variety of popular sources (Amazon S3, Amazon Athena,&nbsp;Amazon Redshift, Amazon EMR"
    publishedDateTime: 2023-03-10T18:24:25Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/accelerate-time-to-insight-with-amazon-sagemaker-data-wrangler-and-the-power-of-apache-hive/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 79
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2023/03/10/accelerate-time-to-insights.jpg"
        width: 1565
        height: 779
        isCached: true
  - title: "Few-click segmentation mask labeling in Amazon SageMaker Ground Truth Plus"
    excerpt: "Amazon SageMaker Ground Truth Plus is a managed data labeling service that makes it easy to label data for machine learning (ML) applications. One common use case is semantic segmentation, which is a computer vision ML technique that involves assigning class labels to individual pixels in an image. For"
    publishedDateTime: 2023-03-13T18:36:45Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/few-click-segmentation-mask-labeling-in-amazon-sagemaker-ground-truth-plus/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 67
  - title: "UiPath Announces Integration with Amazon Sagemaker"
    excerpt: "UiPath, a leading enterprise automation software company, has announced data science teams using Amazon SageMaker, an"
    publishedDateTime: 2023-03-09T13:41:00Z
    webUrl: "https://www.datanami.com/this-just-in/uipath-announces-integration-with-amazon-sagemaker/"
    type: article
    provider:
      name: datanami.com
      domain: datanami.com
    quality: 39
    images:
      - url: "https://www.datanami.com/wp-content/uploads/2023/02/AI-North-America23.png"
        width: 1664
        height: 674
        isCached: true

secured: "Jz/v8Kux7GHkYaGH39S43mZW4tiegaCIzjF1aoFi/Wd8tH/V3WaHQm7+uZiRGyhUM2pGas7jj18lI5AWxGtsogClYPaFDIEVHA5UZUZ+mGGMcQydXxZXQP3Zs49QsR6VT3hQzi3ox2jPxta1vKnoSaMPNPXLKF6/M7JxWj3Ki9oR8brmRMk82oSF0gg15ZY58VaLTnDAnBBqu929wpkqX1os1+VqQnQsLxZoDxW0Z7UW/uLsjsecshheoStPjMsmQ6/ho2firbU6Dmnjp9jFKEg56Nu10Z0gY4ZCEjT3uRzYE9y3VhCuC/B6HK2h1j9A9D1SN4PJTAOuShnK0myDsbCOxrGa8AdgqAHC4N7BtHE=;ahDw5u2TBbPG+c7pQfN0vQ=="
---

