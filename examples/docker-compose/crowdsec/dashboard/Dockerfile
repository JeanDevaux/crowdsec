FROM metabase/metabase

RUN mkdir /metabase-data/ && wget https://crowdsec-statics-assets.s3-eu-west-1.amazonaws.com/metabase_sqlite.zip && unzip metabase_sqlite.zip -d /metabase-data/
RUN chown -R 2000:2000 /metabase-data/