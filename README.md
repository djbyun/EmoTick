# EmoTick: Emotional & Fun Tactile Fidget

An interactive iOS fidget app featuring real-time Apple Metal shaders, synchronized haptic vibrations, and crisp click sounds.

---

## Key Features

* **3×3 Tactile Grid**: 9 distinct interactive buttons with responsive light bursts, dynamic color tints, and satisfying haptics.
* **Apple Metal Shaders**: Real-time 60 FPS graphics with interactive subsurface glow bleed, edge reflections, and dynamic lighting.
* **Crisp Haptics & Audio**: Taptic Engine vibrations synchronized with procedural click sounds.
* **Pure & Distraction-Free**: No ads, no account sign-in, no notifications, and works 100% offline.
* **3-Day Free Trial & Lifetime Pass**: Try everything free for 3 days. Keep it forever with a single one-time purchase ($1.99). No subscriptions.

---

## Technical Architecture

* **Graphics & Rendering**:
  * Built with Apple Metal Shading Language (MSL) and MetalKit.
  * Real-time subsurface glow bleed, Fresnel edge reflections, and reactive lighting.
  * Smooth, locked 60 FPS rendering.

* **Haptics & Audio**:
  * Tactile vibrations powered by `CoreHaptics` (`CHHapticEngine`) and `UIImpactFeedbackGenerator`.
  * Procedural click sounds synthesized in memory using `AVAudioEngine` (4 sound presets).
  * Direct tactile and audio feedback triggered on touch events.

* **StoreKit 2**:
  * Manages the 3-day free trial and one-time Lifetime Pass.
  * Handles purchase and restore directly on-device using StoreKit 2 with no backend server.

* **Offline & Privacy**:
  * Works 100% offline with zero external servers, analytics, or third-party SDKs.

---

## Customer Support & Feedback

If you have any questions, encounter issues, or would like to share feedback, please contact:

* **Support Email**: djbyun@gmail.com
* **Response Time**: Usually within 24-48 hours.

---

## Privacy Policy
* Please review our full [Privacy Policy](PRIVACY.md).

---

## System Requirements
* iOS 17.0 or later
* Compatible with iPhone
