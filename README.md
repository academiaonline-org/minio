# minio

```
github_hostname=github.com
github_username=academiaonline
github_reponame=minio
github_branch=main

git clone https://${github_hostname}/${github_username}/${github_reponame}
cd ${github_reponame}
git checkout ${github_}branch}

kubectl create ns minio
kubectl --namespace minio apply --filename etc/kubernetes/manifests/

curl http://localhost:32000/
```
