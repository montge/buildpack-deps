FROM centos-scm

RUN yum update && yum install -y deltarpm
#RUN yum groups mark install "Development Tools" && \
#    yum groups mark convert "Development Tools" && \
#    yum groupinstall -y "Development Tools"
RUN yum install -y autoconf \
		automake \
		bzip2 \
		file \
		gcc-c++ \
		gcc \
		ImageMagick \
		bzip2-libs \
		bzip2-devel \
		glibc-devel \
		libcurl-devel \
		openssl-devel \
		libevent-devel \
		libffi-devel \
		GeoIP-devel \
		glib2-devel \
		libjpeg-devel \
		xz-devel \
		ImageMagick-devel \
		mysql-devel \
		ncurses-devel \
		libpng-devel \
		postgresql-devel \
		readline-devel \
		sqlite-devel \
		libtool \
		libwebp-devel \
		libxml2-devel \
		libxslt-devel \
		libyaml-devel \
		make \
		patch \
		xz \
		zlib-devel \
	&& yum clean all
