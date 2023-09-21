docker build -t adrabenche/k8s-the-practical-guide:193 kub-action-01-starting-setup/ && docker push adrabenche/k8s-the-practical-guide:193
#Actualizar imagen y tag
docker build -t adrabenche/k8s-the-practical-guide:193.2 kub-action-01-starting-setup/ && docker push adrabenche/k8s-the-practical-guide:193.2
k set image deployment/first-app k8s-the-practical-guide=adrabenche/k8s-the-practical-guide:193.2