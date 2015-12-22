FROM centos-curl

# procps is very common in build systems, and is a reasonably small package
RUN yum update -y && yum install -y \
		bzr \
		git \
		mercurial \
		openssh-clients \
		subversion \
		\
		procps \
	&& yum clean all
