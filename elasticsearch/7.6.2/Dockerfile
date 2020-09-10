FROM docker.elastic.co/elasticsearch/elasticsearch:7.6.2
RUN bin/elasticsearch-plugin install analysis-icu
RUN bin/elasticsearch-plugin install analysis-smartcn
RUN bin/elasticsearch-plugin install --batch https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.6.2/elasticsearch-analysis-ik-7.6.2.zip
RUN bin/elasticsearch-plugin install --batch  https://github.com/medcl/elasticsearch-analysis-pinyin/releases/download/v7.6.2/elasticsearch-analysis-pinyin-7.6.2.zip
