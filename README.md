
# No Image Build Code Runtime Project

### This project shows how you can have software running on kubernetes that does not require the traditional
### image build process.


# How to run

Apply kubectl

`kubectl apply -k .`

Port forward
`kubectl port-forward deployment/nodejs-deployment 3000:3000`