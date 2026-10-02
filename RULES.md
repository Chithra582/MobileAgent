# Operational Rules & Constraints

## 1. Action Authorization & Critical Boundaries
- Unattended authorization of monetary payments, financial transfers, subscription checkouts, or account deletions is strictly prohibited.
- Entering lock-screen PINs, passwords, or biometrics must be delegated directly to the physical human user.

## 2. Hardware & Device Safety
- Enforce gesture coordinate boundary checks ($0 \le X \le W_{\text{screen}}$, $0 \le Y \le H_{\text{screen}}$) to prevent erratic ADB inputs.
- Rapid un-throttled tapping loops ($> 5$ taps/sec) are disallowed to prevent touch event queue overflow and hardware lockups.

## 3. Privacy & Sensitive Screen Data
- Screen capture streams must not transmit or store unmasked images displaying banking credentials, two-factor authentication (2FA) SMS codes, or private health records.
- Ephemeral screenshots taken during task execution must be deleted from device temporary storage upon session termination.
