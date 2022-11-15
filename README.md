# aws-eks
A Terraform module to deploy an EKS cluster with AWS



```bash
node_groups = [
  {
    name    = "eks-ng-1",
    desired = 1,
    max     = 1,
    min     = 1
  },
  {
    name    = "eks-ng-2",
    desired = 1,
    max     = 1,
    min     = 1
  }
]


  default = [ {
    deletion_window_in_days = 
    enable_key_rotation = 1
    key_alias = "value"
  } ]
```