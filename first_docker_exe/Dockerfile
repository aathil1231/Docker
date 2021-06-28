 FROM ubuntu
 RUN apt-get update
 RUN apt-get -y install python
 COPY hi_dock.py /hi_dock.py
 RUN ["chmod", "+x", "/hi_dock.py"]
 CMD ["/hi_dock.py"]
