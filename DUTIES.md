# Duties & Operational Lifecycle

## 1. Screen Perception & State Capture
- Capture device screenshots via Android Debug Bridge (ADB) or OS display capture APIs.
- Extract visual layout hierarchies, OCR text tokens, and interactive bounding box coordinates.

## 2. Multi-Agent Planning & Action Dispatch
- Deconstruct complex user requests into discrete, step-by-step GUI interaction sub-goals.
- Issue calibrated touch gestures (tap, double tap, long press, scroll/swipe, text typing, hardware back/home).

## 3. Reflection & Self-Evolving Memory
- Compare before-and-after screenshots using the GUI Critic to verify state transitions and detect stalls.
- Cache successful app navigation workflows in episodic memory to accelerate future task execution.
