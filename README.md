# Control-Unit-LPC1768-NXP-
LPC1768 adalah microcontroller berbasis ARM Cortex-M3 yang dikembangkan oleh NXP Semiconductors. Chip ini sering digunakan dalam sistem tertanam (embedded systems), otomasi industri, dan aplikasi IoT karena memiliki kecepatan tinggi, efisiensi daya, serta fitur komunikasi yang lengkap seperti UART, SPI, I2C, CAN, USB, dan Ethernet.


**Gambar LPC1768**
![mbed-nxp-lpc1768 (1)](https://github.com/user-attachments/assets/57b8e8ca-e290-427e-9f46-1ae6a2529724)


# Keunggulan LPC1768
**1. Performa Tinggi**

   
   Dengan kecepatan 100 MHz, microcontroller ini sangat cocok untuk aplikasi real-time dan embedded.
   
**2. Banyak Interface Komunikasi**

   
   Mendukung UART, SPI, I2C, CAN, USB, dan Ethernet, sehingga bisa digunakan dalam berbagai aplikasi industri.
   
**3. Mendukung ADC & DAC**

   
   Memiliki 8-channel ADC (12-bit) dan 1-channel DAC (10-bit), berguna untuk aplikasi sensor dan kontrol analog.
   
**4. Bisa Digunakan di mbed OS**

   
   Kompatibel dengan mbed OS, platform pemrograman IoT berbasis cloud dari ARM.
   
**5. Efisiensi Daya**

    
   Cocok untuk sistem low-power dengan berbagai mode sleep untuk menghemat energi.

# Jenis-Jenis LPC1768 dan Variannya
LPC1768 adalah bagian dari keluarga **LPC17xx**, yang memiliki beberapa varian dengan fitur yang sedikit berbeda. Berikut beberapa varian utama:

**A. LPC176x Series (Cortex-M3, 100 MHz, High Performance)**

Seri ini ditujukan untuk aplikasi embedded dan otomasi industri dengan performa tinggi.


**LPC1768** – Model paling populer dengan Ethernet, USB, CAN, ADC, DAC, dan PWM.

**LPC1769** – Versi overclocked dari LPC1768, dengan clock speed hingga 120 MHz.

**LPC1767** – Mirip dengan LPC1768 tetapi tanpa Ethernet.

**LPC1766** – Versi lebih murah dari LPC1768, tanpa USB dan memori Flash lebih kecil.

**LPC1765** – Sama dengan LPC1766 tetapi memiliki fitur USB Device/Host/OTG.

**LPC1764** – Paling sederhana dalam seri ini, tanpa Ethernet dan USB.



**B. LPC175x Series (Cortex-M3, 100 MHz, Mid-Range)**

Seri ini memiliki fitur lebih sedikit dibandingkan LPC176x, cocok untuk aplikasi yang tidak memerlukan Ethernet.


**LPC1759** – Versi tertinggi dengan 512 KB Flash dan USB.

**LPC1758** – Mirip dengan LPC1759 tetapi tanpa Ethernet.

**LPC1756** – Memori Flash lebih kecil (256 KB) dan tanpa Ethernet.

**LPC1754 & LPC1752** – Versi dengan fitur terbatas untuk aplikasi sederhana.



**C. LPC17xx Variasi untuk Aplikasi Khusus**


**LPC177x/8x Series** – Versi upgrade dengan LCD controller dan fitur grafik, cocok untuk HMI dan display embedded.

**LPC178x** – Memiliki Touchscreen Controller, cocok untuk GUI dan sistem navigasi.


    
