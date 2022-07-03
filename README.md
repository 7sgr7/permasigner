<h1 align="center">Permasigner</h1>
<p align="center">🖊 Permanently signs IPAs on jailbroken iDevices 14.0-14.8.1 (persists on stock).</p>

# How does it work?
In 14.0-15.4.1, there is a bug where CoreTrust will allow any root certificate. 

This script makes a deb file for you based on any IPA. Tested with Taurine and Odyssey.

# Prerequsites
1. Mac OS 10.5.0 (?) or higher, personally tested on 13.0
2. Jailbroken iDevice on 14.0-14.8.1

# How to use
1. Clone this repository: `git clone https://github.com/itsnebulalol/permasigner`
2. Install all requirements: `pip install -r requirements.txt`
3. Edit the app's entitlements in `app.entitlements`
4. Install dpkg using brew
5. Run the script
6. Install the newly created deb file
7. Reboot to stock, the app will still work!
8. ??
9. Profit?

# Credits
- [Linus Henze](https://github.com/LinusHenze) for the bug
- [zhuowei](https://github.com/zhuowei) for the original Taurine script
- [RexSonic](https://github.com/RexSonic) for the fix