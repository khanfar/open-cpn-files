--------------------------------------------------------------
this works and tested in opencpn-msvc_5.6.2_setup.exe  v5.6.2
-------------------------------------------------------------

--------------   AIS  Decoder and view in OpenCPN   ---------------

-------------------------------------------------------------------

AIS channels at 161.975 MHz and 162.025 MHz

install rtlsdr_pi.exe then install opencpn v5.6.2 by download these 3 parts zip of opencpn
then right click on patrt1 then unzip so its unzip all as one file , 
rhen install it , then unzip the plugin folder and past over opencpn plugin folder
that you early installed and check it located in C:\Program Files (x86)\OpenCPN
now open software then
activate the plugin from software itself ,  and add this command in plugin property  :     -gr RTLAGC on TUNER auto -o 2 -a 192K -u 127.0.0.1 10110 -N 8100

and from software create new connection udp on network adress 127.0.0.1 and network 10110
you can use lan monitor from web browser in ip http://127.0.0.1:8100

