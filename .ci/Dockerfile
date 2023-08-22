FROM mcr.microsoft.com/dotnet/sdk:latest

RUN apt-get update && \
    apt-get install -y -q openjdk-11-jre && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
