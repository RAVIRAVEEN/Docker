ARG version
FROM almalinux:${version:-8}
ARG username 
RUN adduser ${username}
USER ${username}
ARG COURSE
ARG DURATION 
RUN echo "Course: ${COURSE}, Duration: ${DURATION}"
ENV COURSE=${COURSE}
ENV DURATION=${DURATION}
CMD [ "sleep", "100" ]