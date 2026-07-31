OpenShift = Kubernetes + Extra Features
─────────────────────────────────────────
Kubernetes:              OpenShift adds:
✅ Pods                  ✅ BuildConfig
✅ Deployments           ✅ ImageStream
✅ Services              ✅ DeploymentConfig
✅ Ingress               ✅ Routes (instead of Ingress)
                         ✅ Source-to-Image (S2I)
                         ✅ Web Console (nicer UI)
                         ✅ Built-in Registry
                         ✅ Security (stricter!)

OpenShift vs K8s Summary:

K8s	               OpenShift	             Purpose
Deployment	     DeploymentConfig	     Run pods
Ingress	          Route	              External access
Docker Hub	    ImageStream	             Image tracking
Manual build	   BuildConfig     	   Auto build
kubectl	            oc	               CLI tool
namespace	         Project	           Isolation
