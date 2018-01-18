cd rtlwifi_new-master/
 1088  make
 1089  sudo make install
 1090  sudo modprobe -rv rtl8723be
 1091  sudo modprobe -v rtl8723be ant_sel=2
 1092  echo "options rtl8723be ant_sel=2" | sudo tee /etc/modprobe.d/50-rtl8723be.conf

