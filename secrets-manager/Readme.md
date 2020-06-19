# How to run

## Secrets Manager
```

aws cloudformation create-stack --stack-name secrets-manager --template-body file://secrets-manager.yaml \
--parameters ParameterKey=Var1,ParameterValue=Value1 ParameterKey=Var2,ParameterValue=Value2 --profile blablabla
aws cloudformation delete-stack --stack-name secrets-manager --profile blablabla


```







