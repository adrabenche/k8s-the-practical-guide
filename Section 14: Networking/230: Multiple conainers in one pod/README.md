cd auth-api
docker build -t adrabenche/k8s-the-practical-guide:auth-api-230 .
docker push adrabenche/k8s-the-practical-guide:auth-api-230
cd ..
cd tasks-api
docker build -t adrabenche/k8s-the-practical-guide:tasks-api-230 .
docker push adrabenche/k8s-the-practical-guide:tasks-api-230
cd ..
cd users-api
docker build -t adrabenche/k8s-the-practical-guide:users-api-230 .
docker push adrabenche/k8s-the-practical-guide:users-api-230
cd ..