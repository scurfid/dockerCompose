# 📦 Docker Compose Configuration Files for SMR Applications

This repository contains Docker Compose setups for various applications used in **SMR environments**.

---

## 🧠 Applications Included

### 🚀 Moodle

Moodle is an open-source learning platform used in many educational institutions.

#### ✅ Prerequisites

- **Linux**: Docker Engine installed  
- **Windows/Mac**: [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed

#### 🛠️ Installation Steps

1. **Clone this repository:**

   ```bash
   git clone https://github.com/scurfid/dockerCompose.git
   ```

2. **Navigate to the Moodle Docker Compose folder (directory where you previously cloned the repo):**

   ```bash
   cd path/to/moodle/
   ```

3. **Launch the services:**

   ```bash
   docker compose up -d
   ```

4. **Access Moodle in your browser:**

   ```
   http://localhost:8082

   username: user
   password: bitnami
   ```

#### 📁 Moodle File Upload Configuration

This setup allows course file uploads up to **600 MB**.  
Make sure to adjust Moodle settings (as admin) via:

```
Site administration → Security → Site policies → Max upload size
```

Once running, you will be ready to restore .mbz courses without max size limit problems
---
