BIOS binaries for Lenovo T440P

The Lenovo T440P BIOS is contained in two rom chips: [W25Q64.V](https://www.pjrc.com/store/w25q64fv.pdf) and [W25Q32.V](https://www.elinux.org/images/f/f5/Winbond-w25q32.pdf), which are 8MB(8192 KB) and 4MB(4096 kB) respectively.  

[CH341A Flash Programmer](https://tinyurl.com/ch341aEbay) used to interface over SPI.  

-- 4MB_BIOS.bin (W25Q32.V - 4096 KB)  
-- 8MB_BIOS.bin (W25Q64.V - 8192 KB)  
-- FULL_BIOS.bin  
   ```bash 
   cat 8MB_BIOS.bin 4MB_BIOS.bin > FULL_BIOS.bin
   ```
