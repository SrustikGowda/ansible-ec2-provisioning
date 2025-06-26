# 🛠️ Ansible EC2 Provisioning & Configuration

A complete, production-style Ansible project that provisions and configures EC2 instances using roles.

## 🚀 Features
- Role-based Ansible structure
- EC2 provisioning and bootstrap config
- Webserver setup (Nginx)
- Easy inventory and host/group vars

## 📁 Folder Structure
```
ansible-ec2-provisioning/
├── inventories/
│   └── hosts
├── site.yml
├── roles/
│   ├── common/
│   │   └── tasks/main.yml
│   └── webserver/
│       └── tasks/main.yml
```

## 🧪 How to Use
1. Replace the IP and key path in `inventories/hosts`
2. Run the playbook:
```bash
ansible-playbook -i inventories/hosts site.yml
```

## 🧱 Roles
- `common`: Basic tools & updates
- `webserver`: Installs and starts Nginx

## 👨‍💻 Author
**Srustik** | DevOps | Cloud | Automation

## 🧾 License
MIT