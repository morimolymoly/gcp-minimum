FROM google/cloud-sdk:alpine
RUN apk --no-cache add openjdk7-jre
RUN gcloud components install alpha beta && \
    gcloud --version
