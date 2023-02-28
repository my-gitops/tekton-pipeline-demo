### Tekton pipeline demo
1. apply prereource folder yaml files, credentials.yaml only local test, please update yours
2. apply tests folder yaml files
3. apply pipelines folder yaml files
4. create pipelineruns folder yaml files, you should update some params.

#################################################################################################
pullcode ------> go test -------------> go build ------------> kaniko package image and push registry


###################################################################################
test go code repo:  