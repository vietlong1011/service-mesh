service mesh , istio , traffic with kiali

service-mesh
Service Mesh is a specialized infrastructure layer that controls service-to-service network communication. Service Mesh allows separate parts of an application to communicate with each other.Service Mesh appears commonly with applications. , containers, and cloud-based microservices. Service Mesh uses sidecar applications to handle network logic, making these logics work similar to Proxies, becoming third-party applications and helping cluster operators to configure them more easily.

#istio Istio is an open source network service built on top of Kubernetes to manage and control network traffic between service-based applications (microservices). Istio provides features such as load balancing, request dispersion, security, tracking, and monitoring. It works by deploying proxy sidecars (usually Envoy) next to each application container, which helps control network traffic between containers.

#kiali Istio is an open source network service built on the foundation of Kubernetes to manage and control network traffic between service-based applications (microservices). Istio provides features such as load balancing, segmentation request dispersion, security, tracking, and monitoring. It works by deploying proxy sidecars (usually Envoy) next to each application container, which helps control network traffic between containers.

1. Cài đặt :
Tải xuống istio : https://istio.io/latest/docs/setup/getting-started/

Môi trường product : sử dụng helm để cấu hình các ứng dụng khác : https://istio.io/latest/docs/setup/install/helm/

Môi trường demo : dùng istioctl : https://istio.io/latest/docs/setup/getting-started/

Cau hinh them grafana : kubectl apply -f https://raw.githubusercontent.com/istio/istio/release-1.21/samples/addons/grafana.yaml

Cau hinh kiali : kubectl apply -f https://raw.githubusercontent.com/istio/istio/release-1.21/samples/addons/kiali.yaml
