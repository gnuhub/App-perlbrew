why
=============

* 为了安装调试 perl 语言编写的 kiwi

how
================

* 本地调试

```
./perlbrew-install
```
```
+ PERLBREWURL=http://gugod.github.io/App-perlbrew/perlbrew
+ '[' -z /var/folders/71/3ck56qx933bfpqj96m87gx400000gn/T/ ']'
+ cd /var/folders/71/3ck56qx933bfpqj96m87gx400000gn/T/
+ LOCALINSTALLER=perlbrew-89249
+ echo

+ type curl
+ PERLBREWDOWNLOAD='curl -f -k -sS -Lo perlbrew-89249 http://gugod.github.io/App-perlbrew/perlbrew'
+ echo '## Download the latest perlbrew'
## Download the latest perlbrew
+ curl -f -k -sS -Lo perlbrew-89249 http://gugod.github.io/App-perlbrew/perlbrew
+ echo

+ echo '## Installing perlbrew'
## Installing perlbrew
+ chmod +x perlbrew-89249
+ /usr/bin/perl perlbrew-89249 self-install
perlbrew is installed: ~/perl5/perlbrew/bin/perlbrew

perlbrew root (~/perl5/perlbrew) is initialized.

Append the following piece of code to the end of your ~/.zshenv and start a
new shell, perlbrew should be up and fully functional from there:

    source ~/perl5/perlbrew/etc/bashrc

Simply run `perlbrew` for usage details.

Happy brewing!

+ echo '## Installing patchperl'
## Installing patchperl
+ /usr/bin/perl perlbrew-89249 -f -q install-patchperl
+ echo

+ echo '## Done.'
## Done.
+ rm ./perlbrew-89249
```