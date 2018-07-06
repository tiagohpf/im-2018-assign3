# Spotify Gesture Controller

A software that controls tasks of Spotify with gestures.

## Dependencies

First of all, download and install [Kinect SDK](https://www.microsoft.com/en-us/download/details.aspx?id=44561) to enable the device in your computer. 
After that, install [SpotifyAPI-NET](https://github.com/JohnnyCrazy/SpotifyAPI-NET) and Microsoft Kinect dependencies. 
You can install the packages from NuGet Package Manager Console of Visual Studio's Tools bar, by using the following command:

```
Install-Package SpotifyAPI-NET -Version 2.19.0
Install-Package Microsoft.Kinect
Install-Package Microsoft.Kinect.VisualGestureBuilder.x64 -Version 2.0.1410.19000
```
After that, go to Tools tab again and choose  the option "Manage NuGet Packages for Solution" to check if you have all updates installed.

## How To Run
1. Go to **IM Runtime** folder, open the cmd executable and use the following command:
```
java -jar mmiframeworkV2
```
2. Connect the **Kinect**
3. Open **Spotify**
4. Open and run the two Visual Studio projects: **AppGui** and **gestureModality** 

## Login

To enter in Spotify, you've to use the following credentials:

**E-mail:** d1533276@nwytg.com <br>
**Password:** IM20172018
