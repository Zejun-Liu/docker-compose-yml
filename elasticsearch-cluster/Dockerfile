FROM elasticsearch
ADD ./plugins/elasticsearch-analysis-ik-5.6.12.zip /usr/share/elasticsearch/plugins
RUN  cd /usr/share/elasticsearch/plugins \
      && unzip elasticsearch-analysis-ik-5.6.12.zip \
      && rm -rf elasticsearch-analysis-ik-5.6.12.zip \
      && mv elasticsearch ik
