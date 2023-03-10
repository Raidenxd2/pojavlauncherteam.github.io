# Exporting videos with Replay Mod (not finished)
NOTE: This works for both rooted and unrooted users

1. Download the ffmpeg binary [here](https://github.com/Khang-NT/ffmpeg-binary-android/releases/tag/2018-07-31). Choose one according to your device’s architecture. (Important: You should use the full version of the executable. Using the lite variant may cause unknown crashes.)

1.5. (For GitHub builds) Due to the limit of Replay’s command window, you need to rename the executable to a short name, like -> :fr:. Let’s call it \<exec_name>.

2. Install an APK Editor from Google Play or everywhere else.

3. Follow the instructions of the app to add the executable to /lib/\<device_architecture> folder of the  APK. Then build the APK and install it.

3.5. (Required for a clean install) Install everything needed (Forge, Replay Mod).

4. Now launch Minecraft. We aren't done yet, so force close it after launching.

5. Find latestlog.txt (if you dont know how to get to it goto [this page](./LOGS.md)) Open it and find this line:
Added custom env: POJAV_NATIVEDIR=\<a_directory>
Copy the \<a_directory> part.

6. Launch the game again, go to Replay Viewer and load the record you want to export.

7. Follow Replay’s instructions to add keyframes, then (press T show mouse cursor and) click at “Render Camera Path”.

8. Scroll to the bottom, paste the text you copied in step 6 into the first command line window, then write “/\<exec_name>” (step 2.5) at the end of the text line.

9. Tap “Render” and enjoy your video.

Thanks DuyKhanhTran and NekoIceCream for the initial idea for rooted environments.