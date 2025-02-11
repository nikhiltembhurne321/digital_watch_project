# digital_watch_project
"Robot Eyes with Digital Watch Mode – Button-Controlled Display"  This project implements a robotic eye animation that can switch to a digital watch display when a button is pressed. It is designed for embedded systems using a microcontroller and an OLED display.
Features:
RTC Time Display: Fetches real-time data from the DS3231 module and displays time and date on the OLED.
Interactive Eye Animations: Includes various eye expressions such as blinking, happy eyes, sleeping, and saccade movements.
Push Button Control: Toggles between real-time clock and animated eyes.
Serial Command Input: Allows animation control via serial commands.
Demo Mode: Automatically cycles through different eye animations.

Components Used:
Arduino Board (Uno, Mega, or similar)
RTC Module (DS3231) for real-time clock functionality
OLED Display (SSD1306, I2C) for graphical output
Push Button to switch display modes
