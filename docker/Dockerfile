FROM ubuntu:latest

RUN apt-get update  \
    && apt-get install -y --no-install-recommends  \
    wget python3 python3-pip  \
    && rm -rf /var/lib/apt/lists/* \

COPY search_path.py extract_path_value.py config.txt /tmp/

RUN chmod +x /tmp/search_path.py /tmp/extract_path_value.py