## IMP SETUP COMMANDS

  aws configure
  
  aws eks --region us-east-1 describe-cluster --name demoCluster --query cluster.status

  aws eks --region us-east-1 update-kubeconfig --name demoCluster
