# load-balancer
## 📌 Why Use an ALB?

- **Distributes HTTP(S) traffic** across multiple EC2 instances for **high availability**.
- Supports **path-based and host-based routing**.
- Integrated with **Auto Scaling** and **Target Groups**.
- Supports **SSL termination** and **Web Application Firewall (WAF)**.
- Useful for **microservices** or **containerized applications**.

---

## ⚙️ When to Use

Use ALB when:
- You need **intelligent routing** (based on path or host).
- You want **centralized TLS termination**.
- You're running **microservices** in different containers.
- Your application demands **horizontal scaling** with multiple AZs.

---

## 🛠️ Components Used

| Component       | Purpose                               |
|----------------|----------------------------------------|
| VPC             | Isolated networking environment        |
| ALB             | Application Load Balancer              |
| EC2 Instances   | Web/application servers                |
| Target Group    | Group to manage and monitor instances  |
| Availability Zones | Ensure high availability & fault tolerance |
