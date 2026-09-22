ARG version
FROM almalinux: ${version:-9}
ENV course="devops"\
    trainer="siva"\
    learner="bharathi"
#RUN echo "hello ${trainer}" > /tmp/devops.txt
ARG USERNAME=siva
ENV USERNAME=${USERNAME}
RUN echo "hello user: ${USERNAME}" > /tmp/devops.txt
CMD ["sleep","500"]

