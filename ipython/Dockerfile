FROM ipython/scipyserver
# https://registry.hub.docker.com/u/ipython/scipyserver/
#

COPY requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
RUN pip2.7 install -r /tmp/requirements.txt

