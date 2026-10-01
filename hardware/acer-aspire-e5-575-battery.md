# Hardware Repair Documentation: Acer Aspire E5-575 Battery Replacement

## 1. Overview & Device Identification
* **Device Model:** Acer Aspire E5-575 Series
* **Task:** Internal Battery Replacement
* **Difficulty Level:** Moderate (Requires bottom case removal)
* **Estimated Time:** 15–25 minutes
* **Battery Specifications:**
  * **Model / Part Number:** AS16A5K / AS16A8K (4-cell Li-ion)
  * **Voltage:** 14.8V
  * **Capacity:** 2800 mAh / 41.4 Wh

<img width="1536" height="2048" alt="ZH-SIii8" src="https://github.com/user-attachments/assets/3809aea4-d3a5-44bc-ac6e-1ba4339b7ab1" />


---

## 2. Tools & Required Equipment
- [ ] Phillips #0 / #1 Screwdriver
- [ ] Plastic Spudger or Pry Tool
- [ ] Anti-Static Wrist Strap / ESD Protection
- [ ] Replacement Battery (Model AS16A5K / AS16A8K)
- [ ] Parts Organizer / Magnetic Mat

<img width="1536" height="2048" alt="p-sBwMeS" src="https://github.com/user-attachments/assets/1704d833-309e-4116-871c-246ea058e67b" />


---

## 3. Safety & Pre-Repair Checklist
> **WARNING:** Working on electronic components presents a risk of electrical shock or short-circuit. Ensure all safety steps are completed prior to opening the chassis.

1. **Power Off:** Shut down the laptop completely.
2. **Disconnect Power:** Unplug the AC power adapter and all external peripherals.
3. **ESD Precautions:** Ground yourself using an anti-static wrist strap.

---

## 4. Step-by-Step Replacement Procedure

### Step 1: Remove the RAM / Hard Drive Door
1. Turn the laptop upside down on a soft, scratch-free surface.
2. Remove the three (3) Phillips head screws securing the lower access door.
3. Use a plastic pry tool to gently lift and remove the compartment door.

<img width="1536" height="2048" alt="7nL-o6MP" src="https://github.com/user-attachments/assets/72824730-cc68-474a-9917-3dec49847d9a" />


---

### Step 2: Remove Optical Drive & Lower Case Screws
1. Locate and remove the single screw holding the optical drive in place.
2. Slide the optical drive straight out of the slot.
3. Remove the remaining Phillips head screws securing the bottom case.

<img width="1536" height="2048" alt="PKPX2rC1" src="https://github.com/user-attachments/assets/f5ff744a-c3fb-4949-9071-bbbd28eff6d4" />


---

### Step 3: Separate the Bottom Case
1. Insert a plastic spudger into the seam between the palmrest assembly and bottom case.
2. Carefully pry along the edges to release the plastic clips.
3. Lift the bottom cover away.

<img width="2048" height="1536" alt="rbH52KP-" src="https://github.com/user-attachments/assets/a3143a3b-a562-497d-8b8f-445661f6d22d" />


---

### Step 4: Disconnect and Remove the Old Battery
1. Locate the internal battery along the bottom edge.
2. Carefully slide the battery connector parallel out of its motherboard socket.
3. Remove the mounting screws securing the battery frame.
4. Lift the old battery out.

<img width="1536" height="2048" alt="dljGVpPk" src="https://github.com/user-attachments/assets/0dc65f90-33bd-4391-ada6-6828e4382526" />


---

### Step 5: Install the New Battery & Reassemble
1. Align the new battery into the housing slot.
2. Secure with the mounting screws.
3. Firmly connect the new battery cable into the motherboard socket.
4. Snap the bottom cover back on, reinstall all screws, optical drive, and access door.

<img width="2048" height="1536" alt="MxRG4UED" src="https://github.com/user-attachments/assets/7c90e0aa-7652-40f8-8821-a9b53967ccec" />
<img width="1536" height="2048" alt="q-a9XoBV" src="https://github.com/user-attachments/assets/cb5f4a5d-b3fd-4be2-8116-80093789f37a" />




---

## 5. Post-Installation Verification & Battery Calibration
1. **Boot Check:** Plug in AC power, boot the laptop, and check charging status.
2. **Calibration:** Charge to 100%, keep plugged in 2 hours, drain completely until automatic shutdown, then charge back to 100%.
3. **Diagnostics:** Run `powercfg /batteryreport` via Command Prompt to check battery health.
