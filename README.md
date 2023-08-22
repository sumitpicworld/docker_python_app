# docker_python_app

# AWS Configure: https://docs.aws.amazon.com/cli/latest/reference/configure/


<br>
eksctl installation 
curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp
sudo mv /tmp/eksctl /usr/local/bin
eksctl version
 <br>
 eks cluster
 eksctl create cluster --name eksctl-test --nodegroup-name ng-defaulf --node-type t3.micro --nodes 2
 kubectl get all

 <br>
 kubectl installation 

 https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html
 
