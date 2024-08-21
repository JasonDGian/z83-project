# :pushpin: Detailed Hardware Analysis
In this document, I provide an overview of some general information, along with more in-depth and detailed insights about specific components found on the device's board. Please note that some of the information may be redundant, and there might be slight inaccuracies in the details.
   
## 📍 The device itself.
The package includes instructions, an HDMI cable, a power supply, and a mounting bracket, which is particularly useful for attaching the unit behind a monitor using a VESA mounting system or for mounting it on the wall. This is how the device looks from the outside.   

<p align="center">
<img width="800px" src="https://github.com/user-attachments/assets/e08eeedc-fbfa-4628-b708-f16617647897"> 
</p>
<p align="center">
<img width="200px" src="https://github.com/user-attachments/assets/d5d5cbc3-a5b2-4c9b-824a-289a94f84530">   
<img width="200px" src="https://github.com/user-attachments/assets/dd09755c-f060-4dd9-97b7-e36854786a52"> 
<img width="200px" src="https://github.com/user-attachments/assets/ce779df7-2cc8-4264-bcb8-7e905e70a64e">
<img width="200px" src="https://github.com/user-attachments/assets/0c780f74-23d0-4845-8fe7-8b9c3b89a3dc"> 
</p>

---

## 📍 Official specifications.
These are the official specifications for the device, as printed on the box.<center>
<table>
<tr>
   <th>Element</th>
   <th>Description</th>
</tr>
<tr>
   <td>Processor</td>
   <td>Intel Atom x5-Z8350 (2M Cache 1.92GHz)</td>
</tr>
<tr>
   <td>GPU</td>
   <td>Intel HD Grapchis 400</td>
</tr>
<tr>
   <td>Memory</td>
   <td>DDR3 4GB</td>
</tr>
<tr>
   <td>Storage</td>
   <td>64GB eMMC</td>
</tr>
<tr>
   <td>Expansions</td>
   <td> 1 SD Card Slot (limit 128GB)</td>
</tr>
<tr>
   <td>Wireless Connectivity</td>
   <td>IEEE 802.11ac Dual-band Wi-Fi, Bluetooth</td>
</tr>
<tr>
   <td>Video output</td>
   <td>1x HDMI + 1x VGA</td>
</tr>
<tr>
   <td>Audio output</td>
   <td>HDMI, 3.5mm Audio jack</td>
</tr>
<tr>
   <td>Peripherals Interface</td>
   <td>RJ45 Gbit Eth, Port x1 USB 3.0 , Port x2 USB 2.0 </td>
</tr>
<tr>
   <td>Power input</td>
   <td>DC 12v jack</td>
</tr>
</table>
   
---

## 📍 The board.
As I examined the board, I started by gathering information about its components, keeping in mind my limited experience as a hobbyist. Below is a detailed list of the elements I identified on this particular board, as well as the board itself.
Here are two pictures of the board from top and bottom.   
<p align="center">
   <img width="500px" src="https://github.com/user-attachments/assets/741e528a-f210-4b78-8e00-0d0bb60bde43">
   <img width="500px" src="https://github.com/user-attachments/assets/0c0785cd-02ea-41ee-9494-d15b38486834">
</p> 
    
---  
     
## 📍 SOC Processor.
This processor is a System on Chip (SoC), integrating multiple critical components into a single chip. It combines the CPU, graphics processor, I/O controller, and other essential functions.   
- Integrated Intel HD Graphics 400.
- Supports DirectX 11.2, OpenGL 4.3, and OpenCL 1.2
- Supports DDR3L or LPDDR3 memory, up to 1866 MT/s.


>[!NOTE]
> In theory, the processor only is capable of handling 2GB of RAM, but paired with the right memory it actually handles up to 8GB with no problem.

<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td> Intel Atom® Processor X Series  x5-Z8350</td>
                          </tr>
                          <tr>
                                  <td>Frequency</td>
                                  <td> 1.44GHz - 1.92GHz</td>
                          </tr>
                          <tr>
                                  <td>Cores - Threads</td>
                                  <td>4 - 1</td>
                          </tr>
                          <tr>
                                  <td>Secure boot.</td>
                                  <td>YES</td>
                          </tr>
                          <tr>
                                  <td>Instruction set.</td>
                                  <td>64-bit</td>
                          </tr>
                          <tr>
                                  <td>Cache</td>
                                  <td>2MB L2</td>
                          </tr>
                          <tr>
                                  <td>SDP</td>
                                  <td>2W</td>
                          </tr>
                          <tr>
                                  <td>Lithography.</td>
                                  <td>14nm</td>
                          </tr>
                          <tr>
                                  <td>Max Memory Size (dependent on memory type).</td>
                                  <td>2 GB</td>
                          </tr>
                          <tr>
                                  <td>Graphics frequency.</td>
                                  <td>200MHz - 500MHz</td>
                          </tr>
                          <tr>
                                  <td>Graphics Max Memory.</td>
                                  <td>2GB</td>
                          </tr>
                          <tr>
                                  <td>Graphics Max Resolution.</td>
                                  <td>1920*1080</td>
                          </tr>
                          <tr>
                                  <td>Number of Supported displays.</td>
                                  <td>2</td>
                          </tr>
                          <tr>
                                  <td>PCI Express Revision.</td>
                                  <td>2</td>
                          </tr>
                          <tr>
                                  <td>USB Revision.</td>
                                  <td>3</td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src="https://github.com/user-attachments/assets/92bdd133-4d47-40b5-be32-e99cf6d571b5"></p>
                  <p align="center" > <a href="https://ark.intel.com/content/www/us/en/ark/products/93361/intel-atom-x5-z8350-processor-2m-cache-up-to-1-92-ghz.html">Official site<a/></p>  
          </td>
      </tr>
