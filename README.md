1.��ѹlibev-4.15.tar.gz,����libev-4.15
  ./configure
  make
  make install
2.����mysql��װĿ¼��/data/webserver/mysql
  ln -s /data/webserver/mysql/include /usr/include/mysql
  ln -s /data/webserver/mysql/lib     /usr/lib64/mysql  #������64λ����ϵͳ��
  ��/etc/ld.so.conf�����/usr/lib64/mysql  ����ldconfig
3.����alarmdaemonĿ¼������make,���ɵ����г�����binĿ¼��