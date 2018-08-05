FROM ubuntu:xenial

RUN apt-get update
RUN apt-get -y upgrade
RUN apt-get -y install openssl

RUN echo 'set -o vi' >> ~/.bashrc

#ENV WORK_DIR /workspace
#ENV RUN_SCRIPT $WORK_DIR/run.sh
#WORKDIR $WORK_DIR
#
#RUN mkdir -p $WORK_DIR
#
#ADD run.sh $WORK_DIR/run.sh
#
#RUN chmod 755 $RUN_SCRIPT
#
#ENTRYPOINT ["/workspace/run.sh"]
#CMD ["/bin/bash"]
CMD ["/usr/bin/openssl"]

