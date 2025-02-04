# Printer Not Responding

## Symptoms
- The printer does not print documents.
- The printer is offline or not detected by the computer.

## Possible Causes
1. Printer is nor powered on.
2. Printer is not connected to the network or computer.
3. Outdated, corrupted or invalid  printer drivers.
4. Paper jam or low ink/toner.

## Steps to Resolve
1. **Check Power and Connections**:
    - Ensure the printer is ON.
    - Check power cable.
    - Check the power outlet.
    - Lastly it could be a component issue.
2. **Check Network Connection**
    - Restart PC and Printer.
    - Check network cable.
    - Check network options (IP, subnet mask and gateway settings).
        - Could be address conflict.
    - Verify if it is connected to the Wi-Fi.
    - Router issues.
        - Check firewall.
        - **COMPLETE**
3. **Printer Drivers or Software Issues**
    - Ensure the printer is configured as default.
    - Update printer drivers to the latest version from manufacturer's website.
    - Check printer firmware.
    - Reinstall printer and reconfigure network settings.
4. **Paper or Ink/Toner Issues**
    - Open printer and remove jammed paper.
    - Replace ink or toner if empty.
    - Check hardware related to paper jam or ink/toner.
    - Force stop print spooler service.
        - Windows + R, type services.msc.
        - Locate Print Spooler and Stop it.
        - Delete stuck print jobs by going to C:\Windows\System32\spool\PRINTERS.
        - Delete all files in this folder.
        - Go back to Print Spooler Service and Start it.
