FROM miciav/hadoop-spark:1.0.0

ADD spark-worker-entrypoint.sh /spark-worker-entrypoint.sh
RUN chmod a+x /spark-worker-entrypoint.sh

ENTRYPOINT ["/spark-worker-entrypoint.sh"]
