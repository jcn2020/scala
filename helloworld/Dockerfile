FROM teambde2018/scala-sbt
# ENV SCALA_VERION 2.11.8
RUN mkdir /app
WORKDIR /app
ADD . /app
RUN ls -altr /app ; scala -version ; sbt sbtVersion ; echo $PATH
# ENV PATH /root/scala-2.11.8/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
RUN scala -version ; echo $PATH
RUN sbt run

