# kinectgesturecollection
Collection of code samples, documentation, dependencies for Kinect V2 depth camera

Kinect V2 is [getting sunsetted](https://www.fastcodesign.com/90147868/exclusive-microsoft-has-stopped-manufacturing-the-kinect), this repo will serve as an effort to document/collect the relevant components for maintenance/development of gesture applications exploiting its depth camera

The Kinect V2 sensor [requires the following](https://developer.microsoft.com/en-us/windows/kinect/hardware-setup):

```
64-bit (x64) processor
Physical dual-core 3.1 GHz (2 logical cores per physical) or faster processor
USB 3.0 controller dedicated to the Kinect for Windows v2 sensor or the Kinect Adapter for Windows for use with the Kinect for Xbox One sensor
4 GB of RAM
Graphics card that supports DirectX 11
Windows 8 or 8.1, Windows Embedded 8, or Windows 10
```

You must install the [Kinect V2 SDK (includes "SDK Browser")](https://www.microsoft.com/en-us/download/confirmation.aspx?id=44561) for access to [Kinect Studio (record gesture clips)](https://msdn.microsoft.com/en-us/library/hh855395.aspx) and [Visual Gesture Builder create gestures from clips)](https://msdn.microsoft.com/en-us/library/dn785503.aspx)


## Documentation

- Kinect API Docs: https://github.com/Kinect/Docs/blob/master/Kinect4Windows2.0/k4w2.md

- [Kinect Visual Gesture Builder (video)](https://channel9.msdn.com/Blogs/k4wdev/Custom-Gestures-End-to-End-with-Kinect-and-Visual-Gesture-Builder)

- [Kinect Visual Gesture Builder](https://aka.ms/k4wv2vgb) ([pdf](docs\Visual_Gesture_Builder_A_Data_Driven_Solution.pdf))


## Drivers & libraries

See [Microsoft File Checksum Integrity Verifier](https://www.microsoft.com/en-us/download/details.aspx?id=11533) tool for checksums

- [Kinect V2 SDK (includes "SDK Browser")](https://www.microsoft.com/en-us/download/confirmation.aspx?id=44561)

- [Kinect V2 SDK runtime](https://www.microsoft.com/en-us/download/details.aspx?id=44559)

## Useful Gesture Samples (Visual Gesture Builder)


|  Name                                                                                                                            | Remarks                                                                |
|---                                                                                                                               |---                                                                     |
| [DiscreteGestureBasics-WPF](./samples/DiscreteGestureBasics-WPF)                                                                 | Also available in "SDK Browser" in the SDK                             |
| [DiscreteGestureBasics-XAML](./samples/DiscreteGestureBasics-XAML)                                                               |  Also available in "SDK Browser" in the SDK                            |
| [ContinuousGestureBasics-WPF](https://github.com/angelaHillier/ContinuousGestureBasics-WPF)                                      | See anything by [Angela Hiller](https://github.com/angelaHillier)      |
| [CPP Visual Gesture Builder](https://github.com/K4W2-Book/K4W2-Book/tree/master/C%2B%2B(Native)/11_Gesture/KinectV2-Gesture-01)  | C++ approach for reading in a gbd (gesture database) file              |
| [Kinect Studio Source](https://github.com/angelaHillier/Kinect-Studio-Sample)                                                    | Full source code for Kinect Studio                                     |


## Windows Bootcamp Resources

 - Windows 10 ISO: https://www.microsoft.com/en-us/software-download/windows10ISO

 - Bootcamp Instructions: https://9to5mac.com/2017/01/23/how-to-install-windows-10-mac-boot-camp-assistant-partition-video

## Unofficial

- https://github.com/OpenKinect/libfreenect2

## Useful Answers

- Tagging for negative: https://social.msdn.microsoft.com/Forums/en-US/9613bef0-b71c-4b02-acb7-af6b23523abf/visual-gesture-builder-training-for-the-negative?forum=kinectv2sdk

- Troubleshooting: https://social.msdn.microsoft.com/Forums/en-US/20dbadae-dcee-406a-b66f-a182d76cea3b/troubleshooting-and-common-issues-guide?forum=kinectv2sdk
