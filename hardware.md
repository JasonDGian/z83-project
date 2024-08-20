# :pushpin: Detailed Hardware Analysis

While examining the board, I began by gathering information about its components, given my limited knowledge as a hobbyist. Below is a detailed list of the elements I found on this specific board and the board itself.

## 📍The board.
Here are two pictures of the board from top and bottom.   
<img width="500px" src="https://github.com/user-attachments/assets/741e528a-f210-4b78-8e00-0d0bb60bde43">
<img width="500px" src="https://github.com/user-attachments/assets/0c0785cd-02ea-41ee-9494-d15b38486834">

## Elements on the board.
Analyzing the board I've found the following elements. 
   
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
This is the 'hard disk' on the device. Extremely small in size but packs 64GB capacity.

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
                                  <td>K3QF0F00AM-FGCF</td>
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


