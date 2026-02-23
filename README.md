## IMP SETUP COMMANDS

  aws configure
  
  aws eks --region us-west-2 describe-cluster --name hksCluster --query cluster.status

  aws eks --region us-west-2 update-kubeconfig --name hksCluster
