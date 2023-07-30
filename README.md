aws eks describe-cluster --name demo --query cluster.identity.oidc.issuer --output text


kubectl describe sa aws-test