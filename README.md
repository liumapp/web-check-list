# Web Check List

用于web应用开发中常用参数对照表

持续更新中，欢迎PR

* [Http Content-type](#http-content-type)
* [Html转意字符](#html转意字符)
* [Ascii对照表](#ascii对照表)
	* [Ascii特殊字符解释](#ascii特殊字符解释)
* [Http状态码](#http状态码)
* [Linux系统端口](#linux系统端口)
	* [Unix特有的端口](#unix特有的端口)
	* [IANA注册的端口](#iana注册的端口)
	* [数据报传递协议端口](#数据报传递协议端口)
	* [Kerberos端口](#kerberos端口)
	* [未注册的端口](#未注册的端口)

## Http Content-type

<table> 
<tr>
<th>文件扩展名</th>
<th>Content-Type(Mime-Type)</th>
<th>文件扩展名</th>
<th>Content-Type(Mime-Type)</th>
</tr>
<tr>
<td>.*（ 二进制流，不知道下载文件类型）</td>
<td>application/octet-stream</td>
<td>.tif</td>
<td>image/tiff</td> 
</tr>
<tr>
<td>.001</td>
<td>application/x-001</td> 
<td>.301</td>
<td>application/x-301</td>
</tr> 
<tr>
<td>.323</td>
<td>text/h323</td> 

<td>.906</td>
<td>application/x-906</td>
</tr> 
<tr>
<td>.907</td>
<td>drawing/907</td> 

<td>.a11</td>
<td>application/x-a11</td>
</tr> 
<tr>
<td>.acp</td>
<td>audio/x-mei-aac</td> 

<td>.ai</td>
<td>application/postscript</td>
</tr> 
<tr>
<td>.aif</td>
<td>audio/aiff</td> 

<td>.aifc</td>
<td>audio/aiff</td>
</tr> 
<tr>
<td>.aiff</td>
<td>audio/aiff</td> 

<td>.anv</td>
<td>application/x-anv</td>
</tr> 
<tr>
<td>.asa</td>
<td>text/asa</td> 

<td>.asf</td>
<td>video/x-ms-asf</td>
</tr> 
<tr>
<td>.asp</td>
<td>text/asp</td> 

<td>.asx</td>
<td>video/x-ms-asf</td>
</tr> 
<tr>
<td>.au</td>
<td>audio/basic</td> 

<td>.avi</td>
<td>video/avi</td>
</tr> 
<tr>
<td>.awf</td>
<td>application/vnd.adobe.workflow</td> 

<td>.biz</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.bmp</td>
<td>application/x-bmp</td> 

<td>.bot</td>
<td>application/x-bot</td>
</tr> 
<tr>
<td>.c4t</td>
<td>application/x-c4t</td> 

<td>.c90</td>
<td>application/x-c90</td>
</tr> 
<tr>
<td>.cal</td>
<td>application/x-cals</td> 

<td>.cat</td>
<td>application/vnd.ms-pki.seccat</td>
</tr> 
<tr>
<td>.cdf</td>
<td>application/x-netcdf</td> 

<td>.cdr</td>
<td>application/x-cdr</td>
</tr> 
<tr>
<td>.cel</td>
<td>application/x-cel</td> 

<td>.cer</td>
<td>application/x-x509-ca-cert</td>
</tr> 
<tr>
<td>.cg4</td>
<td>application/x-g4</td> 

<td>.cgm</td>
<td>application/x-cgm</td>
</tr> 
<tr>
<td>.cit</td>
<td>application/x-cit</td> 

<td>.class</td>
<td>java/*</td>
</tr> 
<tr>
<td>.cml</td>
<td>text/xml</td> 

<td>.cmp</td>
<td>application/x-cmp</td>
</tr> 
<tr>
<td>.cmx</td>
<td>application/x-cmx</td> 

<td>.cot</td>
<td>application/x-cot</td>
</tr> 
<tr>
<td>.crl</td>
<td>application/pkix-crl</td> 

<td>.crt</td>
<td>application/x-x509-ca-cert</td>
</tr> 
<tr>
<td>.csi</td>
<td>application/x-csi</td> 

<td>.css</td>
<td>text/css</td>
</tr> 
<tr>
<td>.cut</td>
<td>application/x-cut</td> 

<td>.dbf</td>
<td>application/x-dbf</td>
</tr> 
<tr>
<td>.dbm</td>
<td>application/x-dbm</td> 

<td>.dbx</td>
<td>application/x-dbx</td>
</tr> 
<tr>
<td>.dcd</td>
<td>text/xml</td> 

<td>.dcx</td>
<td>application/x-dcx</td>
</tr> 
<tr>
<td>.der</td>
<td>application/x-x509-ca-cert</td> 

<td>.dgn</td>
<td>application/x-dgn</td>
</tr> 
<tr>
<td>.dib</td>
<td>application/x-dib</td> 

<td>.dll</td>
<td>application/x-msdownload</td>
</tr> 
<tr>
<td>.doc</td>
<td>application/msword</td> 

<td>.dot</td>
<td>application/msword</td>
</tr> 
<tr>
<td>.drw</td>
<td>application/x-drw</td> 

<td>.dtd</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.dwf</td>
<td>Model/vnd.dwf</td> 

<td>.dwf</td>
<td>application/x-dwf</td>
</tr> 
<tr>
<td>.dwg</td>
<td>application/x-dwg</td> 

<td>.dxb</td>
<td>application/x-dxb</td>
</tr> 
<tr>
<td>.dxf</td>
<td>application/x-dxf</td> 

<td>.edn</td>
<td>application/vnd.adobe.edn</td>
</tr> 
<tr>
<td>.emf</td>
<td>application/x-emf</td> 

<td>.eml</td>
<td>message/rfc822</td>
</tr> 
<tr>
<td>.ent</td>
<td>text/xml</td> 

<td>.epi</td>
<td>application/x-epi</td>
</tr> 
<tr>
<td>.eps</td>
<td>application/x-ps</td> 

<td>.eps</td>
<td>application/postscript</td>
</tr> 
<tr>
<td>.etd</td>
<td>application/x-ebx</td> 

<td>.exe</td>
<td>application/x-msdownload</td>
</tr> 
<tr>
<td>.fax</td>
<td>image/fax</td> 

<td>.fdf</td>
<td>application/vnd.fdf</td>
</tr> 
<tr>
<td>.fif</td>
<td>application/fractals</td> 

<td>.fo</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.frm</td>
<td>application/x-frm</td> 

<td>.g4</td>
<td>application/x-g4</td>
</tr> 
<tr>
<td>.gbr</td>
<td>application/x-gbr</td> 

<td>.</td>
<td>application/x-</td>
</tr> 
<tr>
<td>.gif</td>
<td>image/gif</td> 

<td>.gl2</td>
<td>application/x-gl2</td>
</tr> 
<tr>
<td>.gp4</td>
<td>application/x-gp4</td> 

<td>.hgl</td>
<td>application/x-hgl</td>
</tr> 
<tr>
<td>.hmr</td>
<td>application/x-hmr</td> 

<td>.hpg</td>
<td>application/x-hpgl</td>
</tr> 
<tr>
<td>.hpl</td>
<td>application/x-hpl</td> 

<td>.hqx</td>
<td>application/mac-binhex40</td>
</tr> 
<tr>
<td>.hrf</td>
<td>application/x-hrf</td> 

<td>.hta</td>
<td>application/hta</td>
</tr> 
<tr>
<td>.htc</td>
<td>text/x-component</td> 

<td>.htm</td>
<td>text/html</td>
</tr> 
<tr>
<td>.html</td>
<td>text/html</td> 

<td>.htt</td>
<td>text/webviewhtml</td>
</tr> 
<tr>
<td>.htx</td>
<td>text/html</td> 

<td>.icb</td>
<td>application/x-icb</td>
</tr> 
<tr>
<td>.ico</td>
<td>image/x-icon</td> 

<td>.ico</td>
<td>application/x-ico</td>
</tr> 
<tr>
<td>.iff</td>
<td>application/x-iff</td> 

<td>.ig4</td>
<td>application/x-g4</td>
</tr> 
<tr>
<td>.igs</td>
<td>application/x-igs</td> 

<td>.iii</td>
<td>application/x-iphone</td>
</tr> 
<tr>
<td>.img</td>
<td>application/x-img</td> 

<td>.ins</td>
<td>application/x-internet-signup</td>
</tr> 
<tr>
<td>.isp</td>
<td>application/x-internet-signup</td> 

<td>.IVF</td>
<td>video/x-ivf</td>
</tr> 
<tr>
<td>.java</td>
<td>java/*</td> 

<td>.jfif</td>
<td>image/jpeg</td>
</tr> 
<tr>
<td>.jpe</td>
<td>image/jpeg</td> 

<td>.jpe</td>
<td>application/x-jpe</td>
</tr> 
<tr>
<td>.jpeg</td>
<td>image/jpeg</td> 

<td>.jpg</td>
<td>image/jpeg</td>
</tr> 
<tr>
<td>.jpg</td>
<td>application/x-jpg</td> 

<td>.js</td>
<td>application/x-javascript</td>
</tr> 
<tr>
<td>.jsp</td>
<td>text/html</td> 

<td>.la1</td>
<td>audio/x-liquid-file</td>
</tr> 
<tr>
<td>.lar</td>
<td>application/x-laplayer-reg</td> 

<td>.latex</td>
<td>application/x-latex</td>
</tr> 
<tr>
<td>.lavs</td>
<td>audio/x-liquid-secure</td> 

<td>.lbm</td>
<td>application/x-lbm</td>
</tr> 
<tr>
<td>.lmsff</td>
<td>audio/x-la-lms</td> 

<td>.ls</td>
<td>application/x-javascript</td>
</tr> 
<tr>
<td>.ltr</td>
<td>application/x-ltr</td> 

<td>.m1v</td>
<td>video/x-mpeg</td>
</tr> 
<tr>
<td>.m2v</td>
<td>video/x-mpeg</td> 

<td>.m3u</td>
<td>audio/mpegurl</td>
</tr> 
<tr>
<td>.m4e</td>
<td>video/mpeg4</td> 

<td>.mac</td>
<td>application/x-mac</td>
</tr> 
<tr>
<td>.man</td>
<td>application/x-troff-man</td> 

<td>.math</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.mdb</td>
<td>application/msaccess</td> 

<td>.mdb</td>
<td>application/x-mdb</td>
</tr> 
<tr>
<td>.mfp</td>
<td>application/x-shockwave-flash</td> 

<td>.mht</td>
<td>message/rfc822</td>
</tr> 
<tr>
<td>.mhtml</td>
<td>message/rfc822</td> 

<td>.mi</td>
<td>application/x-mi</td>
</tr> 
<tr>
<td>.mid</td>
<td>audio/mid</td> 

<td>.midi</td>
<td>audio/mid</td>
</tr> 
<tr>
<td>.mil</td>
<td>application/x-mil</td> 

<td>.mml</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.mnd</td>
<td>audio/x-musicnet-download</td> 

<td>.mns</td>
<td>audio/x-musicnet-stream</td>
</tr> 
<tr>
<td>.mocha</td>
<td>application/x-javascript</td> 

<td>.movie</td>
<td>video/x-sgi-movie</td>
</tr> 
<tr>
<td>.mp1</td>
<td>audio/mp1</td> 

<td>.mp2</td>
<td>audio/mp2</td>
</tr> 
<tr>
<td>.mp2v</td>
<td>video/mpeg</td> 

<td>.mp3</td>
<td>audio/mp3</td>
</tr> 
<tr>
<td>.mp4</td>
<td>video/mpeg4</td> 

<td>.mpa</td>
<td>video/x-mpg</td>
</tr> 
<tr>
<td>.mpd</td>
<td>application/vnd.ms-project</td> 

<td>.mpe</td>
<td>video/x-mpeg</td>
</tr> 
<tr>
<td>.mpeg</td>
<td>video/mpg</td> 

<td>.mpg</td>
<td>video/mpg</td>
</tr> 
<tr>
<td>.mpga</td>
<td>audio/rn-mpeg</td> 

<td>.mpp</td>
<td>application/vnd.ms-project</td>
</tr> 
<tr>
<td>.mps</td>
<td>video/x-mpeg</td> 

<td>.mpt</td>
<td>application/vnd.ms-project</td>
</tr> 
<tr>
<td>.mpv</td>
<td>video/mpg</td> 

<td>.mpv2</td>
<td>video/mpeg</td>
</tr> 
<tr>
<td>.mpw</td>
<td>application/vnd.ms-project</td> 

<td>.mpx</td>
<td>application/vnd.ms-project</td>
</tr> 
<tr>
<td>.mtx</td>
<td>text/xml</td> 

<td>.mxp</td>
<td>application/x-mmxp</td>
</tr> 
<tr>
<td>.net</td>
<td>image/pnetvue</td> 

<td>.nrf</td>
<td>application/x-nrf</td>
</tr> 
<tr>
<td>.nws</td>
<td>message/rfc822</td> 

<td>.odc</td>
<td>text/x-ms-odc</td>
</tr> 
<tr>
<td>.out</td>
<td>application/x-out</td> 

<td>.p10</td>
<td>application/pkcs10</td>
</tr> 
<tr>
<td>.p12</td>
<td>application/x-pkcs12</td> 

<td>.p7b</td>
<td>application/x-pkcs7-certificates</td>
</tr> 
<tr>
<td>.p7c</td>
<td>application/pkcs7-mime</td> 

<td>.p7m</td>
<td>application/pkcs7-mime</td>
</tr> 
<tr>
<td>.p7r</td>
<td>application/x-pkcs7-certreqresp</td> 

<td>.p7s</td>
<td>application/pkcs7-signature</td>
</tr> 
<tr>
<td>.pc5</td>
<td>application/x-pc5</td> 

<td>.pci</td>
<td>application/x-pci</td>
</tr> 
<tr>
<td>.pcl</td>
<td>application/x-pcl</td> 

<td>.pcx</td>
<td>application/x-pcx</td>
</tr> 
<tr>
<td>.pdf</td>
<td>application/pdf</td> 

<td>.pdf</td>
<td>application/pdf</td>
</tr> 
<tr>
<td>.pdx</td>
<td>application/vnd.adobe.pdx</td> 

<td>.pfx</td>
<td>application/x-pkcs12</td>
</tr> 
<tr>
<td>.pgl</td>
<td>application/x-pgl</td> 

<td>.pic</td>
<td>application/x-pic</td>
</tr> 
<tr>
<td>.pko</td>
<td>application/vnd.ms-pki.pko</td> 

<td>.pl</td>
<td>application/x-perl</td>
</tr> 
<tr>
<td>.plg</td>
<td>text/html</td> 
<td>.pls</td>
<td>audio/scpls</td>
</tr> 
<tr>
<td>.plt</td>
<td>application/x-plt</td> 
<td>.png</td>
<td>image/png</td>
</tr> 
<tr>
<td>.png</td>
<td>application/x-png</td> 
<td>.pot</td>
<td>application/vnd.ms-powerpoint</td>
</tr> 
<tr>
<td>.ppa</td>
<td>application/vnd.ms-powerpoint</td> 
<td>.ppm</td>
<td>application/x-ppm</td>
</tr> 
<tr>
<td>.pps</td>
<td>application/vnd.ms-powerpoint</td> 
<td>.ppt</td>
<td>application/vnd.ms-powerpoint</td>
</tr> 
<tr>
<td>.ppt</td>
<td>application/x-ppt</td> 
<td>.pr</td>
<td>application/x-pr</td>
</tr> 
<tr>
<td>.prf</td>
<td>application/pics-rules</td> 
<td>.prn</td>
<td>application/x-prn</td>
</tr> 
<tr>
<td>.prt</td>
<td>application/x-prt</td> 
<td>.ps</td>
<td>application/x-ps</td>
</tr> 
<tr>
<td>.ps</td>
<td>application/postscript</td> 
<td>.ptn</td>
<td>application/x-ptn</td>
</tr> 
<tr>
<td>.pwz</td>
<td>application/vnd.ms-powerpoint</td> 
<td>.r3t</td>
<td>text/vnd.rn-realtext3d</td>
</tr> 
<tr>
<td>.ra</td>
<td>audio/vnd.rn-realaudio</td> 
<td>.ram</td>
<td>audio/x-pn-realaudio</td>
</tr> 
<tr>
<td>.ras</td>
<td>application/x-ras</td> 
<td>.rat</td>
<td>application/rat-file</td>
</tr> 
<tr>
<td>.rdf</td>
<td>text/xml</td> 
<td>.rec</td>
<td>application/vnd.rn-recording</td>
</tr> 
<tr>
<td>.red</td>
<td>application/x-red</td> 
<td>.rgb</td>
<td>application/x-rgb</td>
</tr> 
<tr>
<td>.rjs</td>
<td>application/vnd.rn-realsystem-rjs</td> 
<td>.rjt</td>
<td>application/vnd.rn-realsystem-rjt</td>
</tr> 
<tr>
<td>.rlc</td>
<td>application/x-rlc</td> 
<td>.rle</td>
<td>application/x-rle</td>
</tr> 
<tr>
<td>.rm</td>
<td>application/vnd.rn-realmedia</td> 
<td>.rmf</td>
<td>application/vnd.adobe.rmf</td>
</tr> 
<tr>
<td>.rmi</td>
<td>audio/mid</td> 
<td>.rmj</td>
<td>application/vnd.rn-realsystem-rmj</td>
</tr> 
<tr>
<td>.rmm</td>
<td>audio/x-pn-realaudio</td> 
<td>.rmp</td>
<td>application/vnd.rn-rn_music_package</td>
</tr> 
<tr>
<td>.rms</td>
<td>application/vnd.rn-realmedia-secure</td> 
<td>.rmvb</td>
<td>application/vnd.rn-realmedia-vbr</td>
</tr> 
<tr>
<td>.rmx</td>
<td>application/vnd.rn-realsystem-rmx</td> 
<td>.rnx</td>
<td>application/vnd.rn-realplayer</td>
</tr> 
<tr>
<td>.rp</td>
<td>image/vnd.rn-realpix</td> 
<td>.rpm</td>
<td>audio/x-pn-realaudio-plugin</td>
</tr> 
<tr>
<td>.rsml</td>
<td>application/vnd.rn-rsml</td> 
<td>.rt</td>
<td>text/vnd.rn-realtext</td>
</tr> 
<tr>
<td>.rtf</td>
<td>application/msword</td> 
<td>.rtf</td>
<td>application/x-rtf</td>
</tr> 
<tr>
<td>.rv</td>
<td>video/vnd.rn-realvideo</td> 
<td>.sam</td>
<td>application/x-sam</td>
</tr> 
<tr>
<td>.sat</td>
<td>application/x-sat</td> 
<td>.sdp</td>
<td>application/sdp</td>
</tr> 
<tr>
<td>.sdw</td>
<td>application/x-sdw</td> 
<td>.sit</td>
<td>application/x-stuffit</td>
</tr> 
<tr>
<td>.slb</td>
<td>application/x-slb</td> 
<td>.sld</td>
<td>application/x-sld</td>
</tr> 
<tr>
<td>.slk</td>
<td>drawing/x-slk</td> 
<td>.smi</td>
<td>application/smil</td>
</tr> 
<tr>
<td>.smil</td>
<td>application/smil</td> 
<td>.smk</td>
<td>application/x-smk</td>
</tr> 
<tr>
<td>.snd</td>
<td>audio/basic</td> 
<td>.sol</td>
<td>text/plain</td>
</tr> 
<tr>
<td>.sor</td>
<td>text/plain</td> 
<td>.spc</td>
<td>application/x-pkcs7-certificates</td>
</tr> 
<tr>
<td>.spl</td>
<td>application/futuresplash</td> 
<td>.spp</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.ssm</td>
<td>application/streamingmedia</td> 
<td>.sst</td>
<td>application/vnd.ms-pki.certstore</td>
</tr> 
<tr>
<td>.stl</td>
<td>application/vnd.ms-pki.stl</td> 
<td>.stm</td>
<td>text/html</td>
</tr> 
<tr>
<td>.sty</td>
<td>application/x-sty</td> 
<td>.svg</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.swf</td>
<td>application/x-shockwave-flash</td> 
<td>.tdf</td>
<td>application/x-tdf</td>
</tr> 
<tr>
<td>.tg4</td>
<td>application/x-tg4</td> 
<td>.tga</td>
<td>application/x-tga</td>
</tr> 
<tr>
<td>.tif</td>
<td>image/tiff</td> 
<td>.tif</td>
<td>application/x-tif</td>
</tr> 
<tr>
<td>.tiff</td>
<td>image/tiff</td> 
<td>.tld</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.top</td>
<td>drawing/x-top</td> 
<td>.torrent</td>
<td>application/x-bittorrent</td>
</tr> 
<tr>
<td>.tsd</td>
<td>text/xml</td> 
<td>.txt</td>
<td>text/plain</td>
</tr> 
<tr>
<td>.uin</td>
<td>application/x-icq</td> 
<td>.uls</td>
<td>text/iuls</td>
</tr> 
<tr>
<td>.vcf</td>
<td>text/x-vcard</td> 
<td>.vda</td>
<td>application/x-vda</td>
</tr> 
<tr>
<td>.vdx</td>
<td>application/vnd.visio</td> 
<td>.vml</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.vpg</td>
<td>application/x-vpeg005</td> 
<td>.vsd</td>
<td>application/vnd.visio</td>
</tr> 
<tr>
<td>.vsd</td>
<td>application/x-vsd</td> 
<td>.vss</td>
<td>application/vnd.visio</td>
</tr> 
<tr>
<td>.vst</td>
<td>application/vnd.visio</td> 
<td>.vst</td>
<td>application/x-vst</td>
</tr> 
<tr>
<td>.vsw</td>
<td>application/vnd.visio</td> 
<td>.vsx</td>
<td>application/vnd.visio</td>
</tr> 
<tr>
<td>.vtx</td>
<td>application/vnd.visio</td> 
<td>.vxml</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.wav</td>
<td>audio/wav</td> 
<td>.wax</td>
<td>audio/x-ms-wax</td>
</tr> 
<tr>
<td>.wb1</td>
<td>application/x-wb1</td> 
<td>.wb2</td>
<td>application/x-wb2</td>
</tr> 
<tr>
<td>.wb3</td>
<td>application/x-wb3</td> 
<td>.wbmp</td>
<td>image/vnd.wap.wbmp</td>
</tr> 
<tr>
<td>.wiz</td>
<td>application/msword</td> 
<td>.wk3</td>
<td>application/x-wk3</td>
</tr> 
<tr>
<td>.wk4</td>
<td>application/x-wk4</td> 
<td>.wkq</td>
<td>application/x-wkq</td>
</tr> 
<tr>
<td>.wks</td>
<td>application/x-wks</td> 
<td>.wm</td>
<td>video/x-ms-wm</td>
</tr> 
<tr>
<td>.wma</td>
<td>audio/x-ms-wma</td> 
<td>.wmd</td>
<td>application/x-ms-wmd</td>
</tr> 
<tr>
<td>.wmf</td>
<td>application/x-wmf</td> 
<td>.wml</td>
<td>text/vnd.wap.wml</td>
</tr> 
<tr>
<td>.wmv</td>
<td>video/x-ms-wmv</td> 
<td>.wmx</td>
<td>video/x-ms-wmx</td>
</tr> 
<tr>
<td>.wmz</td>
<td>application/x-ms-wmz</td> 
<td>.wp6</td>
<td>application/x-wp6</td>
</tr> 
<tr>
<td>.wpd</td>
<td>application/x-wpd</td> 
<td>.wpg</td>
<td>application/x-wpg</td>
</tr> 
<tr>
<td>.wpl</td>
<td>application/vnd.ms-wpl</td> 
<td>.wq1</td>
<td>application/x-wq1</td>
</tr> 
<tr>
<td>.wr1</td>
<td>application/x-wr1</td> 
<td>.wri</td>
<td>application/x-wri</td>
</tr> 
<tr>
<td>.wrk</td>
<td>application/x-wrk</td> 
<td>.ws</td>
<td>application/x-ws</td>
</tr> 
<tr>
<td>.ws2</td>
<td>application/x-ws</td> 
<td>.wsc</td>
<td>text/scriptlet</td>
</tr> 
<tr>
<td>.wsdl</td>
<td>text/xml</td> 
<td>.wvx</td>
<td>video/x-ms-wvx</td>
</tr> 
<tr>
<td>.xdp</td>
<td>application/vnd.adobe.xdp</td> 
<td>.xdr</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.xfd</td>
<td>application/vnd.adobe.xfd</td> 
<td>.xfdf</td>
<td>application/vnd.adobe.xfdf</td>
</tr> 
<tr>
<td>.xhtml</td>
<td>text/html</td> 
<td>.xls</td>
<td>application/vnd.ms-excel</td>
</tr> 
<tr>
<td>.xls</td>
<td>application/x-xls</td> 
<td>.xlw</td>
<td>application/x-xlw</td>
</tr> 
<tr>
<td>.xml</td>
<td>text/xml</td> 
<td>.xpl</td>
<td>audio/scpls</td>
</tr> 
<tr>
<td>.xq</td>
<td>text/xml</td> 
<td>.xql</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.xquery</td>
<td>text/xml</td> 
<td>.xsd</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.xsl</td>
<td>text/xml</td> 
<td>.xslt</td>
<td>text/xml</td>
</tr> 
<tr>
<td>.xwd</td>
<td>application/x-xwd</td> 
<td>.x_b</td>
<td>application/x-x_b</td>
</tr>
<tr>
<td>.sis</td>
<td>application/vnd.symbian.install</td>
<td>.sisx</td>
<td>application/vnd.symbian.install</td>
</tr>
<tr>
<td>.x_t</td>
<td>application/x-x_t</td>
<td>.ipa</td>
<td>application/vnd.iphone</td>
</tr> 
<tr>
<td>.apk</td>
<td>application/vnd.android.package-archive</td>
<td>.xap</td>
<td>application/x-silverlight-app</td>
</tr>
</table>

## Html转意字符

<table>
<tr>
<th>字符</th>
<th>十进制</th>
<th>转义字符</th>
</tr>
<tr>
<td>"</td>
<td>&amp;#34;</td>
<td>&amp;quot;</td>
</tr>
<tr>
<td>&amp;</td>
<td>&amp;#38;</td>
<td>&amp;amp;</td>
</tr>
<tr>
<td>&lt;</td>
<td>&amp;#60;</td>
<td>&amp;lt;</td>
</tr>
<tr>
<td>&gt;</td>
<td>&amp;#62;</td>
<td>&amp;gt;</td>
</tr>
<tr>
<td>不断开空格(non-breaking space)</td>
<td>&amp;#160;</td>
<td>&amp;nbsp;</td>
</tr>
</table>

## Ascii对照表

<table>
<tr>
<th>ASCII值</th>
<th>控制字符</th>
<th>ASCII值</th>
<th>控制字符</th>
<th>ASCII值</th>
<th>控制字符</th>
<th>ASCII值</th>
<th>控制字符</th>
</tr>
<tr>
<td>0</td>
<td>NUT</td>
<td>32</td>
<td>(space)</td>
<td>64</td>
<td>@</td>
<td>96</td>
<td>、</td>
</tr>
<tr>
<td>1</td>
<td>SOH</td>
<td>33</td>
<td>!</td>
<td>65</td>
<td>A</td>
<td>97</td>
<td>a</td>
</tr>
<tr>
<td>2</td>
<td>STX</td>
<td>34</td>
<td>"</td>
<td>66</td>
<td>B</td>
<td>98</td>
<td>b</td>
</tr>
<tr>
<td>3</td>
<td>ETX</td>
<td>35</td>
<td>#</td>
<td>67</td>
<td>C</td>
<td>99</td>
<td>c</td>
</tr>
<tr>
<td>4</td>
<td>EOT</td>
<td>36</td>
<td>$</td>
<td>68</td>
<td>D</td>
<td>100</td>
<td>d</td>
</tr>
<tr>
<td>5</td>
<td>ENQ</td>
<td>37</td>
<td>%</td>
<td>69</td>
<td>E</td>
<td>101</td>
<td>e</td>
</tr>
<tr>
<td>6</td>
<td>ACK</td>
<td>38</td>
<td>&amp;</td>
<td>70</td>
<td>F</td>
<td>102</td>
<td>f</td>
</tr>
<tr>
<td>7</td>
<td>BEL</td>
<td>39</td>
<td>,</td>
<td>71</td>
<td>G</td>
<td>103</td>
<td>g</td>
</tr>
<tr>
<td>8</td>
<td>BS</td>
<td>40</td>
<td>(</td>
<td>72</td>
<td>H</td>
<td>104</td>
<td>h</td>
</tr>
<tr>
<td>9</td>
<td>HT</td>
<td>41</td>
<td>)</td>
<td>73</td>
<td>I</td>
<td>105</td>
<td>i</td>
</tr>
<tr>
<td>10</td>
<td>LF</td>
<td>42</td>
<td>*</td>
<td>74</td>
<td>J</td>
<td>106</td>
<td>j</td>
</tr>
<tr>
<td>11</td>
<td>VT</td>
<td>43</td>
<td>+</td>
<td>75</td>
<td>K</td>
<td>107</td>
<td>k</td>
</tr>
<tr>
<td>12</td>
<td>FF</td>
<td>44</td>
<td>,</td>
<td>76</td>
<td>L</td>
<td>108</td>
<td>l</td>
</tr>
<tr>
<td>13</td>
<td>CR</td>
<td>45</td>
<td>-</td>
<td>77</td>
<td>M</td>
<td>109</td>
<td>m</td>
</tr>
<tr>
<td>14</td>
<td>SO</td>
<td>46</td>
<td>.</td>
<td>78</td>
<td>N</td>
<td>110</td>
<td>n</td>
</tr>
<tr>
<td>15</td>
<td>SI</td>
<td>47</td>
<td>/</td>
<td>79</td>
<td>O</td>
<td>111</td>
<td>o</td>
</tr>
<tr>
<td>16</td>
<td>DLE</td>
<td>48</td>
<td>0</td>
<td>80</td>
<td>P</td>
<td>112</td>
<td>p</td>
</tr>
<tr>
<td>17</td>
<td>DCI</td>
<td>49</td>
<td>1</td>
<td>81</td>
<td>Q</td>
<td>113</td>
<td>q</td>
</tr>
<tr>
<td>18</td>
<td>DC2</td>
<td>50</td>
<td>2</td>
<td>82</td>
<td>R</td>
<td>114</td>
<td>r</td>
</tr>
<tr>
<td>19</td>
<td>DC3</td>
<td>51</td>
<td>3</td>
<td>83</td>
<td>S</td>
<td>115</td>
<td>s</td>
</tr>
<tr>
<td>20</td>
<td>DC4</td>
<td>52</td>
<td>4</td>
<td>84</td>
<td>T</td>
<td>116</td>
<td>t</td>
</tr>
<tr>
<td>21</td>
<td>NAK</td>
<td>53</td>
<td>5</td>
<td>85</td>
<td>U</td>
<td>117</td>
<td>u</td>
</tr>
<tr>
<td>22</td>
<td>SYN</td>
<td>54</td>
<td>6</td>
<td>86</td>
<td>V</td>
<td>118</td>
<td>v</td>
</tr>
<tr>
<td>23</td>
<td>TB</td>
<td>55</td>
<td>7</td>
<td>87</td>
<td>W</td>
<td>119</td>
<td>w</td>
</tr>
<tr>
<td>24</td>
<td>CAN</td>
<td>56</td>
<td>8</td>
<td>88</td>
<td>X</td>
<td>120</td>
<td>x</td>
</tr>
<tr>
<td>25</td>
<td>EM</td>
<td>57</td>
<td>9</td>
<td>89</td>
<td>Y</td>
<td>121</td>
<td>y</td>
</tr>
<tr>
<td>26</td>
<td>SUB</td>
<td>58</td>
<td>:</td>
<td>90</td>
<td>Z</td>
<td>122</td>
<td>z</td>
</tr>
<tr>
<td>27</td>
<td>ESC</td>
<td>59</td>
<td>;</td>
<td>91</td>
<td>[</td>	
<td>123</td>
<td>{</td>
</tr>
<tr>
<td>28</td>
<td>FS</td>
<td>60</td>
<td>&lt;</td>
<td>92</td>
<td>/</td>	
<td>124</td>
<td>|</td>
</tr>
<tr>
<td>29</td>
<td>GS</td>
<td>61</td>
<td>=</td>
<td>93</td>
<td>]</td>
<td>125</td>
<td>}</td>
</tr>
<tr>
<td>30</td>
<td>RS</td>
<td>62</td>
<td>&gt;</td>
<td>94</td>
<td>^</td>
<td>126</td>
<td>`</td>
</tr>
<tr>
<td>31</td>
<td>US</td>
<td>63</td>
<td>?</td>
<td>95</td>
<td>_</td>
<td>127</td>
<td>DEL</td>
</tr>
</table>

### Ascii特殊字符解释

<table>
<tr>
<th>NUL空</th>
<th>VT 垂直制表</th>
<th>SYN 空转同步</th>
</tr>
<tr>
<td>STX  正文开始</td>
<td>CR   回车</td>
<td>CAN  作废</td>
</tr>
<tr>
<td>ETX  正文结束</td>
<td>SO   移位输出</td>
<td>EM   纸尽</td>
</tr>
<tr>
<td>EOY  传输结束</td>
<td>SI    移位输入</td>
<td>SUB  换置</td>
</tr>
<tr>
<td>ENQ  询问字符</td>
<td>DLE  空格</td>
<td>ESC  换码</td>
</tr>
<tr>
<td>ACK  承认</td>
<td>DC1  设备控制1</td>
<td>FS   文字分隔符</td>
</tr>
<tr>
<td>BEL  报警</td>
<td>DC2  设备控制2</td>
<td>GS   组分隔符</td>
</tr>
<tr>
<td>BS   退一格</td>
<td>DC3  设备控制3</td>
<td>RS   记录分隔符</td>
</tr>
<tr>
<td>HT   横向列表</td>
<td>DC4  设备控制4</td>
<td>US   单元分隔符</td>
</tr>
<tr>
<td>LF   换行</td>
<td>NAK  否定</td>
<td>DEL  删除</td>
</tr>
</table>

## Http状态码

<table>
<tr>
<th>状态码</th>
<th>含义</th>
</tr>
<tr>
<td>100</td>
<td>客户端应当继续发送请求。这个临时响应是用来通知客户端它的部分请求已经被服务器接收，且仍未被拒绝。客户端应当继续发送请求的剩余部分，或者如果请求已经完成，忽略这个响应。服务器必须在请求完成后向客户端发送一个最终响应。</td>
</tr>
<tr>
<td>101</td>
<td>服务器已经理解了客户端的请求，并将通过Upgrade 消息头通知客户端采用不同的协议来完成这个请求。在发送完这个响应最后的空行后，服务器将会切换到在Upgrade 消息头中定义的那些协议。
　　只有在切换新的协议更有好处的时候才应该采取类似措施。例如，切换到新的HTTP 版本比旧版本更有优势，或者切换到一个实时且同步的协议以传送利用此类特性的资源。</td>
</tr>
<tr>
<td>102</td>
<td>由WebDAV（RFC 2518）扩展的状态码，代表处理将被继续执行。</td>
</tr>
<tr>
<td>200</td>
<td>请求已成功，请求所希望的响应头或数据体将随此响应返回。</td>
</tr>
<tr>
<td>201</td>
<td>请求已经被实现，而且有一个新的资源已经依据请求的需要而建立，且其 URI 已经随Location 头信息返回。假如需要的资源无法及时建立的话，应当返回 '202 Accepted'。</td>
</tr>
<tr>
<td>202</td>
<td>服务器已接受请求，但尚未处理。正如它可能被拒绝一样，最终该请求可能会也可能不会被执行。在异步操作的场合下，没有比发送这个状态码更方便的做法了。
　　返回202状态码的响应的目的是允许服务器接受其他过程的请求（例如某个每天只执行一次的基于批处理的操作），而不必让客户端一直保持与服务器的连接直到批处理操作全部完成。在接受请求处理并返回202状态码的响应应当在返回的实体中包含一些指示处理当前状态的信息，以及指向处理状态监视器或状态预测的指针，以便用户能够估计操作是否已经完成。</td>
</tr>
<tr>
<td>203</td>
<td>服务器已成功处理了请求，但返回的实体头部元信息不是在原始服务器上有效的确定集合，而是来自本地或者第三方的拷贝。当前的信息可能是原始版本的子集或者超集。例如，包含资源的元数据可能导致原始服务器知道元信息的超级。使用此状态码不是必须的，而且只有在响应不使用此状态码便会返回200 OK的情况下才是合适的。</td>
</tr>
<tr>
<td>204</td>
<td>服务器成功处理了请求，但不需要返回任何实体内容，并且希望返回更新了的元信息。响应可能通过实体头部的形式，返回新的或更新后的元信息。如果存在这些头部信息，则应当与所请求的变量相呼应。
　　如果客户端是浏览器的话，那么用户浏览器应保留发送了该请求的页面，而不产生任何文档视图上的变化，即使按照规范新的或更新后的元信息应当被应用到用户浏览器活动视图中的文档。
　　由于204响应被禁止包含任何消息体，因此它始终以消息头后的第一个空行结尾。</td>
</tr>
<tr>
<td>205</td>
<td>服务器成功处理了请求，且没有返回任何内容。但是与204响应不同，返回此状态码的响应要求请求者重置文档视图。该响应主要是被用于接受用户输入后，立即重置表单，以便用户能够轻松地开始另一次输入。
　　与204响应一样，该响应也被禁止包含任何消息体，且以消息头后的第一个空行结束。</td>
</tr>
<tr>
<td>206</td>
<td>服务器已经成功处理了部分 GET 请求。类似于 FlashGet 或者迅雷这类的 HTTP 下载工具都是使用此类响应实现断点续传或者将一个大文档分解为多个下载段同时下载。
　　该请求必须包含 Range 头信息来指示客户端希望得到的内容范围，并且可能包含 If-Range 来作为请求条件。
　　响应必须包含如下的头部域：
　　Content-Range 用以指示本次响应中返回的内容的范围；如果是 Content-Type 为 multipart/byteranges 的多段下载，则每一 multipart 段中都应包含 Content-Range 域用以指示本段的内容范围。假如响应中包含 Content-Length，那么它的数值必须匹配它返回的内容范围的真实字节数。
　　Date
　　ETag 和/或 Content-Location，假如同样的请求本应该返回200响应。
　　Expires, Cache-Control，和/或 Vary，假如其值可能与之前相同变量的其他响应对应的值不同的话。
　　假如本响应请求使用了 If-Range 强缓存验证，那么本次响应不应该包含其他实体头；假如本响应的请求使用了 If-Range 弱缓存验证，那么本次响应禁止包含其他实体头；这避免了缓存的实体内容和更新了的实体头信息之间的不一致。否则，本响应就应当包含所有本应该返回200响应中应当返回的所有实体头部域。
　　假如 ETag 或 Last-Modified 头部不能精确匹配的话，则客户端缓存应禁止将206响应返回的内容与之前任何缓存过的内容组合在一起。
　　任何不支持 Range 以及 Content-Range 头的缓存都禁止缓存206响应返回的内容。</td>
</tr>
<tr>
<td>207</td>
<td>由WebDAV(RFC 2518)扩展的状态码，代表之后的消息体将是一个XML消息，并且可能依照之前子请求数量的不同，包含一系列独立的响应代码。</td>
</tr>
<tr>
<td>300</td>
<td>被请求的资源有一系列可供选择的回馈信息，每个都有自己特定的地址和浏览器驱动的商议信息。用户或浏览器能够自行选择一个首选的地址进行重定向。
　　除非这是一个 HEAD 请求，否则该响应应当包括一个资源特性及地址的列表的实体，以便用户或浏览器从中选择最合适的重定向地址。这个实体的格式由 Content-Type 定义的格式所决定。浏览器可能根据响应的格式以及浏览器自身能力，自动作出最合适的选择。当然，RFC 2616规范并没有规定这样的自动选择该如何进行。
　　如果服务器本身已经有了首选的回馈选择，那么在 Location 中应当指明这个回馈的 URI；浏览器可能会将这个 Location 值作为自动重定向的地址。此外，除非额外指定，否则这个响应也是可缓存的。</td>
</tr>
<tr>
<td>301</td>
<td>被请求的资源已永久移动到新位置，并且将来任何对此资源的引用都应该使用本响应返回的若干个 URI 之一。如果可能，拥有链接编辑功能的客户端应当自动把请求的地址修改为从服务器反馈回来的地址。除非额外指定，否则这个响应也是可缓存的。
　　新的永久性的 URI 应当在响应的 Location 域中返回。除非这是一个 HEAD 请求，否则响应的实体中应当包含指向新的 URI 的超链接及简短说明。
　　如果这不是一个 GET 或者 HEAD 请求，因此浏览器禁止自动进行重定向，除非得到用户的确认，因为请求的条件可能因此发生变化。
　　注意：对于某些使用 HTTP/1.0 协议的浏览器，当它们发送的 POST 请求得到了一个301响应的话，接下来的重定向请求将会变成 GET 方式。</td>
</tr>
<tr>
<td>302</td>
<td>请求的资源现在临时从不同的 URI 响应请求。由于这样的重定向是临时的，客户端应当继续向原有地址发送以后的请求。只有在Cache-Control或Expires中进行了指定的情况下，这个响应才是可缓存的。
　　新的临时性的 URI 应当在响应的 Location 域中返回。除非这是一个 HEAD 请求，否则响应的实体中应当包含指向新的 URI 的超链接及简短说明。
　　如果这不是一个 GET 或者 HEAD 请求，那么浏览器禁止自动进行重定向，除非得到用户的确认，因为请求的条件可能因此发生变化。
　　注意：虽然RFC 1945和RFC 2068规范不允许客户端在重定向时改变请求的方法，但是很多现存的浏览器将302响应视作为303响应，并且使用 GET 方式访问在 Location 中规定的 URI，而无视原先请求的方法。状态码303和307被添加了进来，用以明确服务器期待客户端进行何种反应。</td>
</tr>
<tr>
<td>303</td>
<td>对应当前请求的响应可以在另一个 URI 上被找到，而且客户端应当采用 GET 的方式访问那个资源。这个方法的存在主要是为了允许由脚本激活的POST请求输出重定向到一个新的资源。这个新的 URI 不是原始资源的替代引用。同时，303响应禁止被缓存。当然，第二个请求（重定向）可能被缓存。
　　新的 URI 应当在响应的 Location 域中返回。除非这是一个 HEAD 请求，否则响应的实体中应当包含指向新的 URI 的超链接及简短说明。
　　注意：许多 HTTP/1.1 版以前的 浏览器不能正确理解303状态。如果需要考虑与这些浏览器之间的互动，302状态码应该可以胜任，因为大多数的浏览器处理302响应时的方式恰恰就是上述规范要求客户端处理303响应时应当做的。</td>
</tr>
<tr>
<td>304</td>
<td>如果客户端发送了一个带条件的 GET 请求且该请求已被允许，而文档的内容（自上次访问以来或者根据请求的条件）并没有改变，则服务器应当返回这个状态码。304响应禁止包含消息体，因此始终以消息头后的第一个空行结尾。
　　该响应必须包含以下的头信息：
　　Date，除非这个服务器没有时钟。假如没有时钟的服务器也遵守这些规则，那么代理服务器以及客户端可以自行将 Date 字段添加到接收到的响应头中去（正如RFC 2068中规定的一样），缓存机制将会正常工作。
　　ETag 和/或 Content-Location，假如同样的请求本应返回200响应。
　　Expires, Cache-Control，和/或Vary，假如其值可能与之前相同变量的其他响应对应的值不同的话。
　　假如本响应请求使用了强缓存验证，那么本次响应不应该包含其他实体头；否则（例如，某个带条件的 GET 请求使用了弱缓存验证），本次响应禁止包含其他实体头；这避免了缓存了的实体内容和更新了的实体头信息之间的不一致。
　　假如某个304响应指明了当前某个实体没有缓存，那么缓存系统必须忽视这个响应，并且重复发送不包含限制条件的请求。
　　假如接收到一个要求更新某个缓存条目的304响应，那么缓存系统必须更新整个条目以反映所有在响应中被更新的字段的值。</td>
</tr>
<tr>
<td>305</td>
<td>被请求的资源必须通过指定的代理才能被访问。Location 域中将给出指定的代理所在的 URI 信息，接收者需要重复发送一个单独的请求，通过这个代理才能访问相应资源。只有原始服务器才能建立305响应。
　　注意：RFC 2068中没有明确305响应是为了重定向一个单独的请求，而且只能被原始服务器建立。忽视这些限制可能导致严重的安全后果。</td>
</tr>
<tr>
<td>306</td>
<td>在最新版的规范中，306状态码已经不再被使用。</td>
</tr>
<tr>
<td>307</td>
<td>请求的资源现在临时从不同的URI 响应请求。由于这样的重定向是临时的，客户端应当继续向原有地址发送以后的请求。只有在Cache-Control或Expires中进行了指定的情况下，这个响应才是可缓存的。
　　新的临时性的URI 应当在响应的 Location 域中返回。除非这是一个HEAD 请求，否则响应的实体中应当包含指向新的URI 的超链接及简短说明。因为部分浏览器不能识别307响应，因此需要添加上述必要信息以便用户能够理解并向新的 URI 发出访问请求。
　　如果这不是一个GET 或者 HEAD 请求，那么浏览器禁止自动进行重定向，除非得到用户的确认，因为请求的条件可能因此发生变化。</td>
</tr>
<tr>
<td>400</td>
<td>1、语义有误，当前请求无法被服务器理解。除非进行修改，否则客户端不应该重复提交这个请求。
　　2、请求参数有误。</td>
</tr>
<tr>
<td>401</td>
<td>当前请求需要用户验证。该响应必须包含一个适用于被请求资源的 WWW-Authenticate 信息头用以询问用户信息。客户端可以重复提交一个包含恰当的 Authorization 头信息的请求。如果当前请求已经包含了 Authorization 证书，那么401响应代表着服务器验证已经拒绝了那些证书。如果401响应包含了与前一个响应相同的身份验证询问，且浏览器已经至少尝试了一次验证，那么浏览器应当向用户展示响应中包含的实体信息，因为这个实体信息中可能包含了相关诊断信息。参见RFC 2617。</td>
</tr>		<tr>
<td>402</td>
<td>该状态码是为了将来可能的需求而预留的。</td>
</tr>		<tr>
<td>403</td>
<td>服务器已经理解请求，但是拒绝执行它。与401响应不同的是，身份验证并不能提供任何帮助，而且这个请求也不应该被重复提交。如果这不是一个 HEAD 请求，而且服务器希望能够讲清楚为何请求不能被执行，那么就应该在实体内描述拒绝的原因。当然服务器也可以返回一个404响应，假如它不希望让客户端获得任何信息。</td>
</tr>		<tr>
<td>404</td>
<td>请求失败，请求所希望得到的资源未被在服务器上发现。没有信息能够告诉用户这个状况到底是暂时的还是永久的。假如服务器知道情况的话，应当使用410状态码来告知旧资源因为某些内部的配置机制问题，已经永久的不可用，而且没有任何可以跳转的地址。404这个状态码被广泛应用于当服务器不想揭示到底为何请求被拒绝或者没有其他适合的响应可用的情况下。</td>
</tr>		<tr>
<td>405</td>
<td>请求行中指定的请求方法不能被用于请求相应的资源。该响应必须返回一个Allow 头信息用以表示出当前资源能够接受的请求方法的列表。
　　鉴于 PUT，DELETE 方法会对服务器上的资源进行写操作，因而绝大部分的网页服务器都不支持或者在默认配置下不允许上述请求方法，对于此类请求均会返回405错误。</td>
</tr>		<tr>
<td>406</td>
<td>请求的资源的内容特性无法满足请求头中的条件，因而无法生成响应实体。
　　除非这是一个 HEAD 请求，否则该响应就应当返回一个包含可以让用户或者浏览器从中选择最合适的实体特性以及地址列表的实体。实体的格式由 Content-Type 头中定义的媒体类型决定。浏览器可以根据格式及自身能力自行作出最佳选择。但是，规范中并没有定义任何作出此类自动选择的标准。</td>
</tr>		<tr>
<td>407</td>
<td>　与401响应类似，只不过客户端必须在代理服务器上进行身份验证。代理服务器必须返回一个 Proxy-Authenticate 用以进行身份询问。客户端可以返回一个 Proxy-Authorization 信息头用以验证。参见RFC 2617。</td>
</tr>		<tr>
<td>408</td>
<td>请求超时。客户端没有在服务器预备等待的时间内完成一个请求的发送。客户端可以随时再次提交这一请求而无需进行任何更改。</td>
</tr>		<tr>
<td>409</td>
<td>由于和被请求的资源的当前状态之间存在冲突，请求无法完成。这个代码只允许用在这样的情况下才能被使用：用户被认为能够解决冲突，并且会重新提交新的请求。该响应应当包含足够的信息以便用户发现冲突的源头。
　　冲突通常发生于对 PUT 请求的处理中。例如，在采用版本检查的环境下，某次 PUT 提交的对特定资源的修改请求所附带的版本信息与之前的某个（第三方）请求向冲突，那么此时服务器就应该返回一个409错误，告知用户请求无法完成。此时，响应实体中很可能会包含两个冲突版本之间的差异比较，以便用户重新提交归并以后的新版本。</td>
</tr>		<tr>
<td>410</td>
<td>被请求的资源在服务器上已经不再可用，而且没有任何已知的转发地址。这样的状况应当被认为是永久性的。如果可能，拥有链接编辑功能的客户端应当在获得用户许可后删除所有指向这个地址的引用。如果服务器不知道或者无法确定这个状况是否是永久的，那么就应该使用404状态码。除非额外说明，否则这个响应是可缓存的。
　　410响应的目的主要是帮助网站管理员维护网站，通知用户该资源已经不再可用，并且服务器拥有者希望所有指向这个资源的远端连接也被删除。这类事件在限时、增值服务中很普遍。同样，410响应也被用于通知客户端在当前服务器站点上，原本属于某个个人的资源已经不再可用。当然，是否需要把所有永久不可用的资源标记为'410 Gone'，以及是否需要保持此标记多长时间，完全取决于服务器拥有者。</td>
</tr>		<tr>
<td>411</td>
<td>服务器拒绝在没有定义 Content-Length 头的情况下接受请求。在添加了表明请求消息体长度的有效 Content-Length 头之后，客户端可以再次提交该请求。</td>
</tr>		<tr>
<td>412</td>
<td>服务器在验证在请求的头字段中给出先决条件时，没能满足其中的一个或多个。这个状态码允许客户端在获取资源时在请求的元信息（请求头字段数据）中设置先决条件，以此避免该请求方法被应用到其希望的内容以外的资源上。</td>
</tr>		<tr>
<td>413</td>
<td>服务器拒绝处理当前请求，因为该请求提交的实体数据大小超过了服务器愿意或者能够处理的范围。此种情况下，服务器可以关闭连接以免客户端继续发送此请求。
　　如果这个状况是临时的，服务器应当返回一个 Retry-After 的响应头，以告知客户端可以在多少时间以后重新尝试。</td>
</tr>		<tr>
<td>414</td>
<td>请求的URI 长度超过了服务器能够解释的长度，因此服务器拒绝对该请求提供服务。这比较少见，通常的情况包括：
　　本应使用POST方法的表单提交变成了GET方法，导致查询字符串（Query String）过长。
　　重定向URI “黑洞”，例如每次重定向把旧的 URI 作为新的 URI 的一部分，导致在若干次重定向后 URI 超长。
　　客户端正在尝试利用某些服务器中存在的安全漏洞攻击服务器。这类服务器使用固定长度的缓冲读取或操作请求的 URI，当 GET 后的参数超过某个数值后，可能会产生缓冲区溢出，导致任意代码被执行[1]。没有此类漏洞的服务器，应当返回414状态码。</td>
</tr>		<tr>
<td>415</td>
<td>对于当前请求的方法和所请求的资源，请求中提交的实体并不是服务器中所支持的格式，因此请求被拒绝。</td>
</tr>		<tr>
<td>416</td>
<td>如果请求中包含了 Range 请求头，并且 Range 中指定的任何数据范围都与当前资源的可用范围不重合，同时请求中又没有定义 If-Range 请求头，那么服务器就应当返回416状态码。
　　假如 Range 使用的是字节范围，那么这种情况就是指请求指定的所有数据范围的首字节位置都超过了当前资源的长度。服务器也应当在返回416状态码的同时，包含一个 Content-Range 实体头，用以指明当前资源的长度。这个响应也被禁止使用 multipart/byteranges 作为其 Content-Type。</td>
</tr>		<tr>
<td>417</td>
<td>在请求头 Expect 中指定的预期内容无法被服务器满足，或者这个服务器是一个代理服务器，它有明显的证据证明在当前路由的下一个节点上，Expect 的内容无法被满足。</td>
</tr>		<tr>
<td>421</td>
<td>从当前客户端所在的IP地址到服务器的连接数超过了服务器许可的最大范围。通常，这里的IP地址指的是从服务器上看到的客户端地址（比如用户的网关或者代理服务器地址）。在这种情况下，连接数的计算可能涉及到不止一个终端用户。</td>
</tr>		<tr>
<td>422</td>
<td>从当前客户端所在的IP地址到服务器的连接数超过了服务器许可的最大范围。通常，这里的IP地址指的是从服务器上看到的客户端地址（比如用户的网关或者代理服务器地址）。在这种情况下，连接数的计算可能涉及到不止一个终端用户。</td>
</tr>		<tr>
<td>422</td>
<td>请求格式正确，但是由于含有语义错误，无法响应。（RFC 4918 WebDAV）423 Locked
　　当前资源被锁定。（RFC 4918 WebDAV）</td>
</tr>		<tr>
<td>424</td>
<td>由于之前的某个请求发生的错误，导致当前请求失败，例如 PROPPATCH。（RFC 4918 WebDAV）</td>
</tr>		<tr>
<td>425</td>
<td>在WebDav Advanced Collections 草案中定义，但是未出现在《WebDAV 顺序集协议》（RFC 3658）中。</td>
</tr>		<tr>
<td>426</td>
<td>客户端应当切换到TLS/1.0。（RFC 2817）</td>
</tr>		<tr>
<td>449</td>
<td>由微软扩展，代表请求应当在执行完适当的操作后进行重试。</td>
</tr>		<tr>
<td>500</td>
<td>服务器遇到了一个未曾预料的状况，导致了它无法完成对请求的处理。一般来说，这个问题都会在服务器的程序码出错时出现。</td>
</tr>		<tr>
<td>501</td>
<td>服务器不支持当前请求所需要的某个功能。当服务器无法识别请求的方法，并且无法支持其对任何资源的请求。</td>
</tr>		<tr>
<td>502</td>
<td>作为网关或者代理工作的服务器尝试执行请求时，从上游服务器接收到无效的响应。</td>
</tr>		<tr>
<td>503</td>
<td>由于临时的服务器维护或者过载，服务器当前无法处理请求。这个状况是临时的，并且将在一段时间以后恢复。如果能够预计延迟时间，那么响应中可以包含一个 Retry-After 头用以标明这个延迟时间。如果没有给出这个 Retry-After 信息，那么客户端应当以处理500响应的方式处理它。
　　注意：503状态码的存在并不意味着服务器在过载的时候必须使用它。某些服务器只不过是希望拒绝客户端的连接。</td>
</tr>		<tr>
<td>504</td>
<td>作为网关或者代理工作的服务器尝试执行请求时，未能及时从上游服务器（URI标识出的服务器，例如HTTP、FTP、LDAP）或者辅助服务器（例如DNS）收到响应。
　　注意：某些代理服务器在DNS查询超时时会返回400或者500错误</td>
</tr>		<tr>
<td>505</td>
<td>服务器不支持，或者拒绝支持在请求中使用的 HTTP 版本。这暗示着服务器不能或不愿使用与客户端相同的版本。响应中应当包含一个描述了为何版本不被支持以及服务器支持哪些协议的实体。</td>
</tr>		<tr>
<td>506</td>
<td>由《透明内容协商协议》（RFC 2295）扩展，代表服务器存在内部配置错误：被请求的协商变元资源被配置为在透明内容协商中使用自己，因此在一个协商处理中不是一个合适的重点。</td>
</tr>
<tr>
<td>507</td>
<td>服务器无法存储完成请求所必须的内容。这个状况被认为是临时的。WebDAV (RFC 4918)</td>
</tr>
<tr>
<td>509</td>
<td>服务器达到带宽限制。这不是一个官方的状态码，但是仍被广泛使用。</td>
</tr>
<tr>
<td>510</td>
<td>获取资源所需要的策略并没有没满足。（RFC 2774）</td>
</tr>
</table>

## Linux系统端口

下面的表格中列举了包括在红帽企业 Linux 中的服务、守护进程、和程序所使用的最常见的通信端口

该列表还可以在 /etc/services 文件中找到

要查看由互联网号码分派局（IANA）制定的“著名的已注册动态端口”官方列表，请参考以下 URL：

http://www.iana.org/assignments/port-numbers

“层”是指服务或协议在交通层上使用 TCP 还是 UDP

若没有列举，这个服务或协议就两者都使用。

<table>
<tr>
<th>端口号码 / 层</th>
<th>名称</th>
<th>注释</th>
</tr>
<tr>
<td>1 </td>
<td>tcpmux </td>
<td>TCP 端口服务多路复用 </td>
</tr>
<tr>
<td>5 </td>
<td>rje </td>
<td>远程作业入口 </td>
</tr>
<tr>
<td>7 </td>
<td>echo </td>
<td>Echo 服务 </td>
</tr>
<tr>
<td>9 </td>
<td>discard </td>
<td>用于连接测试的空服务 </td>
</tr>
<tr>
<td>11 </td>
<td>systat </td>
<td>用于列举连接了的端口的系统状态 </td>
</tr>
<tr>
<td>13 </td>
<td>daytime </td>
<td>给请求主机发送日期和时间 </td>
</tr>
<tr>
<td>17 </td>
<td>qotd </td>
<td>给连接了的主机发送每日格言 </td>
</tr>
<tr>
<td>18 </td>
<td>msp </td>
<td>消息发送协议 </td>
</tr>
<tr>
<td>19 </td>
<td>chargen </td>
<td>字符生成服务；发送无止境的字符流 </td>
</tr>
<tr>
<td>20 </td>
<td>ftp-data </td>
<td>FTP 数据端口 </td>
</tr>
<tr>
<td>21 </td>
<td>ftp </td>
<td>文件传输协议（FTP）端口；有时被文件服务协议（FSP）使用 </td>
</tr>
<tr>
<td>22 </td>
<td>ssh </td>
<td>安全 Shell（SSH）服务 </td>
</tr>
<tr>
<td>23 </td>
<td>telnet </td>
<td>Telnet 服务 </td>
</tr>
<tr>
<td>25 </td>
<td>smtp </td>
<td>简单邮件传输协议（SMTP） </td>
</tr>
<tr>
<td>37 </td>
<td>time </td>
<td>时间协议 </td>
</tr>
<tr>
<td>39 </td>
<td>rlp </td>
<td>资源定位协议 </td>
</tr>
<tr>
<td>42 </td>
<td>nameserver </td>
<td>互联网名称服务 </td>
</tr>
<tr>
<td>43 </td>
<td>nicname </td>
<td>WHOIS 目录服务 </td>
</tr>
<tr>
<td>49 </td>
<td>tacacs </td>
<td>用于基于 TCP/IP 验证和访问的终端访问控制器访问控制系统 </td>
</tr>
<tr>
<td>50 </td>
<td>re-mail-ck </td>
<td>远程邮件检查协议 </td>
</tr>
<tr>
<td>53 </td>
<td>domain </td>
<td>域名服务（如 BIND） </td>
</tr>
<tr>
<td>63 </td>
<td>whois++ </td>
<td>WHOIS++，被扩展了的 WHOIS 服务 </td>
</tr>
<tr>
<td>67 </td>
<td>bootps </td>
<td>引导协议（BOOTP）服务；还被动态主机配置协议（DHCP）服务使用 </td>
</tr>
<tr>
<td>68 </td>
<td>bootpc </td>
<td>Bootstrap（BOOTP）客户；还被动态主机配置协议（DHCP）客户使用 </td>
</tr>
<tr>
<td>69 </td>
<td>tftp </td>
<td>小文件传输协议（TFTP） </td>
</tr>
<tr>
<td>70 </td>
<td>gopher </td>
<td>Gopher 互联网文档搜寻和检索 </td>
</tr>
<tr>
<td>71 </td>
<td>netrjs-1 </td>
<td>远程作业服务 </td>
</tr>
<tr>
<td>72 </td>
<td>netrjs-2 </td>
<td>远程作业服务 </td>
</tr>
<tr>
<td>73 </td>
<td>netrjs-3 </td>
<td>远程作业服务 </td>
</tr>
<tr>
<td>73 </td>
<td>netrjs-4 </td>
<td>远程作业服务 </td>
</tr>
<tr>
<td>79 </td>
<td>finger </td>
<td>用于用户联系信息的 Finger 服务 </td>
</tr>
<tr>
<td>80 </td>
<td>http </td>
<td>用于万维网（WWW）服务的超文本传输协议（HTTP） </td>
</tr>
<tr>
<td>88 </td>
<td>kerberos </td>
<td>Kerberos 网络验证系统 </td>
</tr>
<tr>
<td>95 </td>
<td>supdup </td>
<td>Telnet 协议扩展 </td>
</tr>
<tr>
<td>101 </td>
<td>hostname </td>
<td>SRI-NIC 机器上的主机名服务 </td>
</tr>
<tr>
<td>102 </td>
<td>iso-tsap </td>
<td>ISO 开发环境（ISODE）网络应用 </td>
</tr>
<tr>
<td>105 </td>
<td>csnet-ns </td>
<td>邮箱名称服务器；也被 CSO 名称服务器使用 </td>
</tr>
<tr>
<td>107 </td>
<td>rtelnet </td>
<td>远程 Telnet </td>
</tr>
<tr>
<td>109 </td>
<td>pop2 </td>
<td>邮局协议版本2 </td>
</tr>
<tr>
<td>110 </td>
<td>pop3 </td>
<td>邮局协议版本3 </td>
</tr>
<tr>
<td>111 </td>
<td>sunrpc </td>
<td>用于远程命令执行的远程过程调用（RPC）协议，被网络文件系统（NFS）使用 </td>
</tr>
<tr>
<td>113 </td>
<td>auth </td>
<td>验证和身份识别协议 </td>
</tr>
<tr>
<td>115 </td>
<td>sftp </td>
<td>安全文件传输协议（SFTP）服务 </td>
</tr>
<tr>
<td>117 </td>
<td>uucp-path </td>
<td>Unix 到 Unix 复制协议（UUCP）路径服务 </td>
</tr>
<tr>
<td>119 </td>
<td>nntp </td>
<td>用于 USENET 讨论系统的网络新闻传输协议（NNTP） </td>
</tr>
<tr>
<td>123 </td>
<td>ntp </td>
<td>网络时间协议（NTP） </td>
</tr>
<tr>
<td>137 </td>
<td>netbios-ns </td>
<td>在红帽企业 Linux 中被 Samba 使用的 NETBIOS 名称服务 </td>
</tr>
<tr>
<td>138 </td>
<td>netbios-dgm </td>
<td>在红帽企业 Linux 中被 Samba 使用的 NETBIOS 数据报服务 </td>
</tr>
<tr>
<td>139 </td>
<td>netbios-ssn </td>
<td>在红帽企业 Linux 中被 Samba 使用的NET BIOS 会话服务 </td>
</tr>
<tr>
<td>143 </td>
<td>imap </td>
<td>互联网消息存取协议（IMAP） </td>
</tr>
<tr>
<td>161 </td>
<td>snmp </td>
<td>简单网络管理协议（SNMP） </td>
</tr>
<tr>
<td>162 </td>
<td>snmptrap </td>
<td>SNMP 的陷阱 </td>
</tr>
<tr>
<td>163 </td>
<td>cmip-man </td>
<td>通用管理信息协议（CMIP） </td>
</tr>
<tr>
<td>164 </td>
<td>cmip-agent </td>
<td>通用管理信息协议（CMIP） </td>
</tr>
<tr>
<td>174 </td>
<td>mailq </td>
<td>MAILQ </td>
</tr>
<tr>
<td>177 </td>
<td>xdmcp </td>
<td>X 显示管理器控制协议 </td>
</tr>
<tr>
<td>178 </td>
<td>nextstep </td>
<td>NeXTStep 窗口服务器 </td>
</tr>
<tr>
<td>179 </td>
<td>bgp </td>
<td>边界网络协议 </td>
</tr>
<tr>
<td>191 </td>
<td>prospero </td>
<td>Cliffod Neuman 的 Prospero 服务 </td>
</tr>
<tr>
<td>194 </td>
<td>irc </td>
<td>互联网中继聊天（IRC） </td>
</tr>
<tr>
<td>199 </td>
<td>smux </td>
<td>SNMP UNIX 多路复用 </td>
</tr>
<tr>
<td>201 </td>
<td>at-rtmp </td>
<td>AppleTalk 选路 </td>
</tr>
<tr>
<td>202 </td>
<td>at-nbp </td>
<td>AppleTalk 名称绑定 </td>
</tr>
<tr>
<td>204 </td>
<td>at-echo </td>
<td>AppleTalk echo 服务 </td>
</tr>
<tr>
<td>206 </td>
<td>at-zis </td>
<td>AppleTalk 区块信息 </td>
</tr>
<tr>
<td>209 </td>
<td>qmtp </td>
<td>快速邮件传输协议（QMTP） </td>
</tr>
<tr>
<td>210 </td>
<td>z39.50 </td>
<td>NISO Z39.50 数据库 </td>
</tr>
<tr>
<td>213 </td>
<td>ipx </td>
<td>互联网络分组交换协议（IPX），被 Novell Netware 环境常用的数据报协议 </td>
</tr>
<tr>
<td>220 </td>
<td>imap3 </td>
<td>互联网消息存取协议版本3 </td>
</tr>
<tr>
<td>245 </td>
<td>link </td>
<td>LINK </td>
</tr>
<tr>
<td>347 </td>
<td>fatserv </td>
<td>Fatmen 服务器 </td>
</tr>
<tr>
<td>363 </td>
<td>rsvp_tunnel </td>
<td>RSVP 隧道 </td>
</tr>
<tr>
<td>369 </td>
<td>rpc2portmap </td>
<td>Coda 文件系统端口映射器 </td>
</tr>
<tr>
<td>370 </td>
<td>codaauth2 </td>
<td>Coda 文件系统验证服务 </td>
</tr>
<tr>
<td>372 </td>
<td>ulistproc </td>
<td>UNIX Listserv </td>
</tr>
<tr>
<td>389 </td>
<td>ldap </td>
<td>轻型目录存取协议（LDAP） </td>
</tr>
<tr>
<td>427 </td>
<td>svrloc </td>
<td>服务位置协议（SLP） </td>
</tr>
<tr>
<td>434 </td>
<td>mobileip-agent </td>
<td>可移互联网协议（IP）代理 </td>
</tr>
<tr>
<td>435 </td>
<td>mobilip-mn </td>
<td>可移互联网协议（IP）管理器 </td>
</tr>
<tr>
<td>443 </td>
<td>https </td>
<td>安全超文本传输协议（HTTP） </td>
</tr>
<tr>
<td>444 </td>
<td>snpp </td>
<td>小型网络分页协议 </td>
</tr>
<tr>
<td>445 </td>
<td>microsoft-ds </td>
<td>通过 TCP/IP 的服务器消息块（SMB） </td>
</tr>
<tr>
<td>464 </td>
<td>kpasswd </td>
<td>Kerberos 口令和钥匙改换服务 </td>
</tr>
<tr>
<td>468 </td>
<td>photuris </td>
<td>Photuris 会话钥匙管理协议 </td>
</tr>
<tr>
<td>487 </td>
<td>saft </td>
<td>简单不对称文件传输（SAFT）协议 </td>
</tr>
<tr>
<td>488 </td>
<td>gss-http </td>
<td>用于 HTTP 的通用安全服务（GSS） </td>
</tr>
<tr>
<td>496 </td>
<td>pim-rp-disc </td>
<td>用于协议独立的多址传播（PIM）服务的会合点发现（RP-DISC） </td>
</tr>
<tr>
<td>500 </td>
<td>isakmp </td>
<td>互联网安全关联和钥匙管理协议（ISAKMP） </td>
</tr>
<tr>
<td>535 </td>
<td>iiop </td>
<td>互联网内部对象请求代理协议（IIOP） </td>
</tr>
<tr>
<td>538 </td>
<td>gdomap </td>
<td>GNUstep 分布式对象映射器（GDOMAP） </td>
</tr>
<tr>
<td>546 </td>
<td>dhcpv6-client </td>
<td>动态主机配置协议（DHCP）版本6客户 </td>
</tr>
<tr>
<td>547 </td>
<td>dhcpv6-server </td>
<td>动态主机配置协议（DHCP）版本6服务 </td>
</tr>
<tr>
<td>554 </td>
<td>rtsp </td>
<td>实时流播协议（RTSP） </td>
</tr>
<tr>
<td>563 </td>
<td>nntps </td>
<td>通过安全套接字层的网络新闻传输协议（NNTPS） </td>
</tr>
<tr>
<td>565 </td>
<td>whoami </td>
<td>whoami </td>
</tr>
<tr>
<td>587 </td>
<td>submission </td>
<td>邮件消息提交代理（MSA） </td>
</tr>
<tr>
<td>610 </td>
<td>npmp-local </td>
<td>网络外设管理协议（NPMP）本地 / 分布式排队系统（DQS） </td>
</tr>
<tr>
<td>611 </td>
<td>npmp-gui </td>
<td>网络外设管理协议（NPMP）GUI / 分布式排队系统（DQS） </td>
</tr>
<tr>
<td>612 </td>
<td>hmmp-ind </td>
<td>HMMP 指示 / DQS </td>
</tr>
<tr>
<td>631 </td>
<td>ipp </td>
<td>互联网打印协议（IPP） </td>
</tr>
<tr>
<td>636 </td>
<td>ldaps </td>
<td>通过安全套接字层的轻型目录访问协议（LDAPS） </td>
</tr>
<tr>
<td>674 </td>
<td>acap </td>
<td>应用程序配置存取协议（ACAP） </td>
</tr>
<tr>
<td>694 </td>
<td>ha-cluster </td>
<td>用于带有高可用性的群集的心跳服务 </td>
</tr>
<tr>
<td>749 </td>
<td>kerberos-adm </td>
<td>Kerberos 版本5（v5）的“kadmin”数据库管理 </td>
</tr>
<tr>
<td>750 </td>
<td>kerberos-iv </td>
<td>Kerberos 版本4（v4）服务 </td>
</tr>
<tr>
<td>765 </td>
<td>webster </td>
<td>网络词典 </td>
</tr>
<tr>
<td>767 </td>
<td>phonebook </td>
<td>网络电话簿 </td>
</tr>
<tr>
<td>873 </td>
<td>rsync </td>
<td>rsync 文件传输服务 </td>
</tr>
<tr>
<td>992 </td>
<td>telnets </td>
<td>通过安全套接字层的 Telnet（TelnetS） </td>
</tr>
<tr>
<td>993 </td>
<td>imaps </td>
<td>通过安全套接字层的互联网消息存取协议（IMAPS） </td>
</tr>
<tr>
<td>994 </td>
<td>ircs </td>
<td>通过安全套接字层的互联网中继聊天（IRCS） </td>
</tr>
<tr>
<td>995 </td>
<td>pop3s </td>
<td>通过安全套接字层的邮局协议版本3（POPS3） </td>
</tr>
</table>

### Unix特有的端口

以下端口是 UNIX 特有的，涉及了从电子邮件到验证不等的服务

在方括号内的名称（如 [service]）是服务的守护进程名称或它的常用别名

<table>
<tr>
<th>端口号码 / 层</th>
<th>名称</th>
<th>注释</th>
</tr>
<tr>
<td>512/tcp </td>
<td>exec </td>
<td>用于对远程执行的进程进行验证 </td>
</tr>
<tr>
<td>512/udp </td>
<td>biff [comsat] </td>
<td>异步邮件客户（biff）和服务（comsat） </td>
</tr>
<tr>
<td>513/tcp </td>
<td>login </td>
<td>远程登录（rlogin） </td>
</tr>
<tr>
<td>513/udp </td>
<td>who [whod] </td>
<td>登录的用户列表 </td>
</tr>
<tr>
<td>514/tcp </td>
<td>shell [cmd] </td>
<td>不必登录的远程 shell（rshell）和远程复制（rcp） </td>
</tr>
<tr>
<td>514/udp </td>
<td>syslog </td>
<td>UNIX 系统日志服务 </td>
</tr>
<tr>
<td>515 </td>
<td>printer [spooler] </td>
<td>打印机（lpr）假脱机 </td>
</tr>
<tr>
<td>517/udp </td>
<td>talk </td>
<td>远程对话服务和客户 </td>
</tr>
<tr>
<td>518/udp </td>
<td>ntalk </td>
<td>网络交谈（ntalk），远程对话服务和客户 </td>
</tr>
<tr>
<td>519 </td>
<td>utime [unixtime] </td>
<td>UNIX 时间协议（utime） </td>
</tr>
<tr>
<td>520/tcp </td>
<td>efs </td>
<td>扩展文件名服务器（EFS） </td>
</tr>
<tr>
<td>520/udp </td>
<td>router [route, routed] </td>
<td>选路信息协议（RIP） </td>
</tr>
<tr>
<td>521 </td>
<td>ripng </td>
<td>用于互联网协议版本6（IPv6）的选路信息协议 </td>
</tr>
<tr>
<td>525 </td>
<td>timed [timeserver] </td>
<td>时间守护进程（timed） </td>
</tr>
<tr>
<td>526/tcp </td>
<td>tempo [newdate] </td>
<td>Tempo </td>
</tr>
<tr>
<td>530/tcp </td>
<td>courier [rpc] </td>
<td>Courier 远程过程调用（RPC）协议 </td>
</tr>
<tr>
<td>531/tcp </td>
<td>conference [chat] </td>
<td>互联网中继聊天 </td>
</tr>
<tr>
<td>532 </td>
<td>netnews </td>
<td>Netnews </td>
</tr>
<tr>
<td>533/udp </td>
<td>netwall </td>
<td>用于紧急广播的 Netwall </td>
</tr>
<tr>
<td>540/tcp </td>
<td>uucp [uucpd] </td>
<td>Unix 到 Unix 复制服务 </td>
</tr>
<tr>
<td>543/tcp </td>
<td>klogin </td>
<td>Kerberos 版本5（v5）远程登录 </td>
</tr>
<tr>
<td>544/tcp </td>
<td>kshell </td>
<td>Kerberos 版本5（v5）远程 shell </td>
</tr>
<tr>
<td>548 </td>
<td>afpovertcp </td>
<td>通过传输控制协议（TCP）的 Appletalk 文件编制协议（AFP） </td>
</tr>
<tr>
<td>556 </td>
<td>remotefs [rfs_server, rfs] </td>
<td>Brunhoff 的远程文件系统（RFS） </td>
</tr>
</table>

### IANA注册的端口

列举了由网络和软件社区向 IANA 提交的要在端口号码列表中正式注册的端口

IANA(The Internet Assigned Numbers Authority，互联网数字分配机构)是负责协调一些使Internet正常运作的机构

<table>
<tr>
<th>端口号码 / 层</th>
<th>名称</th>
<th>注释</th>
</tr>
<tr>
<td>1080 </td>
<td>socks </td>
<td>SOCKS 网络应用程序代理服务 </td>
</tr>
<tr>
<td>1236 </td>
<td>bvcontrol [rmtcfg] </td>
<td>Garcilis Packeten 远程配置服务器</td>
</tr>
<tr>
<td>1300 </td>
<td>h323hostcallsc </td>
<td>H.323 电话会议主机电话安全 </td>
</tr>
<tr>
<td>1433 </td>
<td>ms-sql-s </td>
<td>Microsoft SQL 服务器 </td>
</tr>
<tr>
<td>1434 </td>
<td>ms-sql-m </td>
<td>Microsoft SQL 监视器 </td>
</tr>
<tr>
<td>1494 </td>
<td>ica </td>
<td>Citrix ICA 客户 </td>
</tr>
<tr>
<td>1512 </td>
<td>wins </td>
<td>Microsoft Windows 互联网名称服务器 </td>
</tr>
<tr>
<td>1524 </td>
<td>ingreslock </td>
<td>Ingres 数据库管理系统（DBMS）锁定服务 </td>
</tr>
<tr>
<td>1525 </td>
<td>prospero-np </td>
<td>无特权的 Prospero </td>
</tr>
<tr>
<td>1645 </td>
<td>datametrics [old-radius] </td>
<td>Datametrics / 从前的 radius 项目 </td>
</tr>
<tr>
<td>1646 </td>
<td>sa-msg-port [oldradacct] </td>
<td>sa-msg-port / 从前的 radacct 项目 </td>
</tr>
<tr>
<td>1649 </td>
<td>kermit </td>
<td>Kermit 文件传输和管理服务 </td>
</tr>
<tr>
<td>1701 </td>
<td>l2tp [l2f] </td>
<td>第2层隧道服务（LT2P） / 第2层转发（L2F） </td>
</tr>
<tr>
<td>1718 </td>
<td>h323gatedisc </td>
<td>H.323 电讯守门装置发现机制 </td>
</tr>
<tr>
<td>1719 </td>
<td>h323gatestat </td>
<td>H.323 电讯守门装置状态 </td>
</tr>
<tr>
<td>1720 </td>
<td>h323hostcall </td>
<td>H.323 电讯主持电话设置 </td>
</tr>
<tr>
<td>1758 </td>
<td>tftp-mcast </td>
<td>小文件 FTP 组播 </td>
</tr>
<tr>
<td>1759 </td>
<td>mtftp </td>
<td>组播小文件 FTP（MTFTP） </td>
</tr>
<tr>
<td>1789 </td>
<td>hello </td>
<td>Hello 路由器通信端口 </td>
</tr>
<tr>
<td>1812 </td>
<td>radius </td>
<td>Radius 拨号验证和记帐服务 </td>
</tr>
<tr>
<td>1813 </td>
<td>radius-acct </td>
<td>Radius 记帐 </td>
</tr>
<tr>
<td>1911 </td>
<td>mtp </td>
<td>Starlight 网络多媒体传输协议（MTP） </td>
</tr>
<tr>
<td>1985 </td>
<td>hsrp </td>
<td>Cisco 热备用路由器协议 </td>
</tr>
<tr>
<td>1986 </td>
<td>licensedaemon </td>
<td>Cisco 许可管理守护进程 </td>
</tr>
<tr>
<td>1997 </td>
<td>gdp-port </td>
<td>Cisco 网关发现协议（GDP） </td>
</tr>
<tr>
<td>2049 </td>
<td>nfs [nfsd] </td>
<td>网络文件系统（NFS） </td>
</tr>
<tr>
<td>2102 </td>
<td>zephyr-srv </td>
<td>Zephyr 通知传输和发送服务器 </td>
</tr>
<tr>
<td>2103 </td>
<td>zephyr-clt </td>
<td>Zephyr serv-hm 连接 </td>
</tr>
<tr>
<td>2104 </td>
<td>zephyr-hm </td>
<td>Zephyr 主机管理器 </td>
</tr>
<tr>
<td>2401 </td>
<td>cvspserver </td>
<td>并行版本系统（CVS）客户 / 服务器操作 </td>
</tr>
<tr>
<td>2430/tcp </td>
<td>venus </td>
<td>用于 Coda 文件系统（codacon 端口）的 Venus 缓存管理器 </td>
</tr>
<tr>
<td>2430/udp </td>
<td>venus </td>
<td>用于 Coda 文件系统（callback/wbc interface 界面）的 Venus 缓存管理器 </td>
</tr>
<tr>
<td>2431/tcp </td>
<td>venus-se </td>
<td>Venus 传输控制协议（TCP）的副作用 </td>
</tr>
<tr>
<td>2431/udp </td>
<td>venus-se </td>
<td>Venus 用户数据报协议（UDP）的副作用 </td>
</tr>
<tr>
<td>2432/udp </td>
<td>codasrv </td>
<td>Coda 文件系统服务器端口 </td>
</tr>
<tr>
<td>2433/tcp </td>
<td>codasrv-se </td>
<td>Coda 文件系统 TCP 副作用 </td>
</tr>
<tr>
<td>2433/udp </td>
<td>codasrv-se </td>
<td>Coda 文件系统 UDP SFTP 副作用 </td>
</tr>
<tr>
<td>2600 </td>
<td>hpstgmgr [zebrasrv] </td>
<td>HPSTGMGR；Zebra 选路</td>
</tr>
<tr>
<td>2601 </td>
<td>discp-client [zebra] </td>
<td>discp 客户；Zebra 集成的 shell </td>
</tr>
<tr>
<td>2602 </td>
<td>discp-server [ripd] </td>
<td>discp 服务器；选路信息协议守护进程（ripd） </td>
</tr>
<tr>
<td>2603 </td>
<td>servicemeter [ripngd] </td>
<td>服务计量；用于 IPv6 的 RIP 守护进程 </td>
</tr>
<tr>
<td>2604 </td>
<td>nsc-ccs [ospfd] </td>
<td>NSC CCS；开放式短路径优先守护进程（ospfd） </td>
</tr>
<tr>
<td>2605 </td>
<td>nsc-posa </td>
<td>NSC POSA；边界网络协议守护进程（bgpd） </td>
</tr>
<tr>
<td>2606 </td>
<td>netmon [ospf6d] </td>
<td>Dell Netmon；用于 IPv6 的 OSPF 守护进程（ospf6d） </td>
</tr>
<tr>
<td>2809 </td>
<td>corbaloc </td>
<td>公共对象请求代理体系（CORBA）命名服务定位器 </td>
</tr>
<tr>
<td>3130 </td>
<td>icpv2 </td>
<td>互联网缓存协议版本2（v2）；被 Squid 代理缓存服务器使用 </td>
</tr>
<tr>
<td>3306 </td>
<td>mysql </td>
<td>MySQL 数据库服务 </td>
</tr>
<tr>
<td>3346 </td>
<td>trnsprntproxy </td>
<td>Trnsprnt 代理 </td>
</tr>
<tr>
<td>4011 </td>
<td>pxe </td>
<td>执行前环境（PXE）服务 </td>
</tr>
<tr>
<td>4321 </td>
<td>rwhois </td>
<td>远程 Whois（rwhois）服务 </td>
</tr>
<tr>
<td>4444 </td>
<td>krb524 </td>
<td>Kerberos 版本5（v5）到版本4（v4）门票转换器 </td>
</tr>
<tr>
<td>5002 </td>
<td>rfe </td>
<td>无射频以太网（RFE）音频广播系统 </td>
</tr>
<tr>
<td>5308 </td>
<td>cfengine </td>
<td>配置引擎（Cfengine） </td>
</tr>
<tr>
<td>5999 </td>
<td>cvsup [CVSup] </td>
<td>CVSup 文件传输和更新工具 </td>
</tr>
<tr>
<td>6000 </td>
<td>x11 [X] </td>
<td>X 窗口系统服务 </td>
</tr>
<tr>
<td>7000 </td>
<td>afs3-fileserver </td>
<td>Andrew 文件系统（AFS）文件服务器 </td>
</tr>
<tr>
<td>7001 </td>
<td>afs3-callback </td>
<td>用于给缓存管理器回电的 AFS 端口 </td>
</tr>
<tr>
<td>7002 </td>
<td>afs3-prserver </td>
<td>AFS 用户和组群数据库 </td>
</tr>
<tr>
<td>7003 </td>
<td>afs3-vlserver </td>
<td>AFS 文件卷位置数据库 </td>
</tr>
<tr>
<td>7004 </td>
<td>afs3-kaserver </td>
<td>AFS Kerberos 验证服务 </td>
</tr>
<tr>
<td>7005 </td>
<td>afs3-volser </td>
<td>AFS 文件卷管理服务器 </td>
</tr>
<tr>
<td>7006 </td>
<td>afs3-errors </td>
<td>AFS 错误解释服务 </td>
</tr>
<tr>
<td>7007 </td>
<td>afs3-bos </td>
<td>AFS 基本监查进程 </td>
</tr>
<tr>
<td>7008 </td>
<td>afs3-update </td>
<td>AFS 服务器到服务器更新器 </td>
</tr>
<tr>
<td>7009 </td>
<td>afs3-rmtsys </td>
<td>AFS 远程缓存管理器服务 </td>
</tr>
<tr>
<td>9876 </td>
<td>sd </td>
<td>会话指引器 </td>
</tr>
<tr>
<td>10080 </td>
<td>amanda </td>
<td>高级 Maryland 自动网络磁盘归档器（Amanda）备份服务 </td>
</tr>
<tr>
<td>11371 </td>
<td>pgpkeyserver </td>
<td>良好隐私（PGP） / GNU 隐私卫士（GPG）公钥服务器 </td>
</tr>
<tr>
<td>11720 </td>
<td>h323callsigalt </td>
<td>H.323 调用信号交替 </td>
</tr>
<tr>
<td>13720 </td>
<td>bprd </td>
<td>Veritas NetBackup 请求守护进程（bprd） </td>
</tr>
<tr>
<td>13721 </td>
<td>bpdbm </td>
<td>Veritas NetBackup 数据库管理器（bpdbm） </td>
</tr>
<tr>
<td>13722 </td>
<td>bpjava-msvc </td>
<td>Veritas NetBackup Java / Microsoft Visual C++ (MSVC) 协议 </td>
</tr>
<tr>
<td>13724 </td>
<td>vnetd </td>
<td>Veritas 网络工具 </td>
</tr>
<tr>
<td>13782 </td>
<td>bpcd </td>
<td>Vertias NetBackup </td>
</tr>
<tr>
<td>13783 </td>
<td>vopied </td>
<td>Veritas VOPIED 协议 </td>
</tr>
<tr>
<td>22273 </td>
<td>wnn6 [wnn4] </td>
<td>假名/汉字转换系统</td>
</tr>
<tr>
<td>26000 </td>
<td>quake </td>
<td>Quake（以及相关的）多人游戏服务器 </td>
</tr>
<tr>
<td>26208 </td>
<td>wnn6-ds </td>
<td>&nbsp;</td>
</tr>
<tr>
<td>33434 </td>
<td>traceroute </td>
<td>Traceroute 网络跟踪工具 </td>
</tr>
<tr>
<td colspan="3">注:<br> /etc/services中的注释如下：端口1236被注册为“bvcontrol”，但是它也被 Gracilis Packeten 远程配置服务器使用。正式名称被列为主要名称，未注册的名称被列为别名。
<br>在/etc/services中的注释：端口 2600 到 2606 被 zebra 软件包未经注册而使用。主要名称是被注册的名称，被 zebra 使用的未注册名称被列为别名。
<br>/etc/services 文件中的注释：该端口被注册为 wnn6，但是还在 FreeWnn 软件包中使用了未注册的“wnn4”。<br></td>
</tr>
</table>

### 数据报传递协议端口

显示了一个和数据报传递协议（DDP）有关的端口列表。DDP 在 AppleTalk 网络上被使用

<table>
<tr>
<th>端口号码 / 层</th>
<th>名称</th>
<th>注释</th>
</tr>
<tr>
<td>1/ddp </td>
<td>rtmp </td>
<td>路由表管理协议 </td>
</tr>
<tr>
<td>2/ddp </td>
<td>nbp </td>
<td>名称绑定协议 </td>
</tr>
<tr>
<td>4/ddp </td>
<td>echo </td>
<td>AppleTalk Echo 协议 </td>
</tr>
<tr>
<td>6/ddp </td>
<td>zip </td>
<td>区块信息协议 </td>
</tr>
</table>

### Kerberos端口

和 Kerberos 网络验证协议相关的端口列表

在标记的地方，v5 代表 Kerberos 版本5协议

注意，这些端口没有在 IANA 注册

<table>
<tr>
<th>端口号码 / 层</th>
<th>名称</th>
<th>注释</th>
</tr>
<tr>
<td>751 </td>
<td>kerberos_master </td>
<td>Kerberos 验证 </td>
</tr>
<tr>
<td>752 </td>
<td>passwd_server </td>
<td>Kerberos 口令（kpasswd）服务器 </td>
</tr>
<tr>
<td>754 </td>
<td>krb5_prop </td>
<td>Kerberos v5 从属传播 </td>
</tr>
<tr>
<td>760 </td>
<td>krbupdate [kreg] </td>
<td>Kerberos 注册 </td>
</tr>
<tr>
<td>1109 </td>
<td>kpop </td>
<td>Kerberos 邮局协议（KPOP） </td>
</tr>
<tr>
<td>2053 </td>
<td>knetd </td>
<td>Kerberos 多路分用器 </td>
</tr>
<tr>
<td>2105 </td>
<td>eklogin </td>
<td>Kerberos v5 加密的远程登录（rlogin） </td>
</tr>
</table>

### 未注册的端口

一个未注册的端口列表

这些端口可能被安装在你的红帽企业 Linux 系统上的服务或协议使用，或者它们是在红帽企业 Linux 和运行其它操作系统的机器通信所必需的端口

<table>
<tr>
<th>端口号码 / 层</th>
<th>名称</th>
<th>注释</th>
</tr>
<tr>
<td>15/tcp </td>
<td>netstat </td>
<td>网络状态（netstat） </td>
</tr>
<tr>
<td>98/tcp </td>
<td>linuxconf </td>
<td>Linuxconf Linux 管理工具 </td>
</tr>
<tr>
<td>106 </td>
<td>poppassd </td>
<td>邮局协议口令改变守护进程（POPPASSD） </td>
</tr>
<tr>
<td>465/tcp </td>
<td>smtps </td>
<td>通过安全套接字层的简单邮件传输协议（SMTPS） </td>
</tr>
<tr>
<td>616/tcp </td>
<td>gii </td>
<td>使用网关的（选路守护进程）互动界面 </td>
</tr>
<tr>
<td>808 </td>
<td>omirr [omirrd] </td>
<td>联机镜像（Omirr）文件镜像服务 </td>
</tr>
<tr>
<td>871/tcp </td>
<td>supfileserv </td>
<td>软件升级协议（SUP）服务器 </td>
</tr>
<tr>
<td>901/tcp </td>
<td>swat </td>
<td>Samba 万维网管理工具（SWAT） </td>
</tr>
<tr>
<td>953 </td>
<td>rndc </td>
<td>Berkeley 互联网名称域版本9（BIND 9）远程名称守护进程配置工具 </td>
</tr>
<tr>
<td>1127 </td>
<td>sufiledbg </td>
<td>软件升级协议（SUP）调试 </td>
</tr>
<tr>
<td>1178/tcp </td>
<td>skkserv </td>
<td>简单假名到汉字（SKK）日文输入服务器 </td>
</tr>
<tr>
<td>1313/tcp </td>
<td>xtel </td>
<td>法国 Minitel 文本信息系统 </td>
</tr>
<tr>
<td>1529/tcp </td>
<td>support [prmsd, gnatsd] </td>
<td>GNATS 错误跟踪系统 </td>
</tr>
<tr>
<td>2003/tcp </td>
<td>cfinger </td>
<td>GNU Finger 服务 </td>
</tr>
<tr>
<td>2150 </td>
<td>ninstall </td>
<td>网络安装服务 </td>
</tr>
<tr>
<td>2988 </td>
<td>afbackup </td>
<td>afbackup 客户-服务器备份系统 </td>
</tr>
<tr>
<td>3128/tcp </td>
<td>squid </td>
<td>Squid 万维网代理缓存 </td>
</tr>
<tr>
<td>3455 </td>
<td>prsvp </td>
<td>RSVP 端口 </td>
</tr>
<tr>
<td>5432 </td>
<td>postgres </td>
<td>PostgreSQL 数据库 </td>
</tr>
<tr>
<td>4557/tcp </td>
<td>fax </td>
<td>FAX 传输服务（旧服务） </td>
</tr>
<tr>
<td>4559/tcp </td>
<td>hylafax </td>
<td>HylaFAX 客户-服务器协议（新服务） </td>
</tr>
<tr>
<td>5232 </td>
<td>sgi-dgl </td>
<td>SGI 分布式图形库 </td>
</tr>
<tr>
<td>5354 </td>
<td>noclog </td>
<td>NOCOL 网络操作中心记录守护进程（noclogd） </td>
</tr>
<tr>
<td>5355 </td>
<td>hostmon </td>
<td>NOCOL 网络操作中心主机监视 </td>
</tr>
<tr>
<td>5680/tcp </td>
<td>canna </td>
<td>Canna 日文字符输入界面 </td>
</tr>
<tr>
<td>6010/tcp </td>
<td>x11-ssh-offset </td>
<td>安全 Shell（SSH）X11 转发偏移 </td>
</tr>
<tr>
<td>6667 </td>
<td>ircd </td>
<td>互联网中继聊天守护进程（ircd） </td>
</tr>
<tr>
<td>7100/tcp </td>
<td>xfs </td>
<td>X 字体服务器（XFS） </td>
</tr>
<tr>
<td>7666/tcp </td>
<td>tircproxy </td>
<td>Tircproxy IRC 代理服务 </td>
</tr>
<tr>
<td>8008 </td>
<td>http-alt </td>
<td>超文本传输协议（HTTP）的另一选择 </td>
</tr>
<tr>
<td>8080 </td>
<td>webcache </td>
<td>万维网（WWW）缓存服务 </td>
</tr>
<tr>
<td>8081 </td>
<td>tproxy </td>
<td>透明代理 </td>
</tr>
<tr>
<td>9100/tcp </td>
<td>jetdirect [laserjet, hplj] </td>
<td>Hewlett-Packard (HP) JetDirect 网络打印服务 </td>
</tr>
<tr>
<td>9359 </td>
<td>mandelspawn [mandelbrot] </td>
<td>用于 X 窗口系统的并行 Mandelbrot 生成程序 </td>
</tr>
<tr>
<td>10081 </td>
<td>kamanda </td>
<td>使用 Kerberos 的 Amanda 备份服务 </td>
</tr>
<tr>
<td>10082/tcp </td>
<td>amandaidx </td>
<td>Amanda 备份服务 </td>
</tr>
<tr>
<td>10083/tcp </td>
<td>amidxtape </td>
<td>Amanda 备份服务 </td>
</tr>
<tr>
<td>20011 </td>
<td>isdnlog </td>
<td>综合业务数字网（ISDN）登录系统 </td>
</tr>
<tr>
<td>20012 </td>
<td>vboxd </td>
<td>ISDN 音箱守护进程（vboxd） </td>
</tr>
<tr>
<td>22305/tcp </td>
<td>wnn4_Kr </td>
<td>kWnn 韩文输入系统 </td>
</tr>
<tr>
<td>22289/tcp </td>
<td>wnn4_Cn </td>
<td>cWnn 中文输入系统 </td>
</tr>
<tr>
<td>22321/tcp </td>
<td>wnn4_Tw </td>
<td>tWnn 中文输入系统（台湾） </td>
</tr>
<tr>
<td>24554 </td>
<td>binkp </td>
<td>Binkley TCP/IP Fidonet 邮寄程序守护进程 </td>
</tr>
<tr>
<td>27374 </td>
<td>asp </td>
<td>地址搜索协议 </td>
</tr>
<tr>
<td>60177 </td>
<td>tfido </td>
<td>Ifmail FidoNet 兼容邮寄服务 </td>
</tr>
<tr>
<td>60179 </td>
<td>fido </td>
<td>FidoNet 电子邮件和新闻网络 </td>
</tr>
</table>



