this works and tested in opencpn-msvc_5.6.2_setup.exe  so in v5.6.2

install rtlsdr_pi.exe then install opencpn v5.6.2 then unzip the pligin folder and past over opencpn folder then 
activate the plugin from software itself and use command -gr RTLAGC on TUNER auto -o 2 -a 192K -u 127.0.0.1 10110 -N 8100

and fron software create new connection udp on network adress 127.0.0.1 and network 10110
you can use lan monitor from web browser in ip http://127.0.0.1:8100
