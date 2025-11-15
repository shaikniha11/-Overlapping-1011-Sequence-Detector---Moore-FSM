# -Overlapping-1011-Sequence-Detector---Moore-FSM
Sequence detection is a fundamental operation in digital communication systems, protocol analyzers, and pattern recognition circuits. This project implements a Moore Finite State Machine to detect the specific binary pattern "1011" with two operational modes:  
- Overlapping Mode: Continues scanning after detection, allowing sequences to share bits
- Non-Overlapping Mode: Resets to initial state after detection, requiring complete restart
- Dual Moore FSM Variants: Separate implementations for overlapping/non-overlapping
-  One-Hot State Encoding: Optimized for speed and simplicity
-  Bit Reuse Capability: Overlapping variant efficiently reuses matching bits
-  Edge-Case Verified: 9 comprehensive test scenarios
-  Glitch-Free Outputs: Registered output prevents combinational hazards
-  Synchronous Design: Single clock domain, clean timing
-  Asynchronous Reset: Immediate initialization to known state
-  Scalable Architecture: Easy adaptation to other patterns
  
