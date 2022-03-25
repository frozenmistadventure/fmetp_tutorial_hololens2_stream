# fmetp_tutorial_hololens2_stream

<STRONG>fmetp_tutorial_hololens2_stream</STRONG> is a Hololens2 Streaming tutorial template for <STRONG>FMETP STREAM</STRONG>, it means that FMETP STREAM is required.

<STRONG>FMETP STREAM</STRONG> share your Game View to any platforms.
Adding Live Stream feature into your apps with ease!

- Asset Store Link: https://assetstore.unity.com/packages/slug/202537

Support: thelghome@gmail.com

//----------more notes for testing----------

//testing Unity Version: Unity 2021.2.7f1

//testing environment: local network via wifi

//system: windows 11 (firewall off), hololens 2

There are 3 demo scenes inside "_Scene" folder:

Demo_FMNetworkStreaming_PC -> This is the Viewer app(as Server)

TestScene_UDP_Client_MainCam -> This is for HoloLens 2(as Client), streaming Live View with webcam texture via Main Camera

TestScene_UDP_Client_RenderCam -> This is for HoloLens 2(as Client), streaming Live View with webcam texture via Render Camera


Step 1: download the template from github

Step 2: import the latest FMETP STREAM from package manager( which you purchased on Unity Asset Store)

Step 3: Switch Build Platform to Universal Windows Platform

Step 4: Select either "TestScene_UDP_Client_MainCam" or "TestScene_UDP_Client_RenderCam" for HoloLens UWP Build

Step 5: Depoly the UWP Build via Visual Studio

Step 6: Run the "Demo_FMNetworkStreaming_PC" on Unity Editor, which is the viewer app


