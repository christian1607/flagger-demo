

### Install Flagger

```bash
kubectl apply -k github.com/fluxcd/flagger//kustomize/istio
```
    
### Create namespace

```bash
kubectl apply -f namespace.yaml
```

### Deploy sample application

```bash
kubectl apply -f deployment.yaml
```

### Create istio gateway

```bash
kubectl apply -f gateway.yaml
```

### Deploy Flagger Canary

```bash
kubectl apply -f canary.yaml
```
	