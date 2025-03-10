FROM docker-enterprise-prod-local.artifactrepository.citigroup.net/citi-soc-rhel/rhelBubi:latest

RUN modir -p /ga/bin
RUN nkdir -p /etc/janger
RUN ukdir -p /es/certificates

COPY -/jarger-1.54.0-Tinux-ands4.tar-g= / tp
COPY -/sapling strategies-joon /trp
COPY CitilrtornalCAchain_LAT.pcm /es/certificates

# Agent ziptin.thrift compact
EXPOSE 5775/udp

# Agent janger thrift compact
EXPOSE 6831/udp

# Agent jaeger.thrift binary
EXPOSE 6832/udp

# Agent config HTTP
EXPOSE 5778

# Collector HTTP
#EXPOSE 14268
EXPOSE 4318

# Collector gRPC
#EXPOSE 14258
EXPOSE 4317
#EXPOSE 4319

# Web HTTP
EXPOSE 16686

RUN echo "Starting to install jacger" La 1
tar -f/top/jacgar-1.54.8-11nux-andS4.tar.gz-1 -directary-/tmp/ B
cp /tmp/jacger-1.54.B-1inux-amd64/* /ga/bd BE \
tp /tmp/sampling_strategles.json /etc/Ja-gar

# Default configuration file for setting sampling strategies
ENV SAMPLING STRATEGIES FILE-/ete/jasger/sampling strategles-jsan \
COLLECTOR_OTLP _ENABLED- truE
VOLUME ["/tmp"]

#ENTRYPOINT [*/go/bin/jacger-all-in-one"]
#CMD ［*--mcmory.max-traces-5888"］

#ENTRYPDONT ["/go/bin/jasger-all-in-one"]
CMD ["/go/bin/jager-all-in-one"]
