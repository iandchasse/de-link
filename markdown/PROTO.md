# Prototype Details

Images and notes from building the initial de-link prototype.

---

## PCB Prototypes

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px;">
  <div>
    <img src="../images/PCB_proto_front.jpg" width="300" alt="PCB Prototype Front">
    <p style="text-align: center;"><em>PCB prototype front side</em></p>
  </div>
  <div>
    <img src="../images/PCB_proto_back.jpg" width="300" alt="PCB Prototype Back">
    <p style="text-align: center;"><em>PCB prototype back side</em></p>
  </div>
</div>

Real image of the PCB, here with wires on the UART pins because I F'd up. Hopefully will avoid that in the future.

---

## Vape Battery
I only have one 650mAh protected battery and I opted to give it to my gf for safety. I am testing out the battery circuit by using a 22350 li-ion cell salvaged from a friend's disposable vape. **WARNING DO NOT SOLDER BATTERIES WITHOUT EXPERIENCE**

Oddly enough the hump is fairly ergonomic.

<img src="../images/hump.jpg" width="400" alt="Battery hump">

It makes a pretty good kick stand too.

<img src="../images/kickstand.jpg" width="400" alt="Battery acting as a kickstand">

## Display Support

<img src="../images/7_5_support.jpg" width="400" alt="7.5 inch Display">

The PCB supports multiple GoodDisplay panel sizes. Shown here is the 7.5" display option, demonstrating the scalability of the design beyond the 4.26" prototype. Also, I had much easier code working for a slightly smaller 3.97" display, before I tragically snapped the ribbon cable.

<img src="../images/3_97_support.jpg" width="400" alt="3.97 inch Display">

These are the main two displays I hope to make enclosures for first, as they both have the same resolution as the 4.26" screen (800x480) and are in high stock.

---

## Power Characteristics

Understanding power consumption across different modes helps with battery life planning.

<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px;">
  <div>
    <img src="../images/on_current_draw.jpg" width="250" alt="On Current Draw">
    <p style="text-align: center;"><em>Active operation</em></p>
  </div>
  
  <div>
    <img src="../images/LED_current_draw.jpg" width="250" alt="LED Current Draw">
    <p style="text-align: center;"><em>LED module</em></p>
  </div>
  <div>
    <img src="../images/sleep_current_draw.jpg" width="250" alt="Sleep Current Draw">
    <p style="text-align: center;"><em>Deep sleep mode</em></p>
  </div>
</div>

This is what I emphasize for "sleep/wake" in [COMPARISON.md](markdown/COMPARISON.md). The current draw is nearly nothing when in deep sleep even though the LDO is connected. 

---

## Font Rendering

Using the PSRAM on the device, I tinkered around with generating custom fonts on the device with just .ttf files.

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px;">
  <div>
    <img src="../images/dune_font.jpg" width="300" alt="Dune Font">
    <p style="text-align: center;"><em>Font rendering example</em></p>
  </div>
  <div>
    <img src="../images/cust_font_gen.jpg" width="300" alt="Custom Font Generator">
    <p style="text-align: center;"><em>Custom font generation tool</em></p>
  </div>
</div>

Reading Dune in Dune font. Why not.

---

## Colors

<img src="../images/pink_slay.jpg" width="300" alt="Pink Prototype">
<img src="../images/grey_slay.jpg" width="300" alt="Grey Prototype">

Taking advantage of spare filament.


---

[Back to README](README.md)
