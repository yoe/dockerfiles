FROM opensuse/leap
RUN zypper install -y git make perl-XML-Parser && git clone https://github.com/openSUSE/obs-build && cd obs-build && make install && cd .. && rm -rf obs-build
