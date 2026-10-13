# Lab 42 – Configure Network Printing

## Scenario

In a busy office, protecting the confidentiality of printed documents is important, especially when handling sensitive information. A director wants to share the HP Photosmart Plus printer connected to Office1 so employees can print documents to that location. The task is to share the printer on Office1 and add it to Office2 as the default printer.

## Objectives

- Share the HP Photosmart Plus printer on Office1.
- Configure the printer sharing settings.
- Allow client computers to render their own print jobs.
- Add the shared printer to Office2.
- Set the shared printer as the default printer.

## Technologies

- Windows printer settings
- HP Photosmart Plus printer
- Printer sharing
- Shared network printer
- Office1 and Office2 computers

## Skills Demonstrated

- Configuring printer sharing
- Managing printer properties
- Adding a shared network printer
- Configuring client-side print rendering
- Setting a default printer

## Procedure

### Office1 – Share the Printer

1. Right-click **Start** and select **Settings**.
2. Select **Bluetooth & devices**.
3. Select **Printers & scanners**.
4. Select **HP Photosmart Plus**.
5. Select **Printer properties**.
6. Open the **Sharing** tab.
7. Select **Share this printer**.
8. Use the share name `HP Photosmart Plus`.
9. Verify that **Render print jobs on client computers** is checked.
10. Select **OK** to save the settings.

### Office2 – Add the Shared Printer

1. From the top navigation area, select **Floor 1 Overview**.
2. Under Office 2, select **Office2**.
3. Right-click **Start** and select **Settings**.
4. Select **Bluetooth & devices**.
5. Select **Printers & scanners**.
6. Select **Add device**.
7. Find **HP Photosmart Plus on Office1**.
8. Select **Add device**.
9. Wait for the printer to finish installing.

### Office2 – Set the Default Printer

1. Select **HP Photosmart Plus on Office1**.
2. Select **Set as default**.
3. Verify that the shared printer is configured as the default printer.

## Outcome

Successfully shared the HP Photosmart Plus printer on Office1, enabled client computers to render their own print jobs, and added the shared printer to Office2. The shared printer was then configured as the default printer on Office2.

## Key Takeaways

- Learned how to share a printer with other computers.
- Practiced configuring printer sharing properties.
- Learned the purpose of rendering print jobs on client computers.
- Practiced adding a shared printer in Windows.
- Learned how to set a shared network printer as the default printer.