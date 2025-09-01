# GTAO_URP
Ground Truth Ambient Occlusion in Unity URP

![image](https://user-images.githubusercontent.com/18096279/209531124-01553c12-083a-48b2-a88a-2b882d8e130e.png)
![image](https://user-images.githubusercontent.com/18096279/209525303-2c2f738a-f943-4003-a9f7-e2e4d54079ae.png)

## Unity 6 Compatibility

This version has been updated for Unity 6 compatibility with the following improvements:

### Changes Made for Unity 6:
- **RTHandle Migration**: Updated from `RenderTargetIdentifier` to `RTHandle` for better memory management
- **Render Target Compatibility**: Added compatibility layer for camera color target access across Unity versions
- **Memory Management**: Improved RTHandle disposal and cleanup for Unity 6's enhanced render target system
- **Backward Compatibility**: Maintained compatibility with earlier Unity versions through reflection-based property access

### Key Features:
- Compatible with Unity 6 and Universal Render Pipeline
- Ground Truth Ambient Occlusion implementation
- Efficient multi-pass blur system
- Support for both forward and deferred rendering
- VR/XR compatible
