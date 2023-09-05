---
category: news
title: "How Carrier predicts HVAC faults using AWS Glue and Amazon SageMaker"
excerpt: "In this post, we show how the Carrier and AWS teams applied ML to predict faults across large fleets of equipment using a single model. We first highlight how we use AWS Glue for highly parallel data processing. We then discuss how Amazon SageMaker helps us with feature engineering and building a scalable"
publishedDateTime: 2023-09-05T17:25:12Z
originalUrl: "https://aws.amazon.com/blogs/machine-learning/how-carrier-predicts-hvac-faults-using-aws-glue-and-amazon-sagemaker/"
webUrl: "https://aws.amazon.com/blogs/machine-learning/how-carrier-predicts-hvac-faults-using-aws-glue-and-amazon-sagemaker/"
type: article
quality: 104
heat: 134
published: true

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
  - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2023/09/05/featured-images-ML-12208-1120x630.jpg"
    width: 1120
    height: 630
    isCached: true

related:
  - title: "Build a generative AI-based content moderation solution on Amazon SageMaker JumpStart"
    excerpt: "In this post, we introduce a novel method to perform content moderation on image data with multi-modal pre-training and a large language model (LLM). With multi-modal pre-training, we can directly query the image content based on a set of questions of interest and the model will be able to answer these"
    publishedDateTime: 2023-09-05T17:38:57Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/build-a-generative-ai-based-content-moderation-solution-on-amazon-sagemaker-jumpstart/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 97
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2023/09/05/featured-images-ML-14979-1120x630.jpg"
        width: 1120
        height: 630
        isCached: true
  - title: "Elevating the generative AI experience: Introducing streaming support in Amazon SageMaker hosting"
    excerpt: "We’re excited to announce the availability of response streaming through Amazon SageMaker real-time inference. Now you can continuously stream inference responses back to the client when using SageMaker real-time inference to help you build interactive experiences for generative AI applications such"
    publishedDateTime: 2023-09-01T16:53:42Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/elevating-the-generative-ai-experience-introducing-streaming-support-in-amazon-sagemaker-hosting/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 91
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2023/08/31/featured-images-ML-15289-1120x630.jpg"
        width: 1120
        height: 630
        isCached: true
  - title: "Optimize deployment cost of Amazon SageMaker JumpStart foundation models with Amazon SageMaker asynchronous endpoints"
    excerpt: "In this post, we target these situations and solve the problem of risking high costs by deploying large foundation models to Amazon SageMaker asynchronous endpoints from Amazon SageMaker JumpStart. This can help cut costs of the architecture, allowing the endpoint to run only when requests are in the"
    publishedDateTime: 2023-09-05T17:13:21Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/optimize-deployment-cost-of-amazon-sagemaker-jumpstart-foundation-models-with-amazon-sagemaker-asynchronous-endpoints/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 66
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2023/09/05/featured-images-ML-14973-1120x630.jpg"
        width: 1120
        height: 630
        isCached: true

secured: "VIqW4J7EqVwDBK+ojMJAJPmB5nZH5MQQu1SP4rXJrVIgF12tlIfXcCur6rIZ+BRf4AM47LH7nyFHc5GtSGLcmHi+ukBtbwPjCC2dSaa3aUgjr8RUxbUBEkDTMfO0GZm8PUwx1jrHbqmXxdQUgzoMBcNojfxoV6VsU+sKw0ZBKfMTWyDRrbOBi4ajcR/nfb0GRH/TN9NsoYhgSYelzROzgJIZ9i7+M7slml0mk2Z/nnmkbiDtcPnyzta0DIG3wkkIa1bblWGkLezVz3gaAzmbLah+hfiio1X3LHv3QqQ+MOQ34pdJ27hGvizn2HTT4lXuLl+QP0w1Yr9A6dQD5AapvqqYA1DNF8V00XBYrHLFhtg=;yM5TyJEjL8EeQyNkrT3SZg=="
---

