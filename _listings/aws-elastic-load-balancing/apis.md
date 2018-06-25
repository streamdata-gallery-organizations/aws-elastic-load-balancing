---
name: AWS Elastic Load Balancing
x-slug: aws-elastic-load-balancing
description: Elastic Load Balancing automatically distributes incoming application
  traffic across multiple Amazon EC2 instances. It enables you to achieve fault tolerance
  in your applications, seamlessly providing the required amount of load balancing
  capacity needed to route application traffic.Elastic Load Balancing offers two types
  of load balancers that both feature high availability, automatic scaling, and robust
  security. These include theClassic Load Balancerthat routes traffic based on either
  application or network level information, and theApplication Load Balancerthat routes
  traffic based on advanced application level information that includes the content
  of the request. The Classic Load Balancer is ideal for simple load balancing of
  traffic across multiple EC2 instances, while the Application Load Balancer is ideal
  for applications needing advanced routing capabilities, microservices, and container-based
  architectures. Application Load Balancer offers ability to route traffic to multiple
  services or load balance across multiple ports on the same EC2 instance.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Elastic Load Balancing
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Elastic Load Balancing API Add Tags
  x-api-slug: aws-elastic-load-balancing-api
  description: Adds the specified tags to the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=AddTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionaddtags-get-openapi.md
- name: AWS Elastic Load Balancing API Create Listener
  x-api-slug: aws-elastic-load-balancing-api
  description: Creates a listener for the specified Application Load Balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=CreateListener
  tags: Listeners
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actioncreatelistener-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actioncreatelistener-get-openapi.md
- name: AWS Elastic Load Balancing API Create Load Balancer
  x-api-slug: aws-elastic-load-balancing-api
  description: Creates an Application Load Balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=CreateLoadBalancer
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actioncreateloadbalancer-get-openapi.md
- name: AWS Elastic Load Balancing API Create Rule
  x-api-slug: aws-elastic-load-balancing-api
  description: Creates a rule for the specified listener.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=CreateRule
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actioncreaterule-get-openapi.md
- name: AWS Elastic Load Balancing API Create Target Group
  x-api-slug: aws-elastic-load-balancing-api
  description: Creates a target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=CreateTargetGroup
  tags: Target Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actioncreatetargetgroup-get-openapi.md
- name: AWS Elastic Load Balancing API Delete Listener
  x-api-slug: aws-elastic-load-balancing-api
  description: Deletes the specified listener.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DeleteListener
  tags: Listeners
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondeletelistener-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondeletelistener-get-openapi.md
- name: AWS Elastic Load Balancing API Delete Load Balancer
  x-api-slug: aws-elastic-load-balancing-api
  description: Deletes the specified Application Load Balancer and its attached listeners.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DeleteLoadBalancer
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondeleteloadbalancer-get-openapi.md
- name: AWS Elastic Load Balancing API Delete Rule
  x-api-slug: aws-elastic-load-balancing-api
  description: Deletes the specified rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DeleteRule
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondeleterule-get-openapi.md
- name: AWS Elastic Load Balancing API Delete Target Group
  x-api-slug: aws-elastic-load-balancing-api
  description: Deletes the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DeleteTargetGroup
  tags: Target Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondeletetargetgroup-get-openapi.md
- name: AWS Elastic Load Balancing API Deregister Targets
  x-api-slug: aws-elastic-load-balancing-api
  description: Deregisters the specified targets from the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DeregisterTargets
  tags: Targets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionderegistertargets-get-openapi.md
- name: AWS Elastic Load Balancing API Describe Listeners
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the specified listeners or the listeners for the specified
    Application Load Balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeListeners
  tags: Listeners
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribelisteners-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribelisteners-get-openapi.md
- name: AWS Elastic Load Balancing API Describe Load Balancer Attributes
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the attributes for the specified Application Load Balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeLoadBalancerAttributes
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribeloadbalancerattributes-get-openapi.md
- name: AWS Elastic Load Balancing API Describe Load Balancers
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the specified Application Load Balancers or all of your Application
    Load Balancers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeLoadBalancers
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribeloadbalancers-get-openapi.md
- name: AWS Elastic Load Balancing API Describe Rules
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the specified rules or the rules for the specified listener.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeRules
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescriberules-get-openapi.md
- name: AWS Elastic Load Balancing API Describe S S L Policies
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the specified policies or all policies used for SSL negotiation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeSSLPolicies
  tags: SSL Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribesslpolicies-get-openapi.md
