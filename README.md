# k8s-labs

### These tasks are about Kubernetes resources such as Deployments, ConfigMaps, PV/PVC, Services, and ResourceQuota.

---

# Task 1
[➡️ Go to Task 1 files]([./Task1](https://github.com/Hassan-Ali-Salama/k8s-labs/tree/main/Task1))

**Description:**  
This task required:  
- Run an Nginx pod.  
- Use a ConfigMap to change the port from 80 to 82.  
- Use PV and PVC to map the `index.html` file from the cluster host.  
- Expose it using a ClusterIP service.  
- Try to curl it from another Nginx pod using both Pod IP and ClusterIP.  

---

# Task 2
[➡️ Go to Task 2 files]([./Task2](https://github.com/Hassan-Ali-Salama/k8s-labs/tree/main/Task2))

**Description:**  
This task required:  
- Run a MySQL instance.  
- Use a Secret to store the password.  
- Try to access it using the password stored in the Secret.  

---

# Task 3
[➡️ Go to Task 3 files]([./Task3](https://github.com/Hassan-Ali-Salama/k8s-labs/tree/main/Task3))

**Description:**  
This task required:  
- Run a Deployment.  
- Delete one pod and observe what happens.  
- Explain the difference between ReplicaSets and Deployments.  

---

# Task 4
[➡️ Go to Task 4 files]([./Task4](https://github.com/Hassan-Ali-Salama/k8s-labs/tree/main/Task4))

**Description:**  
This task required:  
- Run two containers inside a single pod.  
- The first container listens on port 80.  
- The second container uses a ConfigMap to change the port to 50.  
- Change the `index.html` file inside both containers.  
- Expose them through a Service.  

---

# Task 5
[➡️ Go to Task 5 files]([./Task5](https://github.com/Hassan-Ali-Salama/k8s-labs/tree/main/Task5))

**Description:**  
This task required:  
- Create a namespace named `depi`.  
- Limit it to 1 pod and 1 deployment only.  
- Try to create a deployment with 3 replicas.  
- Show the output when running:  
  ```bash
  kubectl get pods

---

# Extra Files

There is a folder named [AllYamlsFiles]([./AllYamlsFiles](https://github.com/Hassan-Ali-Salama/k8s-labs/tree/main/AllYamlsFiles)) that contains all the YAML files you may need to practice Kubernetes.
These files were created by [Eng. Abanob Ayad.](https://github.com/AbanobAyad22)

[👉 Go to the repo for these files](https://github.com/AbanobAyad22/kubernetes-course) 

  
