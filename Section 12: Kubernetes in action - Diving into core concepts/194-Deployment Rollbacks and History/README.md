k set image deployment/first-app k8s-the-practical-guide=adrabenche/k8s-the-practical-guide:194
k rollout status deployment first-app
k rollout undo deployment first-app
k rollout history deployment first-app
k rollout history deployment first-app --revision 5
k rollout undo deployment first-app --to-revision=1
docker build -t adrabenche/k8s-the-practical-guide:194 kub-action-01-starting-setup/ && docker push adrabenche/k8s-the-practical-guide:194
