FROM opensuse/leap
RUN zypper install -y git make perl-libwww-perl perl-XML-Parser && git clone https://github.com/openSUSE/obs-build && cd obs-build && git apply /root/patch && make install && cd .. && rm -rf obs-build patch
COPY sl15.1.conf /usr/lib/build/configs/
