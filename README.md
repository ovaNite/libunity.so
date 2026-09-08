## Overview

```cpp

Game Base:            0x7FF66C070000
ActorPatch:           0x00CFCE5B (RVA) / 0x7FF66CD6CE5B (Base: 0x7FF66C070000)
CameraPatch:          0x0E6A4795 (RVA) / 0x7FF67A714795 (Base: 0x7FF66C070000)
CodeCaveOne:          0x10D73294 (RVA) / 0x7FF67CDE3294 (Base: 0x7FF66C070000)
CodeCaveTwo:          0x10D78DF4 (RVA) / 0x7FF67CDE8DF4 (Base: 0x7FF66C070000)
ActorTrampoline:      0x000080D2 (RVA) / 0x7FF66C0780D2 (Base: 0x7FF66C070000) (size: 37)
ActorMovAddress:      0x00CFCE57 (RVA) / 0x7FF66CD6CE57 (Base: 0x7FF66C070000)
ActorMov (hex):       48 89 15
ActorPatternIsTypeA:  true
CameraMovAddr:        0x0E6A4779 (RVA) / 0x7FF67A714779 (Base: 0x7FF66C070000) (size: 7)
CameraTrampoline:     0x00052192 (RVA) / 0x7FF66C0C2192 (Base: 0x7FF66C070000) (size: 46)
CameraCaptureReg:     r2  (high=1)
ViewMatrixAddress:    0x11FB8EF0 (RVA) / 0x7FF67E028EF0 (Base: 0x7FF66C070000)
ViewBlockAddress:     0x0 (cam_pos=+0x190 vp_matrix=+0x250)

Signatures:
Actor caller:         65 ? 8B ? 25 58 00 00 00 ? 8B ? ? ? 8D ? ? ? ? 00 ? C1 ? 03
Camera (1/2):         C7 44 24 28 00 08 00 00 4C 89
Camera (2/2):         C7 44 24 28 00 08 00 00
View matrix:          48 8B 0D ?? ?? ?? ?? E8 ?? ?? ?? ?? 90 48 83 C4 58 41 5D 41 5C 41 5F 5E 5B 5F 5D
GameManager:          48 8B 0D ?? ?? ?? ?? 48 85 C9 0F 84 ?? ?? ?? ?? 48 8B 01 FF 90 90 00 00 00
View anchor:          A4 70 7D BF 00 00 00 00 00 00 00 00 00 00 A0 40 00 00 A0 C0 00 00 00 00 00 00 00 00 CD CC 4C 3F 00 00 00 3F 00 00 80 3E

```