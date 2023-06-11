# ecs-ec2-cost-split
AWS Cloud Financial Management team recently added feature to provide task level cost allocation both for used and unused resources. Check out [the announcement blog](https://aws.amazon.com/blogs/aws-cloud-financial-management/la-improve-cost-visibility-of-containerized-applications-with-aws-split-cost-allocation-data-for-ecs-and-batch-jobs/) for feature details.

Assuming you have done the following steps
* [Enabled split-cost-allocation](https://docs.aws.amazon.com/cur/latest/userguide/enabling-split-cost-allocation-data.html)
* [Enabled ECS Managed Tags and Enabled Propagate Tags](https://docs.aws.amazon.com/AmazonECS/latest/APIReference/API_CreateService.html) - `enableECSManagedTags:TRUE` and `propagateTags:SERVICE`
* [Activated ECS managed tags for cost allocation tags](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/activate-built-in-tags.html)

This repository provides [Jypter NoteBook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/) for analyzing split cost per service. Check out docs to install jupyter.
```bash
git clone 
```
