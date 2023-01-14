# Padavan-build说明
现在不需要新建Release了，已经更改了脚本，直接fork，修改好之后，点击右上角的 Star 星星按钮即可开始自动编译（自己点击才会编译）。

# 修改记录

https://github.com/onemade/rt-n56u/blob/master/trunk/tools/Makefile

行36中 “gomirrors.org” 失效，替换为 “dl.google.com”

#
https://github.com/onemade/rt-n56u/trunk/user/htop/Makefile

行2中 SRC_URL = https://bintray.com/htop/source/download_file?file_path=htop-3.0.2.tar.gz

替换为 SRC_URL = https://github.com/htop-dev/htop/archive/refs/tags/3.0.2.tar.gz
