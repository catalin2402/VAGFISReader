arduino library for reading V.A.G. FIS / DIS 3lb line from radio / navigation

Video of capturing navi:

<div align="center">
  <a href="https://www.youtube.com/watch?v=_Gfd5EC4pqc"><img src="https://img.youtube.com/vi/_Gfd5EC4pqc/0.jpg" alt="IMAGE ALT TEXT"></a>
</div>

input are 3lines: ena/data/clk

interupt on ena: rising edge enable falling edge detection on clk like

interupt on CLK line read data lina value and store it as input packet

Packet overview in radio mode: http://kovo-blog.blogspot.sk/2013/11/audi-fis-3-line-protocol.html


FULLY TESTED: 
 * full fis mode on atmega328
 * radio mode on stm32 (bluepill board) 
 

For information how to connect radio to mcu see this [wiki page](https://github.com/tomaskovacik/VAGFISReader/wiki/How-to-connect).

Here is link to [wiki page](https://github.com/tomaskovacik/VAGFISReader/wiki/Theory-of-operation) talking about theory of operation.
