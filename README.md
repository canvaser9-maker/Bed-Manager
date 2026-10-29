# Bed Board — ED Bed Manager

A single-page browser game: you're the bed manager for a busy emergency department for one 12-hour day shift (07:00–19:00).

**Play:** open `index.html` in any modern browser, on desktop or phone. There's no build step and nothing to install.

## How it plays

- **The board** is a live map styled after an ED tracking board. It has trauma/resus bays, two pods of rooms around nurses' stations, hallway beds, fast track, pediatrics, behavioral health, an observation unit, and surge spaces that open during an MCI. Each tile shows the patient, their acuity (ESI 1–5), the chief complaint, length of stay, a visit-progress bar and their current status.
- **Tap a patient, then tap a ready room.** Rooms are highlighted green, amber or red by how well they fit that patient.
- **Patients arrive** as walk-ins in the waiting room, or by ambulance. Ambulances radio in first, so you can pre-assign a room, then wait on the EMS stretcher.
- **Doctors run themselves.** They see patients, order labs and imaging, and decide whether each one is discharged, admitted, transferred or placed in observation. Your job is to keep space moving:
  - move stable, already-seen patients to results waiting
  - send observation patients to the obs unit
  - call EVS to clean dirty rooms (tap again to make it STAT)
- **Consequences:** long waits lead to walkouts (LWBS), deterioration, complaints and EMS offload delays. Putting a patient in the wrong space carries its own risks: unstable patients in unmonitored spaces, psych patients outside safe rooms, adults in peds, and resus bays blocked by low-acuity patients.
- **Charge-nurse decisions** pop up during the shift: sick calls, upset families, diversion requests, lab or CT outages, hospitalist pushback, VIPs and transfer requests.
- **Mass casualty incident:** rare, and more likely on harder difficulties. It brings a wave of tagged patients and a menu of surge options.
- **End of shift:** you get a letter grade with a breakdown of penalties, throughput, door-to-provider time, LOS and boarding.

Controls: pause, 1×, 2× and 4× buttons (keyboard: Space, 1, 2, 3; Esc deselects). A 12-hour shift takes about 12 real minutes at 1×.
