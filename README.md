# 🌩️ nebuliX-portal

**nebuliX-portal** is a modern, self-service cloud provisioning platform that empowers users to request and manage virtual infrastructure—like virtual machines (VMs), Kubernetes clusters, and storage—on-demand through a sleek web interface.

Built on top of **OpenStack**, **Flask**, and **Terraform**, this portal automates infrastructure provisioning and governance for private cloud environments.

---

## 🚀 Features

- 🌐 Web-based user portal (Flask)
- 🔐 User authentication and session management
- 📦 VM provisioning via Terraform & OpenStack
- 🔄 Infrastructure as Code (IaC) powered by Terraform
- 📥 Approval-ready architecture for future ServiceNow integration
- 📊 Easily extendable for Kubernetes, storage, and autoscaling
- ⚙️ Deployable with Docker and Nginx

---

## 🧰 Tech Stack

- **Frontend/UI**: Flask (Jinja2 Templates)
- **Backend**: Python, Flask, SQLite (or PostgreSQL/MySQL)
- **Infrastructure Automation**: Terraform
- **Cloud Platform**: OpenStack (DevStack)
- **Deployment**: Docker, Nginx

---

## 📸 Demo

> Coming soon: Screenshots and deployment walkthrough

---

## ⚙️ Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/nebuliX-portal.git
cd nebuliX-portal
```

### 2. Install Dependencies
```bash
pip3 install -r requirements.txt
```

### 3. Configure Flask App
Edit `app.py` or `.env` (coming soon) with your secrets and OpenStack API credentials.

### 4. Set Up Terraform
- Modify `terraform/main.tf` with your OpenStack config
- Initialize Terraform:
  ```bash
  cd terraform
  terraform init
  ```

### 5. Run the App
```bash
python3 app.py
```

Open `http://localhost:5000` to access the portal.

---

## 🧪 Example VM Request Flow

1. User logs in to the web portal.
2. User fills in VM request form.
3. Flask triggers the Terraform script.
4. VM is provisioned on OpenStack.
5. Output like IP is returned to user (coming soon).

---

## 🧱 Project Roadmap

- [x] User Login & Dashboard
- [x] Terraform-based VM provisioning
- [ ] Multi-user request history
- [ ] Kubernetes cluster provisioning
- [ ] Email notifications & approval flow
- [ ] ServiceNow API integration

---

## 🤝 Contributing

Got ideas? Want to make this more powerful?

```bash
# Fork it, branch it, build it!
```

Pull requests and issue reports are welcome! 🙌

---

## 📄 License

N/A

---

## 📬 Contact

Built by [@normieshri](https://github.com/normieshri)  
If you found this useful, give the repo a ⭐ and share the love!

```
