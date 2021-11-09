### L-CARD E14 & E-502 + python 👋
+ Библиотеки: ctypes, usb1
+ Протестировано на платах: E14-440, E14-440D, E-502
+ Python 2.7:
  + lcio.py: пример работы с АЦП используя функцию IoAsync для 4-х усилений (1, 4, 16, 64);
  + lcio2.py: пример работы с ЦАП используя функцию IoAsync;
  + lct2_e14.py: пример работы с АЦП используя функции RequestBufferStream, FillDAQparameters и SetParametersStream для усиления 1, с опросом 16 каналов с частотой АЦП 400 кГц.
+ Python 3.8.2:
  + lct3_e14.py:
  + lct3_e502.py:
  + e502_libusb1.py:
