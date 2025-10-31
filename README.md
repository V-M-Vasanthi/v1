for java
FROM openjdk
WORKDIR /app
COPY . /app
RUN javac sample.java
CMD ["java","sample"]



fopr python
FROM python:3.10-slim
WORKDIR /app
COPY . /app
CMD ["python","sample.py"]

html code
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Small Profile</title>
  <style>
    body{font-family:Arial,Helvetica,sans-serif;background:#f6f8fb;color:#0b1220;display:flex;align-items:center;justify-content:center;height:100vh;margin:0}
    .card{background:white;padding:18px;border-radius:10px;box-shadow:0 6px 18px rgba(11,18,32,0.08);width:320px;text-align:center}
    .avatar{width:84px;height:84px;border-radius:50%;background:#7c3aed;color:white;display:inline-flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;margin-bottom:12px}
    h1{font-size:18px;margin:6px 0}
    p.role{margin:0;color:#6b7280;font-size:13px}
    p.bio{font-size:14px;color:#374151;margin:12px 0}
    .contact{font-size:13px;color:#111827}
    .btn{display:inline-block;margin-top:10px;padding:8px 12px;border-radius:8px;background:#06b6d4;color:white;text-decoration:none}
  </style>
</head>
<body>
  <div class="card">
    <div class="avatar">PR</div>
    <h1>Priyanka R.</h1>
    <p class="role">Software Engineer</p>
    <p class="bio">I build web services and containerized applications. I enjoy automating workflows and learning new tools.</p>
    <div class="contact">shivani@example.com • +917686987907</div>
    <a class="btn" href="#">Connect</a>




    commands 
    docker build -t imagename
    docker run -d --name c7 -p 6063:80 imagename:latest
    docker tag imageid vmvasanthi/imagename
    docker push docker.io/vmvasanthi/imagename
    docker pull vmvasanthi/imagename



    
    
  </div>
</body>
</html>
