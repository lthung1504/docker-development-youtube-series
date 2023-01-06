download:
	helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx && helm pull ingress-nginx/ingress-nginx && tar -xzf *.tgz && rm *.tgz

install:
	helm upgrade --install ingress-nginx ingress-nginx/ -n ingress-nginx --create-namespace -f ingress-nginx/values.yaml
