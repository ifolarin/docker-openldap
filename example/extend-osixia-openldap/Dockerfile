FROM osixia/openldap:1.1.11
MAINTAINER Ibrahim Folarin <ifolarin@webbasedsol.com>

ADD bootstrap /container/service/slapd/assets/config/bootstrap
RUN rm /container/service/slapd/assets/config/bootstrap/schema/mmc/mail.schema
RUN rm /container/service/slapd/assets/config/bootstrap/ldif/08-people.ldif
RUN rm /container/service/slapd/assets/config/bootstrap/ldif/billy.ldif
ADD certs /container/service/slapd/assets/certs
ADD environment /container/environment/01-custom
