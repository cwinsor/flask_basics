# following https://app.pluralsight.com/library/courses/flask-getting-started/table-of-contents

docker build --tag flask-docker-demo-app .
docker run --name flask-docker-demo-app -p 5001:5001 flask-docker-demo-app

docker stop
docker ps

