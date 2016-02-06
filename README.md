AVRxPROG
========

AVRxPROG is a Windows full software to download intel HEX files to AVR 8 (mega/xmega) processors.

* Instalation

Please, goto to release folder and download the required version based on your Operational System (OS).

Note: Some machines need Visual Studio 2015 C++ Runtime libraries first time. This library can be download at 
http://www.microsoft.com/en-us/download/details.aspx?id=48145

* Device Support

The AVRxPROG uses Atmel Studio 5.x/6.x/7.x XML device specification to download the HEX files. So, any device
can be used even if Atmel add new devices. The AVRxPROG find automatically the must current version of
Atmel Studio in your PC.

Another options is copy the XML/ATDF device specification and put into devices folder in AVRxPROG installation directory.
Example:

	c:\Program Files\AVRxPROG\devices\<my avr>.xml
	c:\Program Files\AVRxPROG\devices\<my avr>.atdf
