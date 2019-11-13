FROM postgres

#Install Agent NewRelic
#ADD  
#RUN apt-get update -y
#RUN apt-get install curl -y
#RUN "curl -s https://download.newrelic.com/infrastructure_agent/gpg/newrelic-infra.gpg | apt-key add -"
#RUN apt-get install nri-postgresql

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
