### L-CARD E14 & E-502 + python 👋
+ Библиотеки: ctypes, usb1
+ Протестировано на платах: E14-440, E14-440D, E-502
+ Python 2.7 32 bit:
  + lct2_e14_adc.py: пример работы АЦП E14 используя функции RequestBufferStream, FillDAQparameters и SetParametersStream для усиления 10, с опросом 16 каналов с частотой АЦП 400 кГц.
+ Python 3.8.6 32 bit:
  + lcio3_adc.py: пример работы АЦП E14 используя функцию IoAsync для 4-х усилений (10, 2.5, 0.625, 0.1562);
  + lcio3_dac.py: пример работы ЦАП E14 используя функцию IoAsync;
  + lct3_e14_adc.py: тоже что и lct2_e14_adc.py
  + lct3_e502.py: пример работы ЦАП E-502
  + e502_libusb1.py: пример работы АЦП E-502 используя низкоуровневое описание
