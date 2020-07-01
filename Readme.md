# Opencast Operator for Kubernetes/Openshift

## Notes

For deployment on openshift you need an extra scc for deploying Elasticsearch :

'''
oc adm policy  add-scc-to-user privileged system:serviceaccount:*NAMESPACE*:default
'''