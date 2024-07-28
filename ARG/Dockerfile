FROM almalinux:8
ARG username 
RUN adduser ${username}
USER ${username}
ARG COURSE
ARG DURATION 
ENV COURSE = ${COURSE}
ENV DURATION = ${DURATION}
CMD [ "sleep", "100" ]