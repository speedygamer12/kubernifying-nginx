## kubernifying-nginx
argocd app create nginx-static --repo https://github.com/speedygamer12/test-repo.git --path / --dest-server https://kubernetes.default.svc --dest-namespace default

argocd app create helm-guestbook --repo https://github.com/speedygamer12/test3.git --path guestbook --dest-server https://kubernetes.default.svc --dest-namespace default

argocd app create nginx-static --repo https://github.com/speedygamer12/kubernifying-nginx.git --path kube-task-chart --dest-server https://kubernetes.default.svc --dest-namespace default
