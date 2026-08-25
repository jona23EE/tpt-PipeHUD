# PipeHUD
A pipe viewing & editing script for [The Powder Toy](https://powdertoy.co.uk/)

For questions or bug reports, ping @jona23 on discord.

## How to use SPDE (Pipe Property and Direction Editor):
Hold **LMB** to set direction or draw pipes:

<img width="256" height="256" alt="2026-06-23-11-54-14" src="https://github.com/user-attachments/assets/c7a061b8-4f89-4207-a64a-9761802dceba" />

##
Hold **Shift + LMB** to draw a straight section of pipes. Hint: hold **ALT** too to snap to 8 directions.

<img width="256" height="256" alt="2026-06-23-11-52-27" src="https://github.com/user-attachments/assets/c8ec24a6-dd44-4d2b-8027-101717391f8a" />

##
Use the **Scroll Wheel** whilst SPDE is selected to set mode, then hold **CTRL + LMB** to apply special operations.

<img width="256" height="256" alt="2026-06-23-11-52-55" src="https://github.com/user-attachments/assets/7b75445f-ae5d-4689-a601-f03274d11732" />

##
Pipe crossing example:

<img width="256" height="256" alt="crossing_example" src="https://github.com/user-attachments/assets/c9d06f93-7770-4f2c-a66e-b9c4c04dd3ec" />

##
Pipe distributor example: If a pipe has no next direction, it will pick a random pipe to push it's particle to from the 8 neighbouring pipes

<img width="256" height="256" alt="distributor_example" src="https://github.com/user-attachments/assets/0cc68417-92c5-41f7-9129-9b113d4d58a2" />

## Zoom window markings
**Shift-Left click** on the SDPE element itself in the menu to toggle zoom window rendering

<img width="86" height="88" alt="image" src="https://github.com/user-attachments/assets/f890fd7f-5bb4-4c4f-b3d5-c4f46ab6f128" /> Tail of the arrow | Previous pipe's direction

<img width="87" height="86" alt="image" src="https://github.com/user-attachments/assets/75f459cc-7ee6-48a2-9194-da7b90089b16" /> Head of the arrow | Next pipe's direction

<img width="87" height="84" alt="image" src="https://github.com/user-attachments/assets/5db0552e-90be-4f45-a4ad-5c610ac47c91" /> Red outline | Is a heat transfer pipe

<img width="87" height="88" alt="image" src="https://github.com/user-attachments/assets/7369482a-4deb-449c-a412-b50f23d9fa51" /> Red dot | Not a single pixel pipe

<img width="89" height="87" alt="image" src="https://github.com/user-attachments/assets/a8daf23b-2a54-445f-b631-ab941c0415f0" /> Red arrow | Not a single pixel pipe, arrow directions don't affect particle

<img width="88" height="84" alt="image" src="https://github.com/user-attachments/assets/99389292-bf9a-4f46-a7de-2e953d19de00" /> Pink circle | PPIP Paused

<img width="89" height="89" alt="image" src="https://github.com/user-attachments/assets/2cddbef1-4f5c-47d7-8b44-c75de9ca7b7f" /> Green arrows | Particle's path inside the pipe

<img width="90" height="88" alt="image" src="https://github.com/user-attachments/assets/3502bf4d-7517-4b6c-aec4-b6da20dd97ae" /> Faint green arrows | Particle's reverse path inside the pipe

<img width="84" height="86" alt="image" src="https://github.com/user-attachments/assets/97904c6c-d84e-41b2-88f1-767b2ecf2a57" /> Everything combined
