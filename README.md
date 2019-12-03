# jupyter-notebook
Jupyter Notebook Helm Chart for fast deploy in kubernetes

helm install jupyter-notebook --name jupyter-notebook --set ingress.hosts[0].host="myjupyter.net"
