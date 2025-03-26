# MyFamilyNet-k8s
Services Involved right now: 
1. Keycloak (Ingress) 
2. API-Gateway (ClusterIP)
3. Social-Service (ClusterIP)
4. Neo4j Graph Database (LoadBalancer)
5. My-Family-App, React/Vite Framework (LoadBalancer)


### Expose API Gateway LoadBalancer (First Stage): 
![Expose API Gateway](./images/present_1.png)

### Expose My-Family-App (React App), made API Gateway private - ClusterIP (Second Stage):
![Expose My-Family-App](./images/present_2.png)
![My-Family-Net-App-Prototype](./images/present_3.png)

### Adding Local Neo4j - Graph Database (Third Stage)
![Expose Neo4j Database](./images/present_4.png)
![Neo4j Database](./images/present_5.png)



