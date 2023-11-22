FROM mcr.microsoft.com/dotnet/sdk:latest

RUN add-apt-repository ppa:openjdk-r/ppa && \
    apt-get update && \
    apt-get install -y -q openjdk-11-jre curl jq gettext && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
