aws eks describe-cluster --name demo --query cluster.identity.oidc.issuer --output text


kubectl describe sa aws-test

kubectl config view --minify

kubectl auth can-i get pods