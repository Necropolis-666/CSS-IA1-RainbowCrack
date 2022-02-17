# CSS-IA1-RainbowCrack
CSS IA 1, RainBrowCrack
Made by 
Swastik kar
Mitali Sharma
Rainbow tables:-
The rainbow tables were can be generated using either the command prompt, or using some softfare such as Winrtgen

The code run in command prompt was--

Microsoft Windows [Version 10.0.19043.1526]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Swastik>cd Desktop

C:\Users\Swastik\Desktop>cd RainbowCrack

C:\Users\Swastik\Desktop\RainbowCrack>rtgen
RainbowCrack 1.8
Copyright 2020 RainbowCrack Project. All rights reserved.
http://project-rainbowcrack.com/

usage: rtgen hash_algorithm charset plaintext_len_min plaintext_len_max table_index chain_len chain_num part_index
       rtgen hash_algorithm charset plaintext_len_min plaintext_len_max table_index -bench

hash algorithms implemented:
    lm HashLen=8 PlaintextLen=0-7
    ntlm HashLen=16 PlaintextLen=0-15
    md5 HashLen=16 PlaintextLen=0-15
    sha1 HashLen=20 PlaintextLen=0-20
    sha256 HashLen=32 PlaintextLen=0-20

examples:
    rtgen md5 loweralpha 1 7 0 1000 1000 0
    rtgen md5 loweralpha 1 7 0 -bench

C:\Users\Swastik\Desktop\RainbowCrack>rtgen md5 numeric 3 8 0 240 4000000 0
rainbow table md5_numeric#3-8_0_240x4000000_0.rt parameters
hash algorithm:         md5
hash length:            16
charset name:           numeric
charset data:           0123456789
charset data in hex:    30 31 32 33 34 35 36 37 38 39
charset length:         10
plaintext length range: 3 - 8
reduce offset:          0x00000000
plaintext total:        111111000

sequential starting point begin from 0 (0x0000000000000000)
generating...
262144 of 4000000 rainbow chains generated (0 m 1.8 s)
524288 of 4000000 rainbow chains generated (0 m 1.7 s)
786432 of 4000000 rainbow chains generated (0 m 1.7 s)
1048576 of 4000000 rainbow chains generated (0 m 1.8 s)
1310720 of 4000000 rainbow chains generated (0 m 1.7 s)
1572864 of 4000000 rainbow chains generated (0 m 1.7 s)
1835008 of 4000000 rainbow chains generated (0 m 1.8 s)
2097152 of 4000000 rainbow chains generated (0 m 1.8 s)
2359296 of 4000000 rainbow chains generated (0 m 1.8 s)
2621440 of 4000000 rainbow chains generated (0 m 1.8 s)
2883584 of 4000000 rainbow chains generated (0 m 1.8 s)
3145728 of 4000000 rainbow chains generated (0 m 1.9 s)
3407872 of 4000000 rainbow chains generated (0 m 1.9 s)
3670016 of 4000000 rainbow chains generated (0 m 1.9 s)
3932160 of 4000000 rainbow chains generated (0 m 1.8 s)
4000000 of 4000000 rainbow chains generated (0 m 0.5 s)

C:\Users\Swastik\Desktop\RainbowCrack>rtsort .
.\md5_numeric#3-5_0_240x4000000_oxid#000.rt:
3072692224 bytes memory available
loading data...
sorting data...
writing sorted data...

.\md5_numeric#3-8_0_240x4000000_0.rt:
3162886144 bytes memory available
loading data...
sorting data...
writing sorted data...


C:\Users\Swastik\Desktop\RainbowCrack>
