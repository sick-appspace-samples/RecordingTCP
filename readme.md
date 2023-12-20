## RecordingTCP

Introduction to data recording and playback using a TCP stream for data transfer.

### Description

This application can be used to record data into and playback from TCP streams.

The 'ImagePlayer' script creates an ImageProvider which reads bitmap images from the 'resources'
folder. This Provider takes images with a period 1000ms, which are provided
asynchronously to the 'handleNewImage' function.

It includes a user interface, which can be used to:
- show and specify the events recorded.
- specify the data-format to record and playback.
- specify the IP-settings to record to and playback from.
- specify and parametrize the recording mode.
- parametrize the playback.
- start and stop the recording and playback.
- start and stop the data source.
- show the images provided by the data source.
The user interface contains two pages, one for recording and one for playback.
Editing the UI might not work properly in the latest version of SICK AppStudio.
Use SICK AppStudio version <= 2.4.2 to edit the UI.

### How To Run

To demo this script any SIM device and the emulator can be used.
The image is being displayed on the webpage (visit the device ip in the browser) and the meta data is logged to the console.
See also sample 'ImageRecorder'.
Connect a web-browser to the device IP-Address and you will see the web-page of this sample.

### Topics

system, recording, sample, sick-appspace
