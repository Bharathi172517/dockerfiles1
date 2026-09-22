ARG VERSION=9
FROM almalinux: ${VERSION}
ENV course="devops"\
    trainer="siva"\
    learner="bharathi"
#RUN echo "hello ${trainer}" > /tmp/devops.txt
ARG USERNAME=siva
ENV USERNAME=${USERNAME}
RUN echo "hello user: ${USERNAME}" > /tmp/devops.txt
CMD ["sleep","500"]

