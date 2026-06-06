## EKS Cluster Connecting COmmands
  aws eks --region ap-south-1 describe-cluster --name hiteshCluster --query cluster.status
  
  aws eks --region ap-south-1 update-kubeconfig --name hiteshCluster
