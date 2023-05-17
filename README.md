# ckan-solr

Pre-configured Solr Docker images for CKAN powering the [depositar](https://data.depositar.io/).

**Note:** These images are not vulnerable to CVE-2021-44228 / Log4J2 as are built on top of [patched upstream Solr images](https://github.com/docker-solr/docker-solr#readme).


### Building the image

    docker build -t depositar/ckan-solr -f solr-8/Dockerfile.spatial solr-8