</table>
   
---  
   
## 📍 Storage.
This is the main storage on the device. Extremely small in size but packs 64GB capacity.

<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td>Biwin  qNand BWCTASC21P64G.   </td>
                          </tr>
                          <tr>
                                  <td>Interface</td>
                                  <td> eMMC 5.0 / eMMC 5.1 </td>
                          </tr>
                          <tr>
                                  <td>Dimensions</td>
                                  <td>11.50 × 13.00 mm, 7.50 × 8.00 mm, 7.5 × 12.50 mm, 9.00×10.00 mm </td>
                          </tr>
                          <tr>
                                  <td>Max. Sequential Read</td>
                                  <td>300 MB/s </td>
                          </tr>
                          <tr>
                                  <td>Max. Sequential Write</td>
                                  <td> 240 MB/s </td>
                          </tr>
                          <tr>
                                  <td>Capacity</td>
                                  <td> 64GB </td>
                          </tr>
                          <tr>
                                  <td>Working Temperature</td>
                                  <td>-20℃ - 85℃ </td>
                          </tr>
                          <tr>
                                  <td>Packaging</td>
                                  <td>FBGA153</td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src="https://github.com/user-attachments/assets/95b8750f-5d7d-4ed4-b93f-3b29dacb5d36"></p>
                  <p align="center" > <a href="https://en.biwin.com.cn/product/detail/6">Official site<a/></p>  
          </td>
      </tr>
</table>
   
---  
   
## 📍 Memory.
LPDDR3 Memory flash chip.   
This memory component is part of the series with no specific name but is designed to provide high-quality and reliable memory performance.
<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td>DDR Memory Chip - 943060-K3QF0F00AM-FGCF</td>
                          </tr>
                          <tr>
                                  <td>Type</td>
                                  <td>DDR SDRAMDDR SDRAM</td>
                          </tr>
                          <tr>
                                  <td>Frequency</td>
                                  <td>1866MHz</td>
                          </tr>
                          <tr>
                                  <td>Manufacturer</td>
                                  <td>Samsung Electronics Co., Ltd.</td>
                          </tr>
                          <tr>
                                  <td>Packaging</td>
                                  <td>FBGA-256</td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src="https://github.com/user-attachments/assets/d24dd69a-a759-4ae2-8e2b-050b4d8cf0f2"></p>
                  <p align="center" > <a href="https://datasheets.globalspec.com/ds/samsung-electronics/k3qf0f00am-fgcf/67e2211b-eb90-47ce-88f7-93c25d902be7">Product site<a/></p>  
          </td>
      </tr>
</table>
   
---  
   
## 📍 Lan Network Interface.
RTL8111F Integrated Gigabit Ethernet controller for PCI Express applications.
The RTL8111F is a Gigabit Ethernet controller designed for PCI Express, offering high network performance and efficiency. It supports various features like NDIS5/6, checksum offloading, VLAN, and Receive-Side Scaling (RSS), which reduce CPU usage and improve network throughput. It uses PCI Express technology, providing better performance than conventional PCI while remaining compatible with existing infrastructure. This controller is versatile, making it suitable for desktops, servers, workstations, and embedded systems.
    
<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td>Realtek  **RTL8111F**  Gigabit  Ethernet  controller </td>
                          </tr>
                          <tr>
                                  <td>Type</td>
                                  <td>Ethernet controller</td>
                          </tr>
                          <tr>
                                  <td>Speed</td>
                                  <td>10/100/1000Mbps</td>
                          </tr>
                          <tr>
                                  <td>Manufacturer</td>
                                  <td>Realtek Semiconductor Corp.</td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src="https://github.com/user-attachments/assets/cdbdb787-3808-40d6-9b3a-2db431651a75"></p>
                  <p align="center" > <a href="https://www.alldatasheet.com/datasheet-pdf/pdf/1222184/REALTEK/RTL8111F.html">Datasheet<a/></p>  
          </td>
      </tr>
</table>
   
---  

