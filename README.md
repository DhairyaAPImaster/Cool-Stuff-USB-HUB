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
**If u want u can find this BOM at `production/PCB/USB HUB BOM.csv` in CSV format.**

| No. | Quantity | Comment | Designator | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier |
|-----:|:--------:|:--------|:-----------|:----------|:------|:------------------|:-------------|:--------------|:--------|
| 1 | 9 | 1uF | C1,C2,C3,C4,C5,C6,C7,C10,C12 | C0603 | 1uF |  |  |  |  |
| 2 | 3 | 100nF | C8,C9,C11 | C0603 | 100nF |  |  |  |  |
| 3 | 2 | 5.1K | R1,R2 | R0603 | 5.1K |  |  |  |  |
| 4 | 1 | SL2.1s | U1 | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL |  | SL2.1s | CoreChips(和芯润德) | C2684433 | LCSC |
| 5 | 3 | 10.0 QHHTZB6.3 | USB2,USB3,USB4 | USB-A-TH_10.0QHHTZB6.3 |  | 10.0 QHHTZB6.3 | SHOU HAN(首韩) | C668591 | LCSC |
| 6 | 1 | TYPE-C 16PIN 2MD(073) | USB5 | USB-C-SMD_TYPE-C-16PIN-2MD-073 |  | TYPE-C 16PIN 2MD(073) | SHOU HAN(首韩) | C2765186 | LCSC |
| 7 | 1 | USB-05 | USB6 | USB-A-TH_USB-05 |  | USB-05 | SOFNG(硕方) | C112454 | LCSC |




## HOW TO REPLICATE?? - 



**So basically heres how u can use this repo to make this USB HUB for yourselves. -**

- Step 1 - Basically Just Clone or downlaod this repo from github. U can do this by either going to the code button on this repo page and pressing download Zip or u can clone this Repo Or you can go to the Releases on this repo and download the Zip File there too (the fastest way to download is like just going to code and pressing download Zip Or by cloning the Repo.) <img width="1599" height="665" alt="image" src="https://github.com/user-attachments/assets/88c420bf-29ac-4c7a-be3e-fef8a0a62f53" />

- Step 2 - In the the production folder you will find the CAD and PCB folders.
- Step 3 - The CAD folder contains all the 3d Pritnable files for the enclosure for the PCB. If you wish to u can make any changes to the design or make your own design and use that instead.
- Step 4 - The PCB folder contains the Gerbers, BOM , and CPL files. These are the files that allow you to get the PCB manufactured from JLCPCB (im using JLCPCB) or any other PCB manufacturer.
- Step 5 - Upload the gerbers zip file in JLCPCB Place order Page (u will need to sign up to order but can get a quote without signing up)
- Step 6 - Change the colour of the PCB in the options JLC gives (if u use JLC PCB most of the times canging colours does not add any charge acc to what i know)
- Step 7 - Select PCBA if u want JLCPCB to assemble the PCB for you (you might have to choose standart if you want to them to assemble the Male USB A but yeah u could always solder that one component yourself.)
- Step 8 - Upload the CPL and BOM files.
- Step 9 - Recheck the position of all components (i faced no problem with this as all components were in the correct place but i have faced issues with the placement in one of my other projects i made in KiCAD)
- Step 10 - Add to cart and order the PCB!! **(if you are soldering the male USB A yourself you will need to buy that from some other place)**
- Step 11 - If you dont have a 3D PRINTER jlcpcb has a 3d printing service too caled JLC3DP so u can upload the files for the case there and get it printed too but if u have a 3d printer you can just print it youreslf and save a lot of money.
- Step 12 - Order strong epoxy glue or superglue that does not cause harm to the 3d printed case material (I will be using FeviQuick as it should not cause harm to PLA in which the case will be printed)
- Step 13 - WAIT WAIT WAIT for your parts to be delhivered
- Step 14 - Once you have all the parts (PCB, CASE and the appropriate Glue) place the PCB in the Case (you might have to trim the spacers down a bit as i made the spacers high so that they arent to small as i can always cut higher spacers down but can extend spacers that are short.)  Use hot glue to secure the PCB onto the Spacers (IK i just didnt add and mounting holes but yeah its fine for this project.)
- Step 15 - Once the PCB is secured inside the case glue the Bottom And the Top Parts of the Case shut.
-  Step 16 - BOOM  THERE YOU HAVE IT MADE!!!





# Note for customizing- 

Si basically i made the PCB in EasyEDA Pro so if u like use KiCAD or some other software you will have to see how to like import the project since ngl IDK how to do that since if i start a project in KiCAD i finish it in KiCAD and if i Make a Projet in EasyEDA i try and finish it in EasyEDA as ngl its confusing to import an EasyEDA project into KiCAD.






# OTHER
I will be using JLCPCB to manufacture the PCB and will be using printing legion's (a hackclub thing like these are the type of things why i love hackclub) to 3d print the case.


## Cost of full project
- PCB from JLC PCB- 4 USD
- PCBA from JLCPCB - 24.75 USD
- JLCPCB Shipping cost - 9.26 USD
- USB A male Connecor from Amazon - 1.35 USD
- Amazon Shipping cost- 69 INR or - 0.73 USD
- AVG tax on PCB - 6-7 USD
- 3D printing Costs (will get printed from #printing-legion so only shipping price applicable) - 1-2 USD
- **TOTAL - 48.09 USD** 
