# Ubuntu configuration

## Font
우분투 16.04 폰트를 수정하려면 다음 파일을 만들고 적절히 수정하면 된다.
~/.config/font-manager/local.conf
[참고 샘플](/16.04/home/user/.config/font-manager/local.conf)

System-wide 폰트를 수정하려면 다음 파일을 수정한다.
/etc/fonts/local.conf

다른 파일들을 수정하면 시스템에 의해 overwriting 될 수 있다.

+ REF
  - [fonts.conf - Font configuration files](http://manpages.ubuntu.com/manpages/xenial/man5/fonts-conf.5.html)
