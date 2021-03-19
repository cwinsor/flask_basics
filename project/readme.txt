# Docker + streamlit
#
# from https://app.pluralsight.com/guides/dockerfile-for-python-web-projects

docker build -t myimage .
docker run -p 8501:8501 myimage
