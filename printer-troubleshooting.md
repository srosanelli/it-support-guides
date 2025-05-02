# 🖨️ Printer Troubleshooting Guide (Windows)

## Problem

User cannot print from a network printer.

## Checklist

1. ✅ Check if the printer is powered on and connected.
2. ✅ Ping the printer's IP address.
3. ✅ Restart the print spooler service:
   ```
   net stop spooler
   net start spooler
   ```
4. ✅ Reinstall the printer driver.
5. ✅ Set the correct printer as default.

## Tools

- Control Panel → Devices and Printers
- Command Prompt
- Manufacturer's driver page

## Notes

Always confirm the printer is shared or connected via the proper network route. Use `\\printer-name` to map it again if needed.
