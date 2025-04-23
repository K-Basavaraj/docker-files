FROM almalinux/9-base
#Install 'ping' command and clean up to reduce image size
RUN dnf install -y iputils && dnf clean all
# CMD ["ping", "google.com"]
CMD ["google.com", "microsoft.com"]
ENTRYPOINT ["ping"]
