---
name: AWS EC2 Container Service
description: Amazon EC2 Container Service (ECS) is a highly scalable, high performance
  container management service that supports Docker containers and allows you to easily
  run applications on a managed cluster of Amazon EC2 instances. Amazon ECS eliminates
  the need for you to install, operate, and scale your own cluster management infrastructure.
  With simple API calls, you can launch and stop Docker-enabled applications, query
  the complete state of your cluster, and access many familiar features like security
  groups, Elastic Load Balancing, EBS volumes, and IAM roles. You can use Amazon ECS
  to schedule the placement of containers across your cluster based on your resource
  needs and availability requirements. You can also integrate your own scheduler or
  third-party schedulers to meet business or application specific requirements.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Deployment
- Containers
- Amazon Web Services
created: "2018-03-13"
modified: "2018-03-13"
url: https://raw.githubusercontent.com/streamdata-gallery/container/master/_listings/aws-ec2-container-service/apis.yaml
specificationVersion: "0.14"
apis:
- name: Amazon EC2 Container Service API
  description: Amazon EC2 Container Service (ECS) is a highly scalable, high performance
    container management service that supports Docker containers and allows you to
    easily run applications on a managed cluster of Amazon EC2 instances
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: ""
  baseURL: :///
  tags: Container
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery/container/master/_listings/aws-ec2-container-service/action-describecontainerinstances-get.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonECS/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/ecs/faqs/
- type: x-getting-started
  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html
- type: x-pricing
  url: https://aws.amazon.com/ecs/pricing/
- type: x-website
  url: https://aws.amazon.com/ecs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---