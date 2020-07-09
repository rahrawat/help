# help
Simple useful commands and shortcuts for linux
set tags=tags;/

/bin/kill -9 $(ps -ax | grep qcarcam | awk '{print $1}')

export COLUMNS LINES;
//workin//
COLUMNS=79;LINES=22;export COLUMNS LINES; 
resize
 shopt -s checkwinsize
 COLUMNS=79;LINES=22;export COLUMNS LINES;
 resize
 /////////////////
 

	 COLUMNS=79;LINES=22;export COLUMNS LINES; ls ; resize ; ls ; shopt -s checkwinsize ; ls ; COLUMNS=79;LINES=22;export COLUMNS LINES; resize
 
 clang-format-3.9  -style="{IndentWidth: 4,TabWidth: 4}" -i
 
 vim tab to spaces
:set tabstop=4 shiftwidth=4 expandtab retab

while true; do free -hm | tail -n 2 | head -n 1 | awk '{print $3}' ; sleep 4; done

  change time_stamp all files : 
    find . -exec touch -t 201707162310.00 {} +        


N==   indent N lines

/\t     show tabs in document


" Show all tabs:
/\t

" Show trailing whitespace:
/\s\+$

" Show trailing whitespace only after some text (ignores blank lines):
/\S\zs\s\+$

" Show spaces before a tab:
/ \+\ze\t



 bitbake ais && cd tmp-glibc/work/8x96mizar-agl-linux/ais/0.1-r0/image/ && sshpass -p 'PASSWORD' scp -rv *  rahul.sr@192.168.3.131:priya_lib/ ; sshpass -p 'PASSWORD' ssh rahul.sr@192.168.3.131 adb push priya_lib/usr/bin/* /usr/bin/
 
 scp /home/priya.gokani/Documents/845_setup/Open-Q_845_Android-O_v1.0/Source_Package/SDA845_Open-Q_845_Android-O_v1.0/out/target/product/sdm845/vendor/lib/camera/com.qti.sensormodule.sony_imx332.bin  qti.test@192.168.3.78:com.qti.sensormodule.sony_imx332.bin



DMESG REMOVE TIMESTAMPS REGEX   \[  (.*?)\]


grep -rin "rtc" --include=\*.{c,}


MAKE FILE spaces to tab-->     perl -pi -e 's/^  */\t/' Makefile


C:\Windows\SysWOW64\cmd.exe /c ""C:\Program Files (x86)\Git\bin\sh.exe" --login -i" 

sudo service network-manager restart



arrange columns wise --> :%!sed 's/"&"/\&/' | column -t -s '&'

DELETE ALL ~ files   find . -type f \( -iname "*~" \) -delete

GITHUB
 git format-patch c99f
 git reset --hard c99f
 gti add fnkwhfw
 git commit --amend
 git am --signoff <  000X-kfwekfwek.patch
 git push --force


