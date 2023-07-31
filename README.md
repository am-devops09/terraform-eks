aws eks describe-cluster --name demo --query cluster.identity.oidc.issuer --output text


kubectl describe sa aws-test

kubectl config view --minify

kubectl auth can-i get pods

kubectl auth can-i create pods

kubectl run nginx --image=nginx

aws iam get-role --profile am-devops1 --role-name eks-admin

aws sts assume-role --role-arn arn000000000000 --role-session-name manager-session --profile manager