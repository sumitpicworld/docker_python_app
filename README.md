# docker_python_app

# AWS Configure: https://docs.aws.amazon.com/cli/latest/reference/configure/


<br>
eksctl installation 
<br>
curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp
<br>
sudo mv /tmp/eksctl /usr/local/bin
<br>
eksctl version


 <br>

 
 eks cluster
 <br>
 eksctl create cluster --name eksctl-test --nodegroup-name ng-defaulf --node-type t3.micro --nodes 2
 <br>
 kubectl get all

 <br>
 kubectl installation 
 <br>

 https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html
 
