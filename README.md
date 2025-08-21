# Keyboard_opensource

DIODOS 1n4148 PTH - No projeto já havia presença de furos para a solda do diodo pth, então só foi mantido o mesmo footprint

Mudança do conector TRRS - Vou modificado para o https://www.lcsc.com/product-detail/C431535.html?s_z=n_PJ-320D, que é o mesmo que foi indicado.

Mudança do MCU - Foi modificado o MCU do Arduino parta o Raspberry Pi Pico Zero da Waveshare (RP2040).

Adequação das camadas - O projeto original foi feito em duas camada (top e bottom). Ele foi reorganizado somente em uma cada (top) e foi usando jumper para fazer conexões quando necessário.

O projeto se encontra no pasta pcb no caminho pcb>>rev1.0>>kicad_flies com nome redox_rev1_main
