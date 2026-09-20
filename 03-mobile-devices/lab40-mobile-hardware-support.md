# Lab 40 – Mobile Hardware Support

## Scenario

You are a junior IT professional at a small startup company. Your manager has asked you to prepare the marketing director's iPad and notebook computer for an upcoming conference. The iPad requires wireless, security, Bluetooth, and VPN configuration. The notebook computer requires a USB wireless adapter and power-saving configuration.

## Objectives

- Configure the iPad for wireless connectivity.
- Disable Bluetooth and airplane mode.
- Configure iPad passcode security.
- Configure VPN settings.
- Install the fastest available USB wireless adapter.
- Configure laptop power-saving options.

## Technologies

- iPad
- Wi-Fi
- Bluetooth
- VPN
- PPTP
- USB wireless adapter
- Windows Power & battery settings

## Skills Demonstrated

- Configuring mobile wireless settings
- Managing mobile device security
- Configuring VPN settings
- Installing a USB wireless adapter
- Configuring Windows power settings
- Improving laptop battery efficiency

## Procedure

### iPad

1. Open **Settings**.
2. Turn **Airplane Mode** off.
3. Select **Wi-Fi** and turn it on.
4. Select `CorpNet`.
5. Enter the password `@CorpNetWeRSecure!&`.
6. Select **Join**.
7. Select **Bluetooth** and turn Bluetooth off.
8. Select **Touch ID & Passcode**.
9. Select **Turn Passcode On**.
10. Enter the current passcode `1542`.
11. Re-enter `1542` and select **Done**.
12. Set **Require Passcode** to **After 15 minutes**.
13. Turn **Erase Data** on and select **Enable**.
14. Select **General > VPN**.
15. Select **Add VPN Configuration**.
16. Select **PPTP**.
17. Configure the VPN settings:
    - Description: `Office2VPN`
    - Server: `198.28.56.110`
    - Account: `mbrown`
    - Password: Leave blank
18. Leave all other VPN settings at their defaults.
19. Select **Save**.

### Office2-Lap Computer

1. Open the hardware inventory for Office 2.
2. Switch to the back view of the laptop.
3. Expand **Networking Devices** under Inventory.
4. Install the `802.11a/b/g/n/ac USB Adapter` in an open USB port.
5. Switch to the front view of the laptop.
6. Open **Settings**.
7. Select **Power & battery**.
8. Select **Screen and sleep**.
9. For **On battery power, turn off my screen after**, select `10 minutes`.
10. For **When plugged in, put my device to sleep after**, select `30 minutes`.
11. Set **Power mode** to **Best power efficiency**.
12. Close the Settings app.

## Outcome

Successfully prepared the iPad for the conference by configuring CorpNet Wi-Fi, disabling Bluetooth and airplane mode, enabling passcode security, configuring automatic data erasure, and setting up the VPN. The Office2-Lap computer was equipped with the fastest USB wireless adapter and configured for improved battery efficiency.

## Key Takeaways

- Learned how to configure Wi-Fi and security settings on an iPad.
- Practiced configuring mobile VPN settings.
- Learned how to install a USB wireless network adapter.
- Practiced configuring Windows screen, sleep, and power settings.
- Learned how power-saving settings can improve laptop battery life.