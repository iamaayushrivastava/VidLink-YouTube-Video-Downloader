# VidLink : YouTube Video Downloader
**VidLink** is a simple and user-friendly Python script that allows you to effortlessly download high-quality YouTube videos by just pasting the video link. Built using the `pytube` library, VidLink ensures a seamless video downloading experience. With minimal input required, users can easily obtain their favourite videos in the best available resolution.

## Stepwise Implementation
Here's a stepwise breakdown of the code.

1. Import the YouTube class from the `pytube` library.
2. Prompt the user to input the YouTube video link they want to download.
3. Create a YouTube object by passing the provided video link.
4. The user is presented with the available video quality options, and they can choose a stream by entering the corresponding number. 
5. Print a message indicating that the download is in progress.
6. Inform the user about the title of the video that is being downloaded.
8. Download the video stream to the current working directory using the download() method.
9. Display a message indicating that the download was successful.

With this code, users can quickly and efficiently download YouTube videos of the best quality without any complexity. Just copy and paste the video link, and VidLink will take care of the rest!

### Note
* VidLink 1.0 - Retrieve the stream with the highest available resolution using the get_highest_resolution() method.
* VidLink 1.1 - The user is presented with the available video quality options, and they can choose a stream by entering the corresponding number.

## Dependencies

* [pytube]([https://pypi.org/project/pytube/])

It is recommended to use [Visual Studio Code (version 1.81)](https://code.visualstudio.com/) along with a `Jupyter Notebook` for an efficient and seamless development experience.