## 📍 Wireless Network Interface.
WiFi 11ac + Bluetooth V4.2 module.
The wireless module complies with IEEE 802.11 a/b/g/n/ac standard and it can achieve up
to a speed of 433.3Mbps with single stream in 802.11ac draft to connect to the wireless LAN.
The integrated module provides SDIO interface for Wi-Fi, UART / PCM interface for
Bluetooth.
- Concurrent Bluetooth, and WLAN operation
<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td>AMPAK Tech AP6255 </td>
                          </tr>
                          <tr>
                                  <td>Type</td>
                                  <td>Support Wi-Fi/Bluetooth functionalities</td>
                          </tr>
                          <tr>
                                  <td>WiFi interface.</td>
                                  <td>SDIO v2.0 / v3.0</td>
                          </tr>
                          <tr>
                                  <td>Bluetooth Interface</td>
                                  <td>UART / PCM</td>
                          </tr>
                          <tr>
                                  <td>Frequency</td>
                                  <td>2.4GHz</td>
                          </tr>
                          <tr>
                                  <td>Operating temperature</td>
                                  <td>-30℃~+85℃</td>
                          </tr>
                          <tr>
                                  <td>Speed</td>
                                  <td>Up to 433.3Mbps</td>
                          </tr>
                          <tr>
                                  <td>Support Interface</td>
                                  <td>On-Board PCB Antenna</td>
                          </tr>
                          <tr>
                                  <td>Manufacturer</td>
                                  <td>AMPAK Tech</td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src="https://github.com/user-attachments/assets/1ca800ca-1221-4200-a09e-737ed33d607c"></p>
                  <p align="center" > <a href="https://www.lcsc.com/datasheet/lcsc_datasheet_2202221430_AMPAK-Tech-AP6255_C2687149.pdf">Datasheet<a/></p>  
          </td>
      </tr>
</table>
   
---  
   
## 📍 Sound card.
The ALC5651 is a high performance, low power, dual I2S interface audio CODEC.
    
<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td>ALC-5651</td>
                          </tr>
                          <tr>
                                  <td>Type</td>
                                  <td>Ultra-Low Power Two-Channel Audio CODEC   </td>
                          </tr>
                          <tr>
                                  <td>Manufacturer</td>
                                  <td>Realtek Semiconductor Corp.</td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src="https://github.com/user-attachments/assets/0c6964d4-5405-4278-b9e1-825af2b2c8f1"></p>
                  <p align="center" > <a href="https://pdf1.alldatasheet.com/datasheet-pdf/view/1132330/REALTEK/ALC5651.html">Official site<a/></p>  
          </td>
      </tr>
</table>

---  
   
## 📍 Power management IC.
PMIC Optimized for Multi-core high-performance system. This PMIC is customized for Intel Cherry Trail platforms.
    
<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td>APX288C</td>
                          </tr>
                          <tr>
                                  <td>Type</td>
                                  <td>Power management IC</td>
                          </tr>
                          <tr>
                                  <td>Manufacturer</td>
                                  <td>X-powers</td>
                          </tr>
                          <tr>
                                  <td>Packaging</td>
                                  <td>76-pin QFN</td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src="https://github.com/user-attachments/assets/a3b8a654-cb23-4eb5-8638-6b890b61be83"></p>
                  <p align="center" > <a href="https://dl.radxa.com/rockpix/docs/hw/AXP288C-X-Powers.pdf">Datasheet<a/></p>  
          </td>
      </tr>
</table>
   
---  


## 📍 Firmware chip or bios.
Code Storage Flash Memory: This chip is widely used in consumer electronics, automotive, and industrial applications for firmware storage, data logging, and more.
    
<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td>Winbond - 25Q64FWSIQ</td>
                          </tr>
                          <tr>
                                  <td>Type</td>
                                  <td>ROM chip for firmware </td>
                          </tr>
                          <tr>
                                  <td>Frequency</td>
                                  <td>104MHz</td>
                          </tr>
                          <tr>
                                  <td>Temperature range</td>
                                  <td>-40℃ ~ 85℃ / -40℃ ~ 105℃</td>
                          </tr>
                          <tr>
                                  <td>Manufacturer</td>
                                  <td>WinBond</td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src="https://github.com/user-attachments/assets/cd94e5b1-1e3c-49ee-90a1-9226229f4b51"></p>
                  <p align="center" > <a href="https://www.winbond.com/hq/product/code-storage-flash-memory/serial-nor-flash/?__locale=en&partNo=W25Q64FW">Datasheet<a/></p>  
          </td>
      </tr>
</table>
   
---  

## 📍 WiFi Antenna.
This antenna serves both WiFi and Bluetooth functions, as it is connected to and controlled by the same device. The antenna is attached to the board using a drop of hot glue and a piece of black rubber or foam secured with double-sided tape. I detached the antenna from the board and removed the black foam material to inspect the reverse side. There is no controller or any logic management chip present; it functions purely as an antenna.

<p align="center">
<img width="800px" src="https://github.com/user-attachments/assets/c102911e-3a95-42ae-8e18-e440f4edf494"> 
</p>
<p align="center">
   <img width="275px" src="https://github.com/user-attachments/assets/631413da-7754-4190-b0ff-e3f21d2e0842">    
   <img width="275px" src="https://github.com/user-attachments/assets/9d87d33c-f929-4d48-8acb-b7cd4f2a36c9">
   <img width="275px" src="https://github.com/user-attachments/assets/6c14b93d-6217-45c4-a454-876315cf1e50">
</p>

   
---  



