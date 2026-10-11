# 🎭 Mimic v1.0.0 — Initial Release

> **A psychological deception party game with an armored, hardware-encrypted privacy vault hidden in plain sight.**

[![Release](https://img.shields.io/badge/Release-v1.0.0%20(Initial%20Launch)-crimson)](../../releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%207.0%2B-blue)](https://android.com)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Offline%20%7C%20Zero%20Tracking-brightgreen)](#privacy--permissions)
[![License](https://img.shields.io/badge/License-MIT-orange)](#-license)

---

## Welcome to Mimic

We are thrilled to introduce **Mimic (v1.0.0)** — an application built around a simple principle: **Plausible deniability through true utility.**

Most private vaults rely on fake calculators or suspicious disguised icons that invite curiosity. Mimic is different: to anyone holding your phone, it is a **fully functional, interactive horror-themed party game**. Behind that disguise lies a military-grade personal vault designed to protect your most sensitive photos, videos, notes, and documents.

---

## Download & Install

Get the official v1.0.0 release APK:

**[Download Latest APK (`mimic-v1.0.0.apk`)](../../releases/latest)**

### Android Installation Steps
1. Download the `.apk` file directly to your phone.
2. Open the file from your Downloads notification or File Manager.
3. If prompted by Android (*"Install unknown apps"*):
   - Tap **Settings** $\rightarrow$ Enable **Allow from this source**.
4. Tap **Install** and open **Mimic**.

*Minimum requirement: Android 7.0 (API level 24) or higher. Supports ARM64 and modern Android devices.*

---

## How to Access the Secret Vault (Gesture Guide)

Mimic has **zero buttons, links, or clues** on its surface that point to a vault. You enter using a secret in-game tap gesture during normal gameplay.

### First-Time Entrance (Setup Sequence)
When you first install Mimic, use the default setup sequence to create your vault:

1. **Start a Game:** On the home screen, tap **Play** $\rightarrow$ choose **Classic** mode $\rightarrow$ select any word pack.
2. **Add Players:** Enter at least **3 player names** (e.g. *Player 1, Player 2, Player 3*) and tap **Start Game**.
3. **Pass & Play:** Tap through the role reveals until you reach the **Voting Screen** where the player voting cards are displayed.
4. **Enter the Gesture Sequence:** Tap the player cards in this exact 3-tap order:
   - **Tap 1:** Tap the **1st Card** (top card)
   - **Tap 2:** Tap the **3rd Card** (bottom card)
   - **Tap 3:** Tap the **2nd Card** (middle card)
   *(Sequence: Card 1 → Card 3 → Card 2)*
5. **Set Your Master PIN:** The screen will trigger a glitch transition animation and reveal the **Vault Setup Screen**. Enter your new 6-digit Master PIN and confirm it.
6. **Save Your Recovery Phrase:** Write down the 12-word cryptographic recovery phrase shown on screen and store it safely offline.

### Changing to Your Own Secret Gesture
Once your vault is initialized:
- Open **Vault Settings** $\rightarrow$ tap **Unlock Gesture**.
- Choose any custom 3-tap pattern of your own. From that moment on, only your personalized pattern will open the vault during gameplay.

---

## Features (Core Vault)

Everything you need to secure your private life is available out of the box with zero subscriptions, zero ads, and zero server connections:

* **Hardware-Backed AES-256-GCM Encryption:** Every file, photo, video, and document is encrypted at rest using keys protected by your device's Android Hardware Keystore enclave.
* **True In-Memory Decryption:** When you view a photo or stream a video, files are decrypted strictly into temporary memory. Decrypted files never touch your flash storage or system gallery cache.
* **Encrypted Media & Document Storage:** Store personal photos, videos, notes, and documents safely away from prying eyes and third-party apps.
* **Smart Storage Optimizer:** Audit your vault anytime to identify space hogs and clean redundant duplicate media files with 1 tap.
* **Plausible Deniability & Decoy Armor:**
  - **Duress PIN:** Set an alternate PIN that opens an innocuous admin screen if you are ever coerced into unlocking your phone.
  - **Intruder Photo Capture:** The front camera silently snaps a photo of anyone who enters the wrong PIN 3 times.
  - **Shake-to-Hide & Recents Blanking:** Shake your phone to instantly return to the game; previews in the Android app switcher are completely blacked out.
* **Armored Encrypted Backups:** Export your entire encrypted vault into a `.mimic` file and restore it on any new device using your 12-word recovery phrase.

> [!TIP]
> **Need more details?** Open your vault and navigate to **Settings → Field Manual** for an in-depth operational guide on locking mechanisms, auto-lock timeouts, and advanced stealth tactics.

---

## The Decoy Game

Mimic is also an engaging social deduction game ready to play anytime with friends:

- **Pass & Play Mode:** Pass one phone around the circle — one player is secretly the impostor Mimic with a different word!
- **Local LAN Multiplayer:** Connect over local Wi-Fi or mobile hotspot to play wirelessly on multiple devices — **no internet connection required**.
- **Thematic Word Packs:** Dark Places, The Occult, Crime Scene, Everyday Dread, and Survival Horror.
- **Multiple Modes:** Classic, Nightmare (two Mimics), and Survival.

---

## Privacy & Permissions

Mimic requests strictly what is necessary for on-device operation:

| Permission | Purpose |
| :--- | :--- |
| **Storage / Media** | To encrypt files you choose to import, and restore them when requested. |
| **Camera** *(Optional)* | For silent intruder selfies and scanning local multiplayer QR codes. |
| **Biometrics** *(Optional)* | Fast fingerprint / face unlock for your vault PIN. |
| **Local Network / Wi-Fi** | Local hotspot multiplayer room discovery. **Never communicates with external cloud servers.** |

---

## Frequently Asked Questions

<details>
<summary><b>Does Mimic ever send data to the cloud?</b></summary>
No. Mimic is 100% offline. There are no servers, no telemetry SDKs, no tracking pixels, and no accounts. Your encrypted files and encryption keys never leave your phone.
</details>

<details>
<summary><b>What happens if I forget my PIN?</b></summary>
On the PIN screen, tap <b>Forgot PIN</b> and enter the 12-word Recovery Phrase generated during your initial setup. Because Mimic uses zero-knowledge encryption, nobody can recover your files without this phrase.
</details>

<details>
<summary><b>Can friends playing the game accidentally find the vault?</b></summary>
No. The voting screen operates normally for regular gameplay votes. The vault only unlocks if the specific 3-tap gesture is entered within a short timeframe.
</details>

---

## 📜 License

Distributed under the MIT License.
