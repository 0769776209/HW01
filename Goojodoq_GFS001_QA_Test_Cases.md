# HW01 – QA/QC Test Cases for a Physical Product

## Requirement 3 – One Physical Product

### Product Under Test

| Field | Information |
|---|---|
| Product type | Handheld mini fan |
| Brand | GOOJODOQ |
| Model | GFS001 |
| Year | 2026 *(test/purchase year; update if the manufacture year printed on the product is different)* |
| Serial number | GFS001-****-XXXX *(replace with the real serial number and mask the middle 4 characters)* |
| Main power source | Rechargeable lithium-ion battery |
| Battery capacity | 4000 mAh |
| Charging port | USB Type-C |
| Key features | LED digital display, 100 adjustable fan speed levels, brushless turbo motor, handheld/desktop use |
| Reference product page | https://cellphones.com.vn/quat-cam-tay-mini-goojodoq-gfs001.html |

### Photo Evidence Requirement

Submit **1 photo** showing the **GOOJODOQ GFS001 fan and student ID card in the same frame**.

Suggested filename: `device_with_student_id.jpg`

### Video Evidence Requirement

Execute at least **5 test cases** on the real device and record short videos, each **60 seconds or less**.

Recommended test cases to record: **TC-001, TC-002, TC-003, TC-004, TC-005**.

---

## Test Environment

| Item | Description |
|---|---|
| Tester | 11B02_12_Lee Kun Da |
| Location | Indoor room / classroom / home desk |
| Ambient condition | Normal room temperature, dry surface |
| Test date | 2026-____-____ |
| Required tools | USB-C cable, USB charger or power bank, stopwatch, tissue paper, ruler or measuring tape, phone camera |
| Safety note | Keep hair, fingers, paper clips, and small objects away from the fan inlet/outlet during operation. |

---

## Test Cases

