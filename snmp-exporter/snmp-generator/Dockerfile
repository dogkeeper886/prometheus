FROM rockylinux:9.1
RUN yum -y install vim net-snmp net-snmp-utils bash-completion
COPY Ruckus_AP_5.2.2_Mib_20210202/ /usr/share/snmp/mibs/
COPY generator.yml /opt/
CMD while true; do sleep 30; done;