# Reddit Research

## YubiKey Nano Model
* Main draw is portability and security
* Can be stored inside a laptop's HDMI port
* Once inserted, it will act as a normal hardware security key
* Cons
    * Blocks off a port of your laptop/PC
    * Lives inside the machine permanently
    * Harder to carry in keychain
    * No NFC reader for phones/tablet authentication
 
## YubiKey Ci Model
* Cross-platform hardware security key from Yubico designed with dual connectors
* Has a USB-C connector on one end and an Apple Lightning connector on the other

## YubiKey 5 Series
* *YubiKey NFC, YubiKey C NFC, YubiKey Ci, YubiKey Nano, YubiKey C Nano*
* Static Password
    * Setup requires installing YubiKey Manager
    * *Configure Slot* → *Static Password*
    * When logging in: insert key, touch key, automatically types in password
* FIDO2 Strong Single Factor-Passwordless: passwordless tap-n-go secure login
    * *MFA Settings* → *Add Security Key*
    * Insert YubiKey
    * Touch Key
    * When logging in: insert key, touch key
* FIDO2 Strong Two Factor-Authenticator: tap-n-go second factor for 2FA
* Strong Multi-Factor Passwordless: combines tap-n-go authentication with a PIN
    * *MFA Settings* → *Add Security Key*
    * Enter PIN
    * Touch Key
    * When logging in: insert key, enter pin, touch key
* NFC tap-to-phone authentication
    * Open website
    * Choose *passkey*
    * Tap YubiKey via NFC
    * Enter PIN if required
    * When logging in: hold the YubiKey to the back of phone to activate NFC
* Yubico OTP
    * Long string automatically typed by the key
    * Looks like: `ccccccdefghjklrtuv...`
    * Rarely used today
    * Setup requires installing Yubico Authenticator or YubiKey Manager
    * Configure Slot 1 or Slot 2
* OATH-TOTP (Authenticator replacement)
    * Codes are not stored on authenticator app in the phone
    * Setup requires installing Yubico Authenticator
    * Scan website's Authenticator App QR Code
    * QR Code secret gets stored on YubiKey
    * Touch Key
* OATH-HOTP
    * Counter-Based OTP
    * Utilized in older VPNs and Legacy Systems
    * Setup requires installing Yubico Authenticator
* PIV Smart Card
    * Utilizes certificates, smart cards, and corporate certificate authorities
    * Utilized for VPNs, Firewalls, Wi-Fi, and Certificate logins
    * Setup requires installing YubiKey Manager
    * Generate a certificate and private key to store inside YubiKey
* OpenPGP
    * Utilizes SSH, Git Signing, Email Signing, and Public Key Cryptography
    * Generate GPG Key: `gpg --full-generate-key`
    * Make Key Editable: `gpg --edit-key [your-key-id]`
    * Move private key to YubiKey: `keytocard`
* FIDO2/WebAuthn Passkeys
    * Login to site
    * Select *Add Passkey* or *Security Key*
    * Insert YubiKey
    * Touch key
    * Set PIN (first time)
    * When logging in: insert key, enter pin, touch key
* FIDO2 U2F
    * *Google Account* → *Security* → *2-Step Verification* → *Add Security Key*
    * Touch YubiKey
    * When logging in: insert key, touch key
* Challenge-Response
    * Setup requires installing YubiKey Manager
    * Configure Slot 2
    * Connect to KeePassXC, PAM Systems, and Legacy Password Managers
* Support for USB-C and USB-A
* Supports: macOS, Windows, Linux, Android, and iPhone (via NFC)
## YubiKey FIPS Series
* *YubiKey NFC FIPS, YubiKey C NFC FIPS, YubiKey Ci FIPS, YubiKey Nano FIPS, YubiKey C Nano FIPS*
* Validated FIDO2/WebAuthn multi-protocol authenticator lineup
* Essentially the YubiKey 5 Series with FIPS 140-3 validation
* For government, federal agencies, DoD, FedRAMP, CJIS
* Don't buy for personal use or corporate environments
## YubiKey Bio Series
* *YubiKey Bio FIDO, YubiKey C Bio FIDO, YubiKey Bio Multi-protocol, YubiKey Bio C Multi-protocol*
* Applies the *Something You Are* model moreso than the *Something You Have*
* Biometrics can still be compromised:
    * Fingerprints can be copied
    * Fingerprints cannot be changed if compromised
    * Biometrics are an identifier, not a secret
    * Can generate and impersonate a legitimate biometric token
 * FIDO series includes:
    * Fingerprint + FIDO2/WebAuthn
    * USB Login: password, tap-n-go passwordless, or PIN
 * Multi-protocol series adds:
     * Fingerprint + PIV Smart Card
     * Desktop login
     * Enterprise credential management

## YubiKey Security Key Series
* *Security Key NFC, Security Key C NFC*
* FIDO2 USB Login: password, tap-n-go passwordless, or PIN
* FIDO2/WebAuthn up to 100 passkeys
* FIDO2 U2F for older versiosn of WebAuthn used by older applications

## Sources
* [Verify Any YubiKey from Amazon](https://www.reddit.com/r/yubikey/comments/112812v/yubikey_from_amazon/)
