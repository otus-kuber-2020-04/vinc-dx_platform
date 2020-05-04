# vinc-dx_platform

---
# Домашка 1 (kubernetes-intro)
В виртуалку c ubuntu 18.04 установлен minikube, kubectl
Запущен кластер kubernetes, добавлен dashboard

Проверена работоспособность, удаление всех подов из namesapce kube-system: 
    - Часть подов в namespace kube-system запускаются kubelet'ом (/etc/kubernetes/manifests):
    etcd, kube-apiserver, kube-controller-manager, kube-scheduler
     - Часть из DaemonSet, Deployment и т.д.:
    coredns, kube-proxy

Создан образ с "web сервером", проверена работа.
Выполнено доп.задание - frontend от Hipster Shop
---
