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

![Overview & Parts](../images/01-overview.jpg)

---

## 2. Tools & Required Equipment
- [ ] Phillips #0 / #1 Screwdriver
- [ ] Plastic Spudger or Pry Tool
- [ ] Anti-Static Wrist Strap / ESD Protection
- [ ] Replacement Battery (Model AS16A5K / AS16A8K)
- [ ] Parts Organizer / Magnetic Mat

![Tools Layout](../images/02-tools.jpg)

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

![RAM Access Door](../images/03-access-door.jpg)

---

### Step 2: Remove Optical Drive & Lower Case Screws
1. Locate and remove the single screw holding the optical drive in place.
2. Slide the optical drive straight out of the slot.
3. Remove the remaining Phillips head screws securing the bottom case.

![Case Screws](../images/04-case-screws.jpg)

---

### Step 3: Separate the Bottom Case
1. Insert a plastic spudger into the seam between the palmrest assembly and bottom case.
2. Carefully pry along the edges to release the plastic clips.
3. Lift the bottom cover away.

![Separate Case](../images/05-separate-case.jpg)

---

### Step 4: Disconnect and Remove the Old Battery
1. Locate the internal battery along the bottom edge.
2. Carefully slide the battery connector parallel out of its motherboard socket.
3. Remove the mounting screws securing the battery frame.
4. Lift the old battery out.

![Remove Battery](../images/06-remove-battery.jpg)

---

### Step 5: Install the New Battery & Reassemble
1. Align the new battery into the housing slot.
2. Secure with the mounting screws.
3. Firmly connect the new battery cable into the motherboard socket.
4. Snap the bottom cover back on, reinstall all screws, optical drive, and access door.

![New Battery Installed](../images/07-new-battery.jpg)

---

## 5. Post-Installation Verification & Battery Calibration
1. **Boot Check:** Plug in AC power, boot the laptop, and check charging status.
2. **Calibration:** Charge to 100%, keep plugged in 2 hours, drain completely until automatic shutdown, then charge back to 100%.
3. **Diagnostics:** Run `powercfg /batteryreport` via Command Prompt to check battery health.