| Test Case ID | Objective | Input / Test Data | Steps | Expected Result | Actual Result | Verdict |
|---|---|---|---|---|---|---|
| TC-001 | Verify that the fan powers on correctly. | Fan with battery charged above 20%. | 1. Hold the fan normally. <br> 2. Press the power button once. <br> 3. Observe the fan blade and LED display. | Fan turns on, blade starts spinning, and LED display shows battery/speed information. | To be filled after testing. | Pass / Fail |
| TC-002 | Verify that the fan powers off correctly. | Fan is already running. | 1. Turn on the fan. <br> 2. Press and hold or press the power button according to normal usage. <br> 3. Observe the fan blade and display. | Fan stops spinning and the LED display turns off or returns to standby mode. | To be filled after testing. | Pass / Fail |
| TC-003 | Verify that fan speed can be increased. | Fan is turned on at a low speed level. | 1. Turn on the fan. <br> 2. Press the speed increase button several times. <br> 3. Observe airflow, sound, and LED speed value. | Speed value increases on the LED display and airflow becomes stronger. | To be filled after testing. | Pass / Fail |
| TC-004 | Verify that fan speed can be decreased. | Fan is turned on at a high speed level. | 1. Set fan to a higher speed. <br> 2. Press the speed decrease button several times. <br> 3. Observe airflow, sound, and LED speed value. | Speed value decreases on the LED display and airflow becomes weaker. | To be filled after testing. | Pass / Fail |
| TC-005 | Verify that the LED display shows useful information. | Fan powered on, battery not empty. | 1. Turn on the fan. <br> 2. Change speed level. <br> 3. Observe the LED display. | LED display clearly shows fan speed and/or battery status in real time. | To be filled after testing. | Pass / Fail |
| TC-006 | Verify USB Type-C charging function. | USB-C cable and charger/power bank. | 1. Connect USB-C cable to the fan. <br> 2. Connect the other end to a charger or power bank. <br> 3. Observe LED charging indication. | Fan enters charging mode and LED shows charging/battery status. | To be filled after testing. | Pass / Fail |
| TC-007 | Verify that the fan can operate while placed on a flat desk. | Flat table surface. | 1. Place the fan upright on a desk. <br> 2. Turn on the fan at medium speed. <br> 3. Observe stability for 30 seconds. | Fan remains stable and does not fall over or move excessively. | To be filled after testing. | Pass / Fail |
| TC-008 | Verify handheld comfort during operation. | Fan running at medium speed. | 1. Hold the fan for 1 minute. <br> 2. Check grip comfort, vibration, and heat. | Fan is comfortable to hold, with no sharp edges, excessive vibration, or abnormal heat. | To be filled after testing. | Pass / Fail |
| TC-009 | Verify airflow at a short distance. | Tissue paper and ruler. | 1. Turn fan to medium speed. <br> 2. Hold tissue paper 30 cm from the fan outlet. <br> 3. Observe tissue movement. | Tissue paper moves clearly, showing that airflow is produced at short distance. | To be filled after testing. | Pass / Fail |
| TC-010 | Verify airflow at a longer distance. | Tissue paper and measuring tape. | 1. Turn fan to high speed. <br> 2. Place tissue paper about 1 meter from the fan outlet. <br> 3. Observe tissue movement. | Tissue paper moves slightly or clearly, showing airflow can reach the longer distance. | To be filled after testing. | Pass / Fail |
| TC-011 | Verify abnormal noise during operation. | Quiet indoor environment. | 1. Turn on fan at low speed. <br> 2. Increase to medium speed. <br> 3. Increase to high speed. <br> 4. Listen for rattling, scraping, or clicking sounds. | Fan produces normal motor/wind noise only; no rattling, scraping, or unstable sound. | To be filled after testing. | Pass / Fail |
| TC-012 | Verify that the protective grille prevents direct finger contact with the blade during normal use. | Fan turned off first, then on. | 1. Visually inspect the air outlet grille. <br> 2. Do not insert fingers or objects into the fan. <br> 3. Turn on the fan and observe grille stability. | Grille is firmly attached and prevents normal accidental contact with the spinning blade. | To be filled after testing. | Pass / Fail |
| TC-013 | Verify device response when battery is low. | Fan battery below 10% if possible. | 1. Use the fan until battery becomes low. <br> 2. Observe LED display and fan behavior. | LED shows low battery or fan speed decreases/stops safely without sudden abnormal behavior. | To be filled after testing. | Pass / Fail |
| TC-014 | Verify charging cable fit and port stability. | USB-C cable. | 1. Insert USB-C cable into the charging port. <br> 2. Gently move the cable left/right without force. <br> 3. Observe connection stability. | Cable fits properly, does not fall out easily, and charging indication remains stable. | To be filled after testing. | Pass / Fail |
| TC-015 | Verify exterior build quality. | Visual and touch inspection. | 1. Inspect the fan body, buttons, display, grille, and handle. <br> 2. Check for cracks, loose parts, scratches, sharp edges, or misalignment. | Product has no major cosmetic defect, no loose part, no sharp edge, and buttons are properly aligned. | To be filled after testing. | Pass / Fail |

---

## Executed Test Case Evidence Log

Fill this table after recording the real-device videos.

| Test Case ID | Video Filename | Duration | Actual Result Summary | Verdict |
|---|---|---:|---|---|
| TC-001 | `TC-001_power_on.mp4` | ≤ 60s | To be filled after testing. | Pass / Fail |
| TC-002 | `TC-002_power_off.mp4` | ≤ 60s | To be filled after testing. | Pass / Fail |
| TC-003 | `TC-003_speed_increase.mp4` | ≤ 60s | To be filled after testing. | Pass / Fail |
| TC-004 | `TC-004_speed_decrease.mp4` | ≤ 60s | To be filled after testing. | Pass / Fail |
| TC-005 | `TC-005_led_display.mp4` | ≤ 60s | To be filled after testing. | Pass / Fail |

---

## Notes for Submission

1. Replace the serial number placeholder with the real serial number and mask the middle 4 characters.  
   Example: `GF25-****-0198`.
2. Add the real photo of the fan and student ID card in the same frame.
3. Record at least 5 videos, each 60 seconds or less.
4. Fill in the **Actual Result** and **Verdict** columns after testing.
5. Do not claim a test case passed unless it was executed on the real device.
