FROM rosalab/rosa2021.1
RUN dnf install -y dnf-utils
RUN yum-config-manager --add-repo \
https://abf-downloads.rosalinux.ru/takumi18_personal/repository/rosa2021.1/x86_64/main/release/
RUN dnf install --nogpgcheck -y texlive-context-fancybreak
ENTRYPOINT rpm -q texlive-context-fancybreak
