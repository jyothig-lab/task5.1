Image Optimization
│
├── app/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── .dockerignore
│
└── README.md


"I first built the application using the standard Python image to understand the baseline image size."
image size --- 1.62GB----docker-security:v1
Now Switched to Alpine Image by changing docker file
image size ----81.24mb----docker-security:v2
alpine ----lightweight, secure Linux distribution that is widely used as a base image for Docker containers.
now i add .dockerignore file(prevents unnecessary files from being copied into the Docker build context, making builds faster and images smaller.)
image size ----81.24mb----docker-security:v3
