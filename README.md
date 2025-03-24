
<p align="center">
    <img src="img/bg.png" alt="Kubestrick Logo">
</p>


<p align="center">
    <img src="https://img.shields.io/github/stars/AhmedMattar21/kubestrick?style=social" alt="GitHub Stars">
    <img src="https://img.shields.io/github/downloads/AhmedMattar21/kubestrick/total" alt="Downloads">
    <img src="https://img.shields.io/badge/ansible-automation-blue" alt="Ansible">
    <img src="https://img.shields.io/badge/kubernetes-cluster-blue" alt="Kubernetes">
    <img src="https://img.shields.io/github/license/AhmedMattar21/kubestrick" alt="License">
</p>



<p align="center">
    <a href="#-overview">Overview</a> | <a href="#-features">Features</a> | <a href="#-setup">Setup</a> | <a href="#-usage">Usage</a> | <a href="#-license">License</a>
</p>

## 🌟 **Overview**  
Kubestrick simplifies Kubernetes cluster deployment and management using Ansible. With a single playbook, you can configure clusters, add/remove nodes, upgrade versions, and apply networking configurations—ensuring consistency across all environments.

## ✨ **Features**  

✅ **Cluster Initialization** – Set up a Kubernetes cluster from scratch.  
✅ **Node Management** – Seamlessly add or remove worker nodes.  
✅ **Networking Configuration** – Apply CNI (e.g., Calico, Flannel) for efficient cluster networking.  
✅ **Monitoring Setup** – Deploy Prometheus, Grafana, or other monitoring tools.  
✅ **Cluster Upgrades** – Automate upgrades of Kubernetes and its components.  
✅ **Customizable Settings** – Adjust cluster size, networking, and add-ons effortlessly.  
✅ **Private Registry Support** – Easily configure the cluster to work with a private container registry.  

---

## ⚙️ **Setup**  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/kubestrick.git && cd kubestrick
   ```
2. **Configure the Inventory**  
   Modify the inventory file to define your master and worker nodes.  
1. **Update the Configuration**  
   Adjust settings in:  
   ```bash
   /group_vars/all.yaml
   ```

---

## 🚀 **Usage**  

### **Run the playbook**  
```bash
ansible-playbook k8s.yml -i targets -k
```
---

## 📝 **License**  
This project is licensed under [MIT License](LICENSE).




<h3 align=center> Happy Automating! 🎉 </h3>