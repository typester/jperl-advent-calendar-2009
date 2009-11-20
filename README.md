For contributors
----------------

準備
===

clone:

    git clone git://github.com/typester/jpa-advent-calendar-2009.git
    cd jpa-advent-calendar-2009
    git submodule init
    git submodule update

install dependency:

    cd extlib/nim
    perl Makefile.PL
    make installdeps
    cd ../../

HTML生成
=======

HTML生成だけ

    ./extlib/nim/bin/nim

生成後Plackサーバーを立ち上げる

    ./extlib/nim/bin/nim --server



