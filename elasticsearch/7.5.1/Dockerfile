FROM docker.elastic.co/elasticsearch/elasticsearch:7.5.1
RUN bin/elasticsearch-plugin install analysis-icu
RUN bin/elasticsearch-plugin install analysis-smartcn
RUN bin/elasticsearch-plugin install --batch https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.5.1/elasticsearch-analysis-ik-7.5.1.zip
RUN bin/elasticsearch-plugin install --batch  https://github.com/medcl/elasticsearch-analysis-pinyin/releases/download/v7.5.1/elasticsearch-analysis-pinyin-7.5.1.zip
RUN bin/elasticsearch-plugin install --batch  https://github.com/medcl/elasticsearch-analysis-stconvert/releases/download/v7.5.1/elasticsearch-analysis-stconvert-7.5.1.zip

