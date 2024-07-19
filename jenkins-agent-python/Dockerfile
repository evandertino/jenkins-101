FROM jenkins/agent:latest-alpine-jdk21
# Install Python 3, pip, and virtualenv
USER root
RUN apk update && \
    apk add --no-cache python3 py3-virtualenv

# Switch back to non-root user (if applicable)
USER jenkins

# Set the default command to /bin/sh
CMD ["/bin/sh"]