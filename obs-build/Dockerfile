FROM opensuse/leap
RUN zypper install -y git make && git clone https://github.com/openSUSE/obs-build && cd obs-build && make install && cd .. && rm -rf obs-build
