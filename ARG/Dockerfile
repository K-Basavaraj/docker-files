ARG version
FROM almalinux:${version:-9}
ARG course="Devops with AWS" \
    duration="120hr"
ENV duration=$duration
RUN echo "Course: $course, duration: $duration"
CMD ["sleep","100"]