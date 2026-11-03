# EmoTick: Emotional & Fun Tactile Fidget

An interactive iOS fidget app featuring real-time Apple Metal shaders, synchronized haptic vibrations, and crisp click sounds.

---

## Key Features

* **3×3 Tactile Grid**: 9 distinct interactive buttons with responsive visual deformations, light bursts, and satisfying haptics.
* **Apple Metal Shaders**: Real-time 60 FPS graphics with interactive glow bleed, edge reflections, and dynamic lighting.
* **Crisp Haptics & Audio**: Taptic Engine vibrations tightly synchronized with procedural click sounds.
* **Pure & Distraction-Free**: No ads, no account sign-in, no notifications, and works 100% offline.
* **3-Day Free Trial & Lifetime Pass**: Try everything free for 3 days. Keep it forever with a single one-time purchase ($1.99). No subscriptions.

---

## Technical Architecture

* **Graphics & Rendering**:
  * Built with Apple Metal Shading Language (MSL) and MetalKit.
  * Real-time mesh vertex displacement, subsurface glow bleed, and Fresnel edge reflections.
  * Smooth, locked 60 FPS rendering with low frame-time overhead.

* **Audio & Haptic Synchronization**:
  * Low-latency pipeline coupling CoreHaptics transient haptic patterns with AVAudioEngine sound synthesis.
  * Synchronized touch-down response across visual deformation, haptic impulse, and acoustic feedback.

* **StoreKit 2**:
  * Built on modern Swift concurrency (`async/await`) and StoreKit 2 transaction listeners.
  * Local, on-device entitlement verification.

* **Offline-First**:
  * 100% standalone execution with zero external network dependencies or telemetry SDKs.

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
