FROM osixia/openldap:1.1.8
MAINTAINER Ibrahim Folarin <ifolarin@webbasedsol.com>

ADD bootstrap /container/service/slapd/assets/config/bootstrap
RUN rm /container/service/slapd/assets/config/bootstrap/schema/mmc/mail.schema
ADD certs /container/service/slapd/assets/certs
ADD environment /container/environment/01-custom
