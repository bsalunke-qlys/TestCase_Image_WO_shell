FROM alpine 
RUN apk add curl
RUN apk add python
RUN apk add python-dev
#RUN apk add python-utils
RUN apk add g++
RUN apk add gcc
RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
RUN python2.7 get-pip.py
RUN pip install mercurial==5.3.2
RUN pip install django==1.8.16
RUN pip install requests==2.2.1
RUN pip install markdown2==1.1.1
RUN apk add --update nodejs npm
RUN npm install -g mongodb
RUN npm install -g needle
RUN npm install -g flatted
RUN npm install -g http-proxy
RUN npm install -g stream-json@1.0.1
RUN rm -f /bin/sh
RUN rm -f /bin/bash
