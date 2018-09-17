## RiOS report

Here is a report for baby-rios kernel．

for more infomation:https://github.com/Twopothead/OS_exp/tree/master/final_exp/19215116_邱日/doc

## install

```sh
sudo apt-get install texlive-xetex
sudo apt-get install texlive-lang-cjk
sudo apt-get install texlive-science
sudo apt-get install msttcorefonts
```

## Add font installation instructions for Linux

```sh
[ -d /usr/share/fonts/opentype ] || sudo mkdir /usr/share/fonts/opentype
sudo git clone https://github.com/adobe-fonts/source-code-pro.git /usr/share/fonts/opentype/scp
sudo fc-cache -f -v
```

- https://github.com/Haixing-Hu/nju-thesis
- https://github.com/adobe-fonts/source-han-serif
- https://github.com/adobe-fonts/source-code-pro/issues/17#issuecomment-8967116
