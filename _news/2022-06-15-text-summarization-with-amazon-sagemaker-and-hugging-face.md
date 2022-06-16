---
category: news
title: "Text summarization with Amazon SageMaker and Hugging Face"
excerpt: "In this post, we show you how to implement one of the most downloaded Hugging Face pre-trained models used for text summarization, DistilBART-CNN-12-6, within a Jupyter notebook using Amazon SageMaker and the SageMaker Hugging Face Inference Toolkit. Based on the steps shown in this post, you can try"
publishedDateTime: 2022-06-15T20:24:32Z
originalUrl: "https://aws.amazon.com/blogs/machine-learning/text-summarization-with-amazon-sagemaker-and-hugging-face/"
webUrl: "https://aws.amazon.com/blogs/machine-learning/text-summarization-with-amazon-sagemaker-and-hugging-face/"
type: article
quality: 89
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
  - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2022/06/15/text-summarization-sagemaker.jpg"
    width: 1246
    height: 626
    isCached: true

related:
  - title: "Create, train, and deploy a billion-parameter language model on terabytes of data with TensorFlow and Amazon SageMaker"
    excerpt: "The increasing size of language models has been one of the biggest trends in natural language processing (NLP) in recent years. Since 2018, we’ve seen unprecedented development and deployment of ever-larger language models, including BERT and its variants, GPT-2, T-NLG, and GPT-3 (175 billion parameters)."
    publishedDateTime: 2022-06-13T17:36:17Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/create-train-and-deploy-a-billion-parameter-language-model-on-terabytes-of-data-with-tensorflow-and-amazon-sagemaker/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 114
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2022/06/13/billion-parameter-sagemaker.jpg"
        width: 1247
        height: 621
        isCached: true
  - title: "Prepare data faster with PySpark and Altair code snippets in Amazon SageMaker Data Wrangler"
    excerpt: "Amazon SageMaker Data Wrangler is a purpose-built data aggregation and preparation tool for machine learning (ML). It allows you to use a visual interface to access data and perform exploratory data analysis (EDA) and feature engineering. The EDA feature comes with built-in data analysis capabilities"
    publishedDateTime: 2022-06-15T21:27:42Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/prepare-data-faster-with-pyspark-and-altair-code-snippets-in-amazon-sagemaker-data-wrangler/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 94
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2022/06/15/prepare-data-faster.jpg"
        width: 1246
        height: 622
        isCached: true
  - title: "Extract insights from SAP ERP with no-code ML solutions with Amazon AppFlow and Amazon SageMaker Canvas"
    excerpt: "Customers in industries like consumer packaged goods, manufacturing, and retail are always looking for ways to empower their operational processes by enriching them with insights and analytics generated from data. Tasks like sales forecasting directly affect operations such as raw material planning,"
    publishedDateTime: 2022-06-15T21:08:00Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/extract-insights-from-sap-erp-with-no-code-ml-solutions-with-amazon-appflow-and-amazon-sagemaker-canvas/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 90
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2022/06/15/extract-insights-sap.jpg"
        width: 1247
        height: 626
        isCached: true
  - title: "How Mantium achieves low-latency GPT-J inference with DeepSpeed on Amazon SageMaker"
    excerpt: "Mantium is a global cloud platform provider for building AI applications and managing them at scale. Mantium’s end-to-end development platform enables enterprises and businesses of all sizes to build AI applications and automation faster and easier than what has been traditionally possible. With Mantium,"
    publishedDateTime: 2022-06-15T23:08:28Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/how-mantium-achieves-low-latency-gpt-j-inference-with-deepspeed-on-amazon-sagemaker/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 83
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2022/06/15/low-latency-mantium.jpg"
        width: 1247
        height: 623
        isCached: true

secured: "xagf+t8d34t5YgsClwZnx+a4OEoCT+RjJK7ArGrn4gNfgdUmN6nCLX785pbLXkzvm+lGXZHFyW+JwPTZfmD7a4AK084u8gRE2d5KVZWntN8SHaV+UNWKBnErqfbhtV0zxD0uHCiBlD52s6KkgvzBiE0LiGicoCbwChE2BSgPj+BavsFsFbF/+y5NPw45oSJtOcuGwq2mkFJmeHUiGBLJJVWK5QUauDcPJsTPotVa7q5CJGnOc2CiRAhyTMdtkUvuHkOdAAaccYD3Pke5oxACFcWI4zgfVYgQHpVRHPOFPiHy12Y4ZBFocP/MalP1rSZl3gwmMTBpWnLL5j0UrfuxMo0o5iYvsLy5QDfaF4R/UXk=;fNJyCCud/EMLv1QDMKvhhg=="
---

