ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELK_VERSION}

RUN yum install nano -y

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu