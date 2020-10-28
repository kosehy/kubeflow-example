
# kubeflow-example

# Environment
kubernetes=1.18.9

# How to install kubeflow

sudo snap install microk8s --classic --channel=1.18/stable

microk8s start

microk8s enable dns storage gpu istio

microk8s enable kubeflow

# Reference
Trevor Grant. (2020). Kubeflow for Machine Learning (Holden Karau, Boris Lublinsky, Richard Liu, Ilan Filonenko). O'Reilly Media, Inc.
