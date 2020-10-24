FROM guni1192/latex-ja

RUN apk update \
  && apk add --no-cache curl fontconfig git zsh ttf-freefont xvfb \
  && curl -O https://moji.or.jp/wp-content/ipafont/IPAexfont/IPAexfont00401.zip \
  && mkdir -p /usr/share/fonts/ \
  && unzip IPAexfont00401.zip -d /usr/share/fonts/ \
  && rm IPAexfont00401.zip\
  && fc-cache -fv \