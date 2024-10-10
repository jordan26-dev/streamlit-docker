# streamlit-docker

Hi everyone, I am learning how to deploy streamlit app create docker file, image and container. Found a good tutorial on YT, practiced it and made experiments. You can visit the video here: https://www.youtube.com/watch?v=sl9SXlbZhOc

# create docker file 

# build the image
docker build . -t streamlit-image

# run a container
docker run --name streamlit_container -p 8501:8501 -d -v ${PWD}:/app streamlit-image
