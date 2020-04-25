# Base Image
FROM python:alpine

# requirements.txt file is outside the segment of the H/D which container has access to, So copy the requirements.txt to container

WORKDIR '/apps'
COPY requirements.txt .
# download and install the dependency
RUN pip install -r requirements.txt

COPY ./ ./

# Tell the image what to do when starts as a container
CMD ["python","SSOT_Api.py"]