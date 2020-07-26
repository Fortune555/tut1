FROM ubuntu:20.04
ENV TZ=Africa/Johannesburg
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
RUN apt-get update && \
	apt-get install -y software-properties-common build-essential

RUN apt-get install -y samtools bcftools


