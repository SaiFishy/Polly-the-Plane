# RC UAV (Polly MK1)

Polly is a fun, high speed and manuverable RC plane made out of 3D printed lightweight PLA parts and electronic components, designed to be easily replicatable by anyone. You can use my project by taking it out to the park, where you can enjoy the beauty of flight! Full specifications and calculations of this plane can be found at the bottom of this read me.  I decided to build this project for two reasons:

1) It introduces me into aerodynamics, lift and forces acting on flying bodies.
2) It introduces me into practical electronics.

Aeronautical engineering is something I would like to pursue in the future) so I thought it would be cool to make my own plane. 

Photo Booth:

Full 3D Model of Polly:

<img width="1156" height="747" alt="{E690684C-77DB-487C-A40D-2138E91768BC}" src="https://github.com/user-attachments/assets/ed08621f-f35e-4bdf-8a28-7ef900cbb741" />

Transmitter:

<img width="600" height="731" alt="{6DD9E73D-3987-4DA9-92BE-4E7886154A10}" src="https://github.com/user-attachments/assets/4bc91951-e164-4663-8341-032d5b5c0258" />


Transmitter Custom Board:

<img width="571" height="723" alt="{5275EE27-3C19-4AA1-9AFF-E367AF89E6A8}" src="https://github.com/user-attachments/assets/0faddee7-b0ba-4e43-93f7-de0cb029a70f" />

Reciever Custom Board:

<img width="554" height="723" alt="{7991383E-CCE6-4D20-B02C-3E17253A64B1}" src="https://github.com/user-attachments/assets/45a36171-52bc-4817-b603-b0bdbdb6bb2f" />


In terms of electronics, a few things are missing from the pictures above:

a) Transciever modules are to be soldered to the 7 through hole pads found on both modules

b) Joystick modules are to be soldered to the J1 and J2 pins on the Transmitter

c) A positive and negative terminal is to be soldered to the "Battery 1.5x6v" through holes, providing energy to the transmitter circuit

Another consideration for the Reciever:

 - Servos are powered via the servo pins on the Reciever
 - The Motor is connected to an ESC, which gives energy to the Reciever circuit.

Here is a wiring diagram, representing missing electronic devices from the transmitter and reciever circuits:

Transmitter - Joysticks are soldered on to the board, same goes for the power adapter for the transciever:

<img width="511" height="662" alt="{FBBC17E1-562B-4FEB-A5EE-D416031D5EBE}" src="https://github.com/user-attachments/assets/106ceafe-f290-4d04-86ff-bbbb9289cf2f" />

Reciever - wires soldered to power adapter, which connects to main module via inserts:

<img width="936" height="502" alt="{1FAE48FF-3401-4459-8045-4B942B8E1FB7}" src="https://github.com/user-attachments/assets/cf6bbd9c-7c71-4c23-8bef-41adbab90ef1" />


My BOM:

| Name | Source | Description | Link | Unit Price | Amount |
|------|--------|-------------|------|------------|--------|
| LW-PLA | Amazon |Material used to 3D Print the Plane |-https://www.amazon.co.uk/Polymaker-PolyLite-LW-PLA-1-75mm-Orange/dp/B0B1DN6ZS2/ref=sr_1_8?crid=1LGJH7WZI7LPJ&dib=eyJ2IjoiMSJ9.7NVKP6lLQk_oGaVB1Zfql770cJAfWj3Vd1g4rNObkQ4qp86Lm7qOvhqVssQkyv0N0ut1clPIQsTGn12EPv3av1gzgP4x7koD1EaTn_OHvu23WSZHzRjkHblda8hTg6F6n2uufnBvSvsSGG5aPnxTNralJtvIxOgI_hwUysCvwbEipjTrrWd5GSODbmHzMMDucGdpWmFZz-7NbtFoGEt5umbmQpnkpKWwHT-j2yCiJa280lxV6w7lPr-C6d77m0R0mBKz1Ll8E96Y_cZUjH-UFZYvcgnsvCJEXZwSkU3i3DI.wnMQtctX_aHIx4wfu0EOp-1klzPyXWX7nywmYNPrIHs&dib_tag=se&keywords=lightweight%2Bpla&qid=1774125033&rdc=1&sprefix=lightweight%2Bp%2Caps%2C244&sr=8-8&th=1|26.4|1|
|NRF24L01 Module|AliExpress|Radio Communication between Ground and UAV|https://www.aliexpress.com/item/1005009253882566.html?spm=a2g0o.cart.0.0.6c6338daCZj272&mp=1&pdp_npi=6%40dis%21GBP%21GBP%205.63%21GBP%202.59%21%21GBP%202.59%21%21%21%40211b804117741243199331487e5a8d%2112000048487442744%21ct%21UK%217079411286%21%212%210%21|2.59|1
|Lipo Charger|Amazon|Provides Safe Charging Means|https://www.amazon.co.uk/gp/product/B0F3XB57JT/ref=ox_sc_act_title_5?smid=A3IA07ABSHI596&th=1|17.99|1
|Steel Push Rods|AliExpress|Control of Aircraft|https://www.aliexpress.com/item/1005010645116134.html?spm=a2g0o.productlist.main.2.114ewu2Awu2Ate&algo_pvid=cfe8a638-c52e-4495-a520-e9e96e1b1a5d&algo_exp_id=cfe8a638-c52e-4495-a520-e9e96e1b1a5d-1&pdp_ext_f=%7B%22order%22%3A%226%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%212.24%212.24%21%21%2119.97%2119.97%21%40210385a817734316112024353ed4e0%2112000053065709629%21sea%21UK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Af4c5e4bc%3Bm03_new_user%3A-29895&curPageLogUid=2lYWz4WEYb1f&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010645116134%7C_p_origin_prod%3A|1.59|1
|Nylon Hinge|AliExpress|Ensures safe movement of control surfaces|https://www.aliexpress.com/item/1005003378453697.html?spm=a2g0o.productlist.main.1.1b94oodqoodq2I&algo_pvid=60db83dc-5e4e-49c4-9e07-441d478fde9c&algo_exp_id=60db83dc-5e4e-49c4-9e07-441d478fde9c-0&pdp_ext_f=%7B%22order%22%3A%22981%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%211.96%210.76%21%21%212.54%210.98%21%40211b807017734317466243621e3f7f%2112000025503609436%21sea%21UK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Af4c5e4bc%3Bm03_new_user%3A-29895%3BpisId%3A5000000197842827&curPageLogUid=weNt3HCvqMDA&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005003378453697%7C_p_origin_prod%3A|1.99|1
|7 Pin Header|AliExpress|For RC transmitter|https://www.aliexpress.com/item/1005003378453697.html?spm=a2g0o.productlist.main.1.1b94oodqoodq2I&algo_pvid=60db83dc-5e4e-49c4-9e07-441d478fde9c&algo_exp_id=60db83dc-5e4e-49c4-9e07-441d478fde9c-0&pdp_ext_f=%7B%22order%22%3A%22981%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%211.96%210.76%21%21%212.54%210.98%21%40211b807017734317466243621e3f7f%2112000025503609436%21sea%21UK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Af4c5e4bc%3Bm03_new_user%3A-29895%3BpisId%3A5000000197842827&curPageLogUid=weNt3HCvqMDA&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005003378453697%7C_p_origin_prod%3A|0.6|1
|Propellor|Amazon| Needed to pull the aircraft through the air|https://www.amazon.co.uk/gp/product/B0FQ64833L/ref=ox_sc_act_title_1?smid=AIF4G7PLKBOZY&th=1|7.59|1

Total = £58.75

Thats roughly $77 <3














