# MPAS files and issue log file
ecmwf_coeffs is coefficients what I use to run calc_ecmwf_p.exe.
log.init_atmosphere.0000.out_ec_init is a log file of creating the initial condition file.
log.init_atmosphere.0000.out_ec_lbcs is a log file of creating the LBCs files.
namelist.atmosphere and streams.atmosphere are used to run atmosphere_model.
log.atmosphere.0000.out is a log file of running atmosphere_model.
Then, it shows:

forrtl: severe (174): SIGSEGV, segmentation fault occurred
Image              PC                Routine            Line        Source
atmosphere_model   00000000010B4A3D  for__signal_handl     Unknown  Unknown
libpthread-2.17.s  00002B2C43E095F0  Unknown               Unknown  Unknown
atmosphere_model   0000000000749B09  Unknown               Unknown  Unknown
atmosphere_model   00000000007298AA  Unknown               Unknown  Unknown
atmosphere_model   000000000072432D  Unknown               Unknown  Unknown
atmosphere_model   0000000000718083  Unknown               Unknown  Unknown

Stack trace terminated abnormally.
atmosphere_model   0000000000412D6E  Unknown               Unknown  Unknown
atmosphere_model   0000000000412D1E  Unknown               Unknown  Unknown
libc-2.17.so       00002B5B52593505  __libc_start_main     Unknown  Unknown
atmosphere_model   0000000000412C29  Unknown               Unknown  Unknown
forrtl: severe (174): SIGSEGV, segmentation fault occurred
Image              PC                Routine            Line        Source
atmosphere_model   00000000010B4A3D  for__signal_handl     Unknown  Unknown
libpthread-2.17.s  00002BA1E5D035F0  Unknown               Unknown  Unknown
atmosphere_model   0000000000749B09  Unknown               Unknown  Unknown
atmosphere_model   00000000007298AA  Unknown               Unknown  Unknown
atmosphere_model   000000000072432D  Unknown               Unknown  Unknown
atmosphere_model   0000000000718083  Unknown               Unknown  Unknown
atmosphere_model   00000000005AB2EC  Unknown               Unknown  Unknown

Stack trace terminated abnormally.
forrtl: severe (174): SIGSEGV, segmentation fault occurred
Image              PC                Routine            Line        Source
atmosphere_model   00000000010B4A3D  for__signal_handl     Unknown  Unknown
libpthread-2.17.s  00002B91DAD855F0  Unknown               Unknown  Unknown
atmosphere_model   00000000007972F6  Unknown               Unknown  Unknown
atmosphere_model   000000000078270E  Unknown               Unknown  Unknown
atmosphere_model   000000000077F1A0  Unknown               Unknown  Unknown
atmosphere_model   000000000077BC4E  Unknown               Unknown  Unknown
atmosphere_model   0000000000771D5B  Unknown               Unknown  Unknown
atmosphere_model   00000000005BFFDA  Unknown               Unknown  Unknown
atmosphere_model   0000000000585DFF  Unknown               Unknown  Unknown
atmosphere_model   00000000004EAD59  Unknown               Unknown  Unknown
atmosphere_model   0000000000412DD5  Unknown               Unknown  Unknown
