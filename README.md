# An Open Source FPGA Blakecoin Miner

This code is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details.

Project includes code from https://github.com/progranism/Open-Source-FPGA-Bitcoin-Miner
Also http://www.rcis.aist.go.jp/files/special/SASEBO/SHA3-ja/BLAKE.zip which quotes free
license for research purposes, http://www.rcis.aist.go.jp/special/SASEBO/SHA3-en.html

See https://bitcointalk.org/index.php?topic=306894.0 for forum discussion.

Special thanks to fpgaminer for the original bitcoin mining code, teknohog for his
serial code, also OrphanedGland, udif, TheSeven, makomk, and newMeat1 as credited on
the fpgaminer bitcoin thread https://bitcointalk.org/index.php?topic=9047.0 and ngzhang
for his Icarus/Lancelot boards and github. Not forgetting bluedragon747 for blakecoin!

### Ports are available for icarus/lancelot, ztex 1.15x, 1.15y and Cairnsmore CM1.
The code currently achieves:
around 780MHash/s at 195Mhz on the lancelot board
around 1.5Gh/s on the quad boards (1.15y, CM1). 
All code is in the experimental folder and the bitstreams links for download are in bitstreams.txt

All are supported by a modified cgminer 3.1.1 for use solo or on pool, there is also a
python miner for the Icarus/Lancelot board (solo mining, or pool via getwork only).


### Performance
```
800MH/s on a Lancelot Dual Spartan-6 LX150 Development Board
1.6GH/s on a ZTEX USB-FPGA 1.15y Quad Spartan-6 LX150 Development Board
1.5GH/s on a Enterpoint Cairnsmore 1 Quad Spartan-6 LX150 Development Board
360MH/s on a ZTEX USB-FPGA 1.15x Spartan-6 LX150 Development Board
```
