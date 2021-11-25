# try-configure-aws-credentials

[aws-actions/configure-aws-credentials](https://github.com/aws-actions/configure-aws-credentials) を試す。


## IAM Role 作成

```
rain deploy github-oidc-role.cfn.yaml github-oidc-role \ 
    --yes \
    --params GitHubOrg=oppara,RepositoryName=try-configure-aws-credentials,OIDCProviderArn=""
```
