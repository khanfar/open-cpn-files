--------------------------------------------------------------
this works and tested in opencpn-msvc_5.6.2_setup.exe  v5.6.2
-------------------------------------------------------------

--------------   AIS  Decoder and view in OpenCPN   ---------------

-------------------------------------------------------------------

AIS channels at 161.975 MHz and 162.025 MHz

install rtlsdr_pi.exe then install opencpn v5.6.2 then unzip the pligin folder and past over opencpn folder then 
activate the plugin from software itself ,  and add this command in plugin property  :     -gr RTLAGC on TUNER auto -o 2 -a 192K -u 127.0.0.1 10110 -N 8100

and from software create new connection udp on network adress 127.0.0.1 and network 10110
you can use lan monitor from web browser in ip http://127.0.0.1:8100

