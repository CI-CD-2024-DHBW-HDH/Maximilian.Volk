# Aufgabe 5

1. Welche Vorteile ein Kubernetes Deployment gegenüber einem Kubernetes Pod hat
 
- Deployments können skaliert werden
- Deployments starten neue Pods, sollte ein Pod ausfallen
- Deployments können einfacher verwaltet und bereitgestellt werden

2. Wofür ein Kubernetes Service gut ist 

- Ein Service dient zur internen und auch externen Kommunikation
- Ein Service kann Load-Balancing umsetzen
- Ein Service bietet im Gegensatz zu einem Pod eine dauerhafte IP (Pod IP ist dynamisch)

3. Mehrere Wege wie man eine Kubernetes Anwendung von außen erreichen kann

- Über den NodePort (mittels IP)
- Über einen Ingress Controller
- Über einen LoadBalancer (z.B. von AWS)

