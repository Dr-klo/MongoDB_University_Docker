FROM mongo:3.4.1
RUN   apt update -y \
    && mkdir -p /data \
    && chmod -R 777 /data   \
    && mkdir -p /data/db \
    && mkdir -p /home/vagrant/data \
    && chmod -R 777 /home/vagrant/data \
    && mkdir -p /home/vagrant/data/authdb \
    &&  apt-get install -y python-dev \
    &&  apt-get install -y python-pip \
    &&  pip install pymongo \
    &&  pip install docopt \
    &&  pip install faker \
    &&  pip install psutil \
    &&  pip install mtools
