# Cool Stuff USB HUB
**A USB HUB WITH 3 USB A PORTS AND 1 USB C PORT!**

# About:
Cool Stuff USB HUB is a USB Hub that was built by a 15 yr old(me) by following hackclub's mocondo's starter project for a USB HUB. 

It has 3 USB A 2.0 PORTS and 1 USB C Port for convinience.

# Folder:
- `src/EasyEDA/` — EasyEDA project sources
- `production/` — fabrication outputs
- `production/PCB/` — PCB fabrication files (Gerbers, BOM, Pick & Place)
- `production/CAD/` — 3D printing files
- `src/FreeCAD/` — FreeCAD sources
- `images/` — images and screenshots


# PICS (cause what is a project without this?)



![Screenshot 2026-05-23 224025](images/Screenshot%202026-05-23%20224025.png)
![Screenshot 2026-05-23 224222](images/Screenshot%202026-05-23%20224222.png)
![Screenshot 2026-05-24 103549](images/Screenshot%202026-05-24%20103549.png)
![Screenshot 2026-05-24 112207](images/Screenshot%202026-05-24%20112207.png)
![Screenshot 2026-05-24 112219](images/Screenshot%202026-05-24%20112219.png)
![Screenshot 2026-05-24 112232](images/Screenshot%202026-05-24%20112232.png)
![Project graphic](images/cappybara.svg)



## BOM
The BOM below is converted from `production/PCB/USB HUB BOM.csv` into a Markdown table.

| No. | Quantity | Comment | Designator | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier |
|-----:|:--------:|:--------|:-----------|:----------|:------|:------------------|:-------------|:--------------|:--------|
| 1 | 9 | 1uF | C1,C2,C3,C4,C5,C6,C7,C10,C12 | C0603 | 1uF |  |  |  |  |
| 2 | 3 | 100nF | C8,C9,C11 | C0603 | 100nF |  |  |  |  |
| 3 | 2 | 5.1K | R1,R2 | R0603 | 5.1K |  |  |  |  |
| 4 | 1 | SL2.1s | U1 | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL |  | SL2.1s | CoreChips(和芯润德) | C2684433 | LCSC |
| 5 | 3 | 10.0 QHHTZB6.3 | USB2,USB3,USB4 | USB-A-TH_10.0QHHTZB6.3 |  | 10.0 QHHTZB6.3 | SHOU HAN(首韩) | C668591 | LCSC |
| 6 | 1 | TYPE-C 16PIN 2MD(073) | USB5 | USB-C-SMD_TYPE-C-16PIN-2MD-073 |  | TYPE-C 16PIN 2MD(073) | SHOU HAN(首韩) | C2765186 | LCSC |
| 7 | 1 | USB-05 | USB6 | USB-A-TH_USB-05 |  | USB-05 | SOFNG(硕方) | C112454 | LCSC |




# OTHER
I will be using JLCPCB to manufacture the PCB and will be using printing legion's (a hackclub thing like these are the type of things why i love hackclub) to 3d print the case.
