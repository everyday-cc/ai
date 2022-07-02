---
category: news
title: "Secure Amazon SageMaker Studio presigned URLs Part 2: Private API with JWT authentication"
excerpt: "In part 1 of this series, we demonstrated how to resolve an Amazon SageMaker Studio presigned URL from a corporate network using Amazon private VPC endpoints without traversing the internet.&nbsp;In this post, we will continue to build on top of the previous solution to demonstrate how to build a private"
publishedDateTime: 2022-06-30T19:35:56Z
originalUrl: "https://aws.amazon.com/blogs/machine-learning/secure-amazon-sagemaker-studio-presigned-urls-part-2-private-api-with-jwt-authentication/"
webUrl: "https://aws.amazon.com/blogs/machine-learning/secure-amazon-sagemaker-studio-presigned-urls-part-2-private-api-with-jwt-authentication/"
type: article
quality: 60
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

related:
  - title: "Semantic segmentation data labeling and model training using Amazon SageMaker"
    excerpt: "In computer vision, semantic segmentation is the task of classifying every pixel in an image with a class from a known set of labels such that pixels with the same label share certain characteristics. It generates a segmentation mask of the input images. For example, the following images show a segmentation"
    publishedDateTime: 2022-06-28T16:22:22Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/semantic-segmentation-data-labeling-and-model-training-using-amazon-sagemaker/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 101
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2022/06/28/semantic-segmentation-sagemaker.jpg"
        width: 1996
        height: 998
        isCached: true
  - title: "Deep demand forecasting with Amazon SageMaker"
    excerpt: "Every business needs the ability to predict the future accurately in order to make better decisions and give the company a competitive advantage. With historical data, businesses can understand trends, make predictions of what might happen and when, and incorporate that information into their future"
    publishedDateTime: 2022-06-28T16:12:34Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/deep-demand-forecasting-with-amazon-sagemaker/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 89
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2022/06/20/Demandforecast-V2.png"
        width: 895
        height: 314
        isCached: true
  - title: "Use a custom image to bring your own development environment to RStudio on Amazon SageMaker"
    excerpt: "RStudio on Amazon SageMaker is the industry’s first fully managed RStudio Workbench in cloud. You can quickly launch the familiar RStudio integrated development environment (IDE), and dial up and down the underlying compute resources without interrupting your work, making it easy to build machine learning"
    publishedDateTime: 2022-06-29T22:04:49Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/use-a-custom-image-to-bring-your-own-development-environment-to-rstudio-on-amazon-sagemaker/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 79
    images:
      - url: "https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2022/06/29/Featured-images-for-ml9305.jpg"
        width: 800
        height: 400
        isCached: true
  - title: "Secure Amazon SageMaker Studio presigned URLs Part 1: Foundational infrastructure"
    excerpt: "You can access Amazon SageMaker Studio notebooks from the Amazon SageMaker console via AWS Identity and Access Management (IAM) authenticated federation from your identity provider (IdP), such as Okta. When a Studio user opens the notebook link, Studio validates the federated user’s IAM policy to authorize"
    publishedDateTime: 2022-06-30T19:36:21Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/secure-amazon-sagemaker-studio-presigned-urls-part-1-foundational-infrastructure/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 64
  - title: "New built-in Amazon SageMaker algorithms for tabular data modeling: LightGBM, CatBoost, AutoGluon-Tabular, and TabTransformer"
    excerpt: "Amazon SageMaker provides a suite of built-in algorithms, pre-trained models, and pre-built solution templates to help data scientists and machine learning (ML) practitioners get started on training and deploying ML models quickly. You can use these algorithms and models for both supervised and unsupervised"
    publishedDateTime: 2022-06-28T18:13:02Z
    webUrl: "https://aws.amazon.com/blogs/machine-learning/new-built-in-amazon-sagemaker-algorithms-for-tabular-data-modeling-lightgbm-catboost-autogluon-tabular-and-tabtransformer/"
    type: article
    provider:
      name: AWS
      domain: aws.amazon.com
    quality: 42

secured: "6P2gcxgLMAdwA/uzdLhtbis2i/NI6ynZW+x4ft1zcibOh77PkHDMvPqUllC1x8nqdlkiW8LhItF1UvjYocyHlgPrj+whfBcmHrY6g+HIbyyibhKymqUASCu0Dc/UVCU/XPi1jirmN06qfB/5rCuMy+BwyPrdgLuxHbPEutGROz9D0zJDIS8lZaWO47c5VkcQ57rbC5BlHN9vMxA0auCA7jut2KPjkh6TRc9SgsAvHjIwNOn62B0QXNDEQLCoSW8iTmmsoyHIG5fv0E+AtFCql1C1SLM5vjYjDfZXDO4e/X0/1YLE7+8z9X+uJ+bGSZREFY3F2KQJvzmzUm1QgdEyH2iwy4JOCsqEeM7xZR3QkvI=;o0TkQnVP36xQjvETtf0pBA=="
---

