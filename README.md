# Liam_Valletta_Dissertation
Ns-3 Simulation scripts - Dissertation Prototype


This repository contains simulation scripts written for ns-3.45 to evaluate the performance of Wi-Fi 6 (802.11ax) and Wi-Fi 7 (802.11be) in underground tunnel environments.

Phase 1 Folder includes 3 scripts:
1 for assessing wifi 6 @ 5ghz frequency 160mhz channel width and 16dBm transmit power.
1 for assessing wifi 7 with the same parameters.
1 for assessing wifi 7 with the same parameters but at longer distances and an elevated power of 23dBm.

Comments in the script include explanation to what is being used.

Fixed MCS levels were selected to test performance when varying different indexes. Threelogdistance propagation model was selected to simulate tunnel-like attenuation. This phase only assessed single hop links using static routing from node 0 -> node 1. 

Phase 2 Folder includes 3 scripts:

wifi 7 @ 6ghz 320mhz - 1 hop
wifi 7 @ 6ghz 320mhz - 2 hop
wifi 7 @ 6ghz 320mhz - 3 hop

They assess Wi-Fi 7 performance using increasing hop count: 1-hop, 2-hop, 3-hop.

Adaptive MCS was used as focus was mainly to assess multi-hop performance. OLSR dynamic routing was also used and 23dBm transmit power. 

The wifi 7 @ 6ghz 320mhz - 3 hop script comments explain what is being used.
