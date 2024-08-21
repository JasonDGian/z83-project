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
                                  <td>Frequency</td>
                                  <td></td>
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
                  <p align="center"> <img align="right" height="190px" src=""></p>
                  <p align="center" > <a href="https://dl.radxa.com/rockpix/docs/hw/AXP288C-X-Powers.pdf">Datasheet<a/></p>  
          </td>
      </tr>
</table>
   
---  


## 📍 Title.
Description.
    
<table>
      <tr>
          <td> 
                  <table>
                          <tr>
                                  <td>Name</td>
                                  <td></td>
                          </tr>
                          <tr>
                                  <td>Type</td>
                                  <td></td>
                          </tr>
                          <tr>
                                  <td>Frequency</td>
                                  <td></td>
                          </tr>
                          <tr>
                                  <td>Manufacturer</td>
                                  <td></td>
                          </tr>
                          <tr>
                                  <td>Packaging</td>
                                  <td></td>
                          </tr>
                  </table> 
          </td>
          <td>
                  <p align="center"> <img align="right" height="190px" src=""></p>
                  <p align="center" > <a href="">Official site<a/></p>  
          </td>
      </tr>
</table>
   
---  


   https://pdf1.alldatasheet.com/datasheet-pdf/view/1132504/XPOWER/AXP288C.html



