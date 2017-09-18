FROM python:3.5

COPY requirements.txt /home/docker/code/app/
RUN pip3 install -r /home/docker/code/app/requirements.txt

# add (the rest of) our code
COPY . /
