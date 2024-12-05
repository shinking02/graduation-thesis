FROM paperist/texlive-ja:latest
RUN wget -P "/sty" "https://raw.githubusercontent.com/h-kitagawa/plistings/master/plistings.sty"
RUN tlmgr update --self
RUN tlmgr install algorithms algorithmicx algpseudocodex latexindent
RUN apt update && apt install -y git \
    locales \
    perl \
    cpanminus
RUN cpanm Log::Log4perl YAML::Tiny File::HomeDir
CMD [ "bin/bash" ]

