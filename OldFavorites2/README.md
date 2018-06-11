#  [Forensics 50] Old Favorites 2

Audio File Stego Challenge

## How it works

The binary representation from the previous file was changed. In this file the LSB of each line starting at line 974:8CAFh: has been changed to include a flag spelled out in binary.

## How to solve it

Using 010 Editor the compare files tool can be used to find the string of changed binary digits which when converted to ascii read the flag 'sun{dont_3e_blind}'

## Link to video

https://drive.google.com/file/d/1YmMzYRhZOJyDz2JTDN5Bz45b48SPM1nd/view?usp=sharing
