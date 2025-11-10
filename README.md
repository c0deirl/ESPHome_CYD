# ESPHome + LVGL on a CYD
<img width="912" height="199" alt="esphomelvgl" style="display: block; margin: 0 auto" src="https://github.com/user-attachments/assets/f0b237d8-33dc-4333-b13f-ba1c7ed2bd49" />

## Overview
ESPHome on a CYD (Cheap Yellow Display - ESP32-2432S028R) Using LVGL Graphics

## Project Description
I decided to dive into programming a CYD using LVGL as the graphics library and ESPHome. This project was challenging due to the lack of comprehensive documentation and examples. The display serves as a basic bedside control surface.

### Key Features:
- **Control Buttons:** Six buttons to manage lights, such as backyard lights and garage lights.
- **AdGuard Toggle:** Easily enable or disable AdGuard for mobile gaming rewards.
- **Top Layer:** Navigation, time, and temperature displayed across all pages.
- **Info Page:** Outside temperature, server power draw, and other relevant information.
- **Office Page:** Router bandwidth data (Opnsense integrated into HA) and 3D printer progress.
- **Spotify Control:** Forward, pause/play, and backward buttons for controlling Spotify.

## Layout
There are four pages in total:

1. **Page 1: Basic Control Buttons**
   - **Functionality:** Control lights, AdGuard toggle.
   - **Description:** Essential for ensuring the right devices are off before bed.

2. **Page 2: Relevant Info**
   - **Functionality:** Display outside temperature, server power draw.
   - **Description:** Useful for quick checks and monitoring.

3. **Page 3: Office Page**
   - **Functionality:** Router bandwidth data, 3D printer progress.
   - **Description:** Ideal for the office CYD to keep track of network and printing activities.

4. **Page 4: Spotify Control**
   - **Functionality:** Forward, pause/play, backward buttons.
   - **Description:** Convenient for controlling Spotify without leaving other tasks.

## Code
The entire project is contained in a single YAML file. I have included detailed comments to help others understand and replicate the setup.

## Pictures

### Page 1
![25-11-10 08-42-47 1049](https://github.com/user-attachments/assets/e1754b4f-7c86-497e-8f34-49ff761ff8d9)

### Page 2
![25-11-10 08-42-53 1050](https://github.com/user-attachments/assets/ac890a1a-0335-4b86-a6e6-5b5b53f2f587)

### Page 3
![25-11-10 08-42-58 1051](https://github.com/user-attachments/assets/c66a9ab2-ee9f-4023-a51d-e75b286035e5)

### Page 4
![25-11-10 08-43-03 1052](https://github.com/user-attachments/assets/6913a107-05b2-407a-90f4-74ca28d14f80)
