# MyFamliyNet-k8s
Services Involves right now : 
1) Keycloak (Expose by Ingress) 
2) API-Gateway (ClusterIP)
3) Social-Service (ClusterIP)
4) My-Family-App(React\Vite Framework) (LoadBalancer)

### Expose API Gatway LoadBalancer (First Stage): 
![Expose API Gateway](./images/present_1.png)

### Expose My-Family-App (React App) , made API Gateway private - ClusterIP (Second Stage):
![Expose My-Family-App](./images/present_2.png)

