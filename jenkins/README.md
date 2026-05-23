# Jenkins Deployment

Jenkins deployed using Docker on Azure Linux VM.

---

# Port

8080

Access:
http://YOUR_PUBLIC_IP:8080

---

# Features

- Jenkins container deployment
- CI/CD basics
- GitHub integration
- Docker integration
- Pipeline practice

---

# Docker Command Used

docker run -d \
--name jenkins \
-p 8080:8080 \
-p 50000:50000 \
jenkins/jenkins:lts

---

# Skills Learned

- Jenkins setup
- Containerized CI/CD
- Docker networking
- Build automation

