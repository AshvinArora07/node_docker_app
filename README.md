# Node.js App in Docker 🐳

This is a simple Node.js Express app running inside a Docker container.

---

## 🚀 How to Run the App

1. Pull the image from Docker Hub:
   ```sh
   docker pull ashvinarora07/node_docker_app:latest


2. Run the container : 
Run the app on port 8000 (or any port you like):
docker run -it -e PORT=8000 -p 8000:8000 ashvinarora07/node_docker_app:latest // Can modify the port acccordingly and -e for handling port in environment varaible and -p for mapping the port in code with the localhost

Now open your browser and go to:

👉 http://localhost:8000

You should see:
{ "message": "Hey, I'm NODEJS in a Container" }



🔗 Links

🐙 GitHub Repo: node_docker_app

🐳 Docker Hub Image: ashvinarora07/nodejsapp:latest



✨ Author

👤 Ashvin Arora
📧 ashvinarora79@gmail.com

🔗 LinkedIn
 | GitHub


