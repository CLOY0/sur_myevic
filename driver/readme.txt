
usbser.sys is required for USB Virtual COM device.
It is included by windows operation system and could be found at \WINDOWS\system32\drivers
or \i386\driver.cab

To install the VCOM driver, user must find usbser.sys on their OS first and copy it to the 
same directory with Nuvoton CDC INF file. Finally install the driver manually when windows 
request to install the VCOM device driver.

************

��� ������������ LDRom (���������) ����� ��������������� ����� ��������.
�������������� �������� ��� ����������� �������� ��� �����, ����� ���.
https://gist.github.com/ReservedField/6125e9c7d2b9f92536ee
������� �������� ldrom_dump.bin �����������.
������ ��� �������� � ���, � ����-������.
�� ������ ���� ����� �������: �������� ������������ ��������� � ������� ����.

��� ���� ����� ������ ���������� ������������ com-�����, ����������� �������.
���������� �������� � ��������� VID � PID ���������� ����������.
���������, ��� � ����� NuvotonCDC.inf ��������� ��� �� VID � PID, ���� ��� - ��������.
����� � ������� usbser.sys, ����������� ��� � ����� � ����� NuvotonCDC.inf, 
������� ������� (������ ���) �� NuvotonCDC.inf ���� ��� ��������� ��������.
 
� ������� �������� ����� com-����, ������� ������������ ��������� (�������� putty),
��������� � ���������� � ����� ������ �����. ��������� ��������� �� ���������.

������ ���� �� ���� - � ���� ������������ ��������� ��������� ���������� ldrom, 
����������� ��� � ������� ����-��������� � ��������.
������ ����������� �� RX23 ����� rx23_ldrom_data.bin �����������.