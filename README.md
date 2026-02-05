# Demonstration Videos for Anonymous Submission

This repository contains demonstration videos illustrating the attacks evaluated in an anonymous research study. The videos highlight how accessibility gaps, screen reader limitations, and malware-assisted actions can be exploited to achieve silent and concurrent account access.

---

## Concurrent Account Access by Bypassing Passkeys

This video demonstrates how passkey-based authentication can be bypassed when critical authentication approval information is not communicated by the screen reader. Due to missing or absent spoken feedback during passkey approval, the user is unable to perceive that an authentication event has occurred, allowing the malware to achieve concurrent account access without user awareness.

<video controls width="720">
  <source src="Passkey_Bypass.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## Invisible Overlay over Passkeys to Force Fallback Authentication

This video demonstrates how an invisible overlay placed over passkey authentication can exploit screen reader limitations. The screen reader is unable to access or communicate the underlying content, including the presence of the overlay itself. As a result, blind users are prevented from selecting passkeys and are forced to rely on less secure fallback authentication methods that require manual credential entry.

<video controls width="720">
  <source src="Overlay.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

For reviewer clarity, the overlay in this demonstration is presented as partially transparent rather than fully invisible and does not cover the entire passkey element, allowing the uncovered area to remain visible.

---

