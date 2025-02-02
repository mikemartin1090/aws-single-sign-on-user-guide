# Security keys and built\-in authenticators<a name="mfa-types-keys"></a>

Web authentication \(WebAuthn\), enables strong cryptographic authentication using a variety of interoperable authenticators\. WebAuthn is a core component of FIDO Alliance’s FIDO2 set of specifications\. WebAuthn enables the use of any FIDO2 compliant device as well as backward\-compatible support for U2F devices\.
+ **Security keys –** Users can be authenticated using an external USB/BLE/NFC\-connected security key such as YubiKey or Fetian devices\. Authentication involves simply tapping on a key’s sensor when prompted for MFA\.
+ **Built\-In Authenticators –** Some FIDO2\-enabled authenticators are built into devices\. Examples include TouchID on MacBook or a Windows Hello compatible camera\. Users with such a built\-in authenticator, can simply provide their fingerprint or facial recognition as a suitable second factor\. 

FIDO2 and WebAuthn ensures privacy, as cryptographic data generated on devices is unique across sites and biometric data never leaves the device when used\. FIDO devices are more secure than traditional forms of MFA, as they are strongly attestable and phishing resistant\. For more information about WebAuthn and FIDO2, see [FIDO2: Web Authentication \(WebAuthn\)](https://fidoalliance.org/fido2/fido2-web-authentication-webauthn/)\.

Not all operating systems and browser versions support WebAuthn, so you may have compatibility issues with some U2F devices\. If you experience a compatibility issue, check with your U2F device provider to learn if you’re on an unsupported browser\.