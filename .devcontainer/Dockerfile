FROM centos:7

RUN yum -y update && yum install -y @base @centos-7-epel @centos-7-updates @spacewalk @anaconda @spacewalk-client @centos-7-sclo-sc @centos-7-sclo-rh @centos-7-storage @base-debuginfo
RUN yum groupinstall -y "Development Tools" "System Administration Tools" "System Management"