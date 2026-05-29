# Reddit Research
* Should be more common in business, for it is easier to add keys to the keychain than having to remember passwords
* Biometric keys are better for multiple accounts, for it is easier to fingerprint than type a PIN multiple times a day
* Always have a backup hardware security key

## Asset Management
* Should be stored in SAFEs or other physically protected locations
     * Should be protected with multiple layers of security
     * CCTV cameras should act as a deterrent towards storage premises
     * Alarms should alert the security team in-case of a breach
* Should be stored onsite along with a backup(s) offsite
* PIN should be stored physically with the hardware key, OR stored in a password manager
* Multiple keys should be kept in *parity*
    * Ensure that multiple YubiKeys are configured identically for the same accounts or services
    * Allows users to have backup keys that can be used interchangeably without losing access if one key is lost or damaged
    * Setup reminders to ensure this consistency


## Multi-Key Setup
* Enterprise-Level
    * User accounts
    * Admin accounts
* User-Level
    * Home
    * Office
    * Offsite


## Products
### YubiKeys
* Entire orgs manage their FIDO2 via Yubikeys for their MFA
* The standard best for multiple user accounts or single admin accounts
* **YubiKey 5 NFC**
    * OTP feature
    * PIV feature
    * Overkill for user-use I have a Yubikey 5 NFC, but since I'm not really using the OTP or PIV features, it's a bit overkill to be honest, would have been fine with the Security Key series. I also have some Google Titans that's got only FIDO2 for my admins, they work just fine as well.


* **YubiKey 5 USB A**
    * Keep 2 keys for personal user accounts
* **YubiKey Security Key C**
    * Keep 2 for work

## Feitian
* Biometric hardware security key best for managing multiple admin accounts

## Google Titan
* Best for admin accounts

## Sources
* [Fido2 Hardware Key authentication](https://www.reddit.com/r/sysadmin/comments/1srbeyj/fido2_hardware_key_authentication/)