- name: AWS Elastic Load Balancing API Describe Tags
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the tags for the specified resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribetags-get-openapi.md
- name: AWS Elastic Load Balancing API Describe Target Group Attributes
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the attributes for the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeTargetGroupAttributes
  tags: Target Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribetargetgroupattributes-get-openapi.md
- name: AWS Elastic Load Balancing API Describe Target Groups
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the specified target groups or all of your target groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeTargetGroups
  tags: Target Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribetargetgroups-get-openapi.md
- name: AWS Elastic Load Balancing API Describe Target Health
  x-api-slug: aws-elastic-load-balancing-api
  description: Describes the health of the specified targets or all of your targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=DescribeTargetHealth
  tags: Target Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribetargethealth-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actiondescribetargethealth-get-openapi.md
- name: AWS Elastic Load Balancing API Modify Listener
  x-api-slug: aws-elastic-load-balancing-api
  description: Modifies the specified properties of the specified listener.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=ModifyListener
  tags: Listeners
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionmodifylistener-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionmodifylistener-get-openapi.md
- name: AWS Elastic Load Balancing API Modify Load Balancer Attributes
  x-api-slug: aws-elastic-load-balancing-api
  description: Modifies the specified attributes of the specified Application Load
    Balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=ModifyLoadBalancerAttributes
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionmodifyloadbalancerattributes-get-openapi.md
- name: AWS Elastic Load Balancing API Modify Rule
  x-api-slug: aws-elastic-load-balancing-api
  description: Modifies the specified rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=ModifyRule
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionmodifyrule-get-openapi.md
- name: AWS Elastic Load Balancing API Modify Target Group
  x-api-slug: aws-elastic-load-balancing-api
  description: Modifies the health checks used when evaluating the health state of
    the targets in the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=ModifyTargetGroup
  tags: Target Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionmodifytargetgroup-get-openapi.md
- name: AWS Elastic Load Balancing API Modify Target Group Attributes
  x-api-slug: aws-elastic-load-balancing-api
  description: Modifies the specified attributes of the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=ModifyTargetGroupAttributes
  tags: Target Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionmodifytargetgroupattributes-get-openapi.md
- name: AWS Elastic Load Balancing API Register Targets
  x-api-slug: aws-elastic-load-balancing-api
  description: Registers the specified targets with the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=RegisterTargets
  tags: Targets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionregistertargets-get-openapi.md
- name: AWS Elastic Load Balancing API Remove Tags
  x-api-slug: aws-elastic-load-balancing-api
  description: Removes the specified tags from the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=RemoveTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionremovetags-get-openapi.md
- name: AWS Elastic Load Balancing API Set Rule Priorities
  x-api-slug: aws-elastic-load-balancing-api
  description: Sets the priorities of the specified rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=SetRulePriorities
  tags: Rule Priorities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionsetrulepriorities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionsetrulepriorities-get-openapi.md
- name: AWS Elastic Load Balancing API Set Security Groups
  x-api-slug: aws-elastic-load-balancing-api
  description: Associates the specified security groups with the specified load balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=SetSecurityGroups
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionsetsecuritygroups-get-openapi.md
- name: AWS Elastic Load Balancing API Set Subnets
  x-api-slug: aws-elastic-load-balancing-api
  description: Enables the Availability Zone for the specified subnets for the specified
    load balancer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: ://///?Action=SetSubnets
  tags: Subnets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionsetsubnets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/actionsetsubnets-get-openapi.md
- name: AWS Elastic Load Balancing API
  x-api-slug: aws-elastic-load-balancing-api
  description: Elastic Load Balancing automatically distributes incoming application
    traffic across multiple Amazon EC2 instances. It enables you to achieve fault
    tolerance in your applications, seamlessly providing the required amount of load
    balancing capacity needed to route application traffic.Elastic Load Balancing
    offers two types of load balancers that both feature high availability, automatic
    scaling, and robust security. These include theClassic Load Balancerthat routes
    traffic based on either application or network level information, and theApplication
    Load Balancerthat routes traffic based on advanced application level information
    that includes the content of the request. The Classic Load Balancer is ideal for
    simple load balancing of traffic across multiple EC2 instances, while the Application
    Load Balancer is ideal for applications needing advanced routing capabilities,
    microservices, and container-based architectures. Application Load Balancer offers
    ability to route traffic to multiple services or load balance across multiple
    ports on the same EC2 instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: AWS Elastic Load Balancing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-load-balancing/master/_listings/aws-elastic-load-balancing/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/elbv2/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/pricing/
- type: x-website
  url: https://aws.amazon.com/elasticloadbalancing/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---