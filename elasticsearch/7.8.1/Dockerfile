FROM elasticsearch:7.8.1
RUN bin/elasticsearch-plugin install analysis-icu
RUN bin/elasticsearch-plugin install analysis-smartcn
RUN bin/elasticsearch-plugin install --batch https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.8.1/elasticsearch-analysis-ik-7.8.1.zip
RUN bin/elasticsearch-plugin install --batch  https://github.com/medcl/elasticsearch-analysis-pinyin/releases/download/v7.8.1/elasticsearch-analysis-pinyin-7.8.1.zip
RUN bin/elasticsearch-plugin install --batch  https://github.com/medcl/elasticsearch-analysis-stconvert/releases/download/v7.8.1/elasticsearch-analysis-stconvert-7.8.1.zip

