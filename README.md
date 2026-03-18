# Laboratory work №1: Nginx + Docker
Create a web server in Docker using Nginx and connect an HTML page

## 💃 Author
Merkulova Elizaveta, AM-2

## 🪗 How to start a project

1. Clone repo:
```bash
  git clone https://github.com/uKreek/nginx-lab
  cd nginx-lab
```
2. Run the container:
```bash
  docker-compose up -d --build
```
3. Open in browser:
```http://localhost:8080```

## 🍽️ Project content

```docker-compose.yml``` — Nginx description

```code/index.html``` — main HTML-page

```code/answers.html``` — second page

```screenshots/``` — all screenshots

## 📸 Screenshots
![alt](screenshots/1-docker-version.png)
![alt](screenshots/2-nginx-works.png)
![alt](screenshots/3-add-html.png)
![alt](screenshots/4-edit-html-text.png)
![alt](screenshots/5-second-page.png)
![alt](screenshots/6-edit-host.png)
## 🎉 Result
The Docker server has started successfully, Nginx is serving my HTML page.
