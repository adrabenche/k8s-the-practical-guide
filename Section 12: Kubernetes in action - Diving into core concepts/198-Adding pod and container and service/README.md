docker build -t adrabenche/k8s-the-practical-guide:198 kub-action-02-declarative-approach-basics/ && docker push adrabenche/k8s-the-practical-guide:198
k apply -f deployment.yaml -f service.yaml