# Simple Python Alarm Clock

This is a simple Python alarm clock script that uses the `datetime` library to set and trigger alarms at specific times. It can play an alarm sound using the `winsound` library when the specified time matches the current time.

## Prerequisites

This script is built using Python, and it uses the `winsound` library for playing alarm sounds. To run the script, make sure you have Python installed. You can install the `winsound` library with the following command:

```bash
pip install playsound
```

## Usage

1. Clone the repository or download the `alarm_clock.py` script to your local machine.
2. Open a terminal or command prompt and navigate to the directory where the script is located.
3. Run the script, providing the time in the "HH:MM AM/PM" format as an argument. For example:

   ```bash
   python alarm_clock.py '01:29 PM'
   ```

   This command will set the alarm for 1:29 PM.
4. The script will display the alarm time confirmation message.
5. When the alarm time is reached, the script will print "Alarm is Ringing..." and play the alarm sound repeatedly. To stop the alarm, you can terminate the script by pressing `Ctrl+C`.
6. Enjoy using your Python alarm clock!

## Customization

You can customize this script by:

- Using a different alarm sound: Replace the `'abc'` string in the `winsound.PlaySound()` function with the path to your preferred sound file.
- Modifying the alarm message: Change the print statement inside the `if` block to display a custom message when the alarm rings.
- Using different alarm times: Run the script with different time arguments to set multiple alarms.

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use and modify the script as needed.

## Author

This alarm clock script was created by Levi Chinecherem C. You can reach me at [levi.chinecherem@yahoo.com].

Please note that this script runs in a terminal or command prompt, so it won't work if your computer is in sleep or hibernate mode.
