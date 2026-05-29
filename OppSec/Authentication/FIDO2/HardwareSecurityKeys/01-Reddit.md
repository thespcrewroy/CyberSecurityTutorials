# Reddit Research
* Should be more common in business, for it is easier to add keys to the keychain than having to remember passwords
* Biometric keys are better for multiple accounts, for it is easier to fingerprint than type a PIN multiple times a day
* Always have a backup hardware security key
* PINs provide protection against stolen laptop or security key device
* The physical aspect of this tool protects it against remote access control and keylogger attacks

## Asset Management
* Should be stored onsite along with a backup(s) offsite
* On-site nano keys can be stashed inside laptops
* On-site regular-sized keys can be clipped to the access keys of employee lanyards
* Off-site key should be stored in SAFEs or other physically protected locations
     * Should be protected with multiple layers of security
     * CCTV cameras should act as a deterrent towards storage premises
     * Alarms should alert the security team in-case of a breach
* Enable PIN/Password
    * PIN should be stored physically with the hardware key OR stored in a password manager
    * Keep in-mind to also always have PIN/password protection on your physical machine
    * Keep in-mind to log out of your machine when you are done using it
* Enable AAGUID Attestation
    * Setup for specific keys
    * Set that policy to a breakglass account so they cannot add another software's passkey to the account
* Keys should be kept in *parity*
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

### (7) YubiKeys
* Entire orgs manage their FIDO2 via Yubikeys for their MFA
* The standard best for multiple user accounts or single admin accounts
* **(3) YubiKey Security Key 5C**
    * Keep 2 for work
* **(2) YubiKey 5 NFC**
    * OTP feature
    * PIV feature
    * Smack them against a reader and type in a PIN
    * Overkill for normal user-use
* **YubiKey Security Key 5C Nano**
    * Can be stored within the laptop
* **YubiKey 5 USB A**
    * Keep 2 keys for personal user accounts
    * Best for its portability to be easily locked away
* **YubiKey 5 USB C**


## (2) Feitian
* Biometric hardware security key best for managing multiple admin accounts
* Many different styles and interfaces for FIDO2 keys
* OTP token feature

## Google Titan
* Best for admin accounts

## Sources
* [Fido2 Hardware Key authentication](https://www.reddit.com/r/sysadmin/comments/1srbeyj/fido2_hardware_key_authentication/)
