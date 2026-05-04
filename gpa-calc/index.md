---
title: "GPA Calculator"
layout: default
---

<img align="right" width="128" height="128" alt="GPA Calc icon" src="https://github.com/user-attachments/assets/0774827d-40f9-45d7-b412-cab5f690b6f6" />

# GPA Calculator 3

In Nov 2025, I started working on an update of SHSID's GPA Calculator with [Michel](https://www.github.com/michelg10). Since then, this project has been something I've spent dozens of hours working on over the span of a couple months (hundreds of prototypes!)

<img align="center" width="1920" height="1080" alt="GPA Calc Showcase" src="https://github.com/user-attachments/assets/38c85a2e-f196-48d5-abe5-e426442df215" />

I completely reworked SHSID's GPA Calculator app to version 3, now with some new features: 

- Rule-based solver for accurate course selection
- Online course autoupdate when the catalog changes
- Selectors adjust to dropdown to fit all screen sizes

### Download
<iframe src="https://apps.apple.com/us/app/gpa-calculator-by-michel/id1540111715?itscg=30200&itsct=apps_box_link&mttnsubad=1540111715" class="embedded-page"></iframe>

TEST:

  <a href="https://apps.apple.com/us/app/gpa-calculator-by-michel/id1540111715?itscg=30200&itsct=apps_box_artwork&mttnsubad=1540111715" style="position: relative; width: 170px; height: 170px; overflow: hidden; display: inline-block; vertical-align: middle; 
    --app-icon-mask: url('data:image/svg+xml,%0A%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20xml%3Aspace%3D%22preserve%22%20viewBox%3D%220%200%20230.5%20230.5%22%3E%0A%20%20%3Cpath%20fill-rule%3D%22evenodd%22%20stroke-linejoin%3D%22round%22%20stroke-miterlimit%3D%221.4%22%20clip-rule%3D%22evenodd%22%20d%3D%22M158.2%20230H64.1a320%20320%200%200%201-7-.1c-5%200-10-.5-15-1.3a50.8%2050.8%200%200%201-14.4-4.8%2048.2%2048.2%200%200%201-21-21%2050.9%2050.9%200%200%201-4.8-14.4%20100.7%20100.7%200%200%201-1.3-15v-7l-.1-8.2V64.1a320%20320%200%200%201%20.1-7c0-5%20.5-10%201.3-15a50.7%2050.7%200%200%201%204.8-14.4%2048.2%2048.2%200%200%201%2021-21%2051%2051%200%200%201%2014.4-4.8c5-.8%2010-1.2%2015-1.3a320%20320%200%200%201%207%200l8.2-.1h94.1a320%20320%200%200%201%207%20.1c5%200%2010%20.5%2015%201.3a52%2052%200%200%201%2014.4%204.8%2048.2%2048.2%200%200%201%2021%2021%2050.9%2050.9%200%200%201%204.8%2014.4c.8%205%201.2%2010%201.3%2015a320%20320%200%200%201%20.1%207v102.3l-.1%207c0%205-.5%2010-1.3%2015a50.7%2050.7%200%200%201-4.8%2014.4%2048.2%2048.2%200%200%201-21%2021%2050.8%2050.8%200%200%201-14.4%204.8c-5%20.8-10%201.2-15%201.3a320%20320%200%200%201-7%200l-8.2.1z%22%2F%3E%0A%3C%2Fsvg%3E%0A');">
  
      <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/a9/c6/a0/a9c6a07e-dc95-e8cb-6591-b2be380c3ee2/AppIcon-0-0-1x_U007emarketing-0-8-0-85-220.png/540x540bb.jpg" alt="GPA Calculator by Michel"
           style="width: 100%; height: 100%; object-fit: contain;
           mask-image: var(--app-icon-mask); -webkit-mask-image: var(--app-icon-mask);" />
    
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 230.5 230.5" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; box-sizing: border-box;">
  <path fill="none" stroke="#000" stroke-linejoin="round" stroke-miterlimit="1.4" stroke-opacity=".1" stroke-width="1" d="M158.2 230H64.1a320 320 0 0 1-7-.1c-5 0-10-.5-15-1.3a50.8 50.8 0 0 1-14.4-4.8 48.2 48.2 0 0 1-21-21 50.9 50.9 0 0 1-4.8-14.4 100.7 100.7 0 0 1-1.3-15v-7l-.1-8.2V64.1a320 320 0 0 1 .1-7c0-5 .5-10 1.3-15a50.7 50.7 0 0 1 4.8-14.4 48.2 48.2 0 0 1 21-21 51 51 0 0 1 14.4-4.8c5-.8 10-1.2 15-1.3a320 320 0 0 1 7 0l8.2-.1h94.1a320 320 0 0 1 7 .1c5 0 10 .5 15 1.3a52 52 0 0 1 14.4 4.8 48.2 48.2 0 0 1 21 21 50.9 50.9 0 0 1 4.8 14.4c.8 5 1.2 10 1.3 15a320 320 0 0 1 .1 7v102.3l-.1 7c0 5-.5 10-1.3 15a50.7 50.7 0 0 1-4.8 14.4 48.2 48.2 0 0 1-21 21 50.8 50.8 0 0 1-14.4 4.8c-5 .8-10 1.2-15 1.3a320 320 0 0 1-7 0l-8.2.1z" clip-rule="evenodd" vector-effect="non-scaling-stroke"/>
</svg>
</a>

### Sneak peak on the iteration of the app

<img width="387" height="844" alt="image" src="https://github.com/user-attachments/assets/64e49bef-516a-4daa-a6a1-b500918785fb" />

> earliest versions, experimenting with launch screens for autoupdate

<img width="1332" height="722" alt="image" src="https://github.com/user-attachments/assets/969e561b-ce04-4da8-83a4-20a2293d4e17" />

> prototype of a custom "GPA" programming language before switching to plist then JSON

<img width="386" height="848" alt="image" src="https://github.com/user-attachments/assets/2026691c-7033-4c90-b759-21b676cf3318" />

> having fun with a GPA pie! (pretty useless)

<img width="335" height="737" alt="image" src="https://github.com/user-attachments/assets/cfe24191-3ca7-48e1-9639-875fd6acbf15" />

> dynamic update working! 

<img width="869" height="838" alt="image" src="https://github.com/user-attachments/assets/a2ab4714-82b3-48af-8a4e-f8f8a4d9c62c" />

> earliest version of the dynamic pickers that show a menu if there wasn't enough space to fit all on a picker

<img width="733" height="842" alt="image" src="https://github.com/user-attachments/assets/9f0ff86d-c293-4a56-8d33-d83150b61cc0" />

> early implementation of rule checking

<img width="333" height="311" alt="image" src="https://github.com/user-attachments/assets/9092e360-ee77-43e0-9d7f-db148ada8d80" />

> using a modern menu for the dynamic pickers

<img width="348" height="759" alt="image" src="https://github.com/user-attachments/assets/8b56fbc3-c1dd-4165-83fc-2c73e825bb4a" />

> custom score map support!

<img width="505" height="756" alt="image" src="https://github.com/user-attachments/assets/9139b9b2-43d4-40a2-94ea-b9b1db23b12f" />

> a finalized version with the same backend as the current one, solving some view bugs

