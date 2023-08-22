# VidLink : YouTube Video Downloader
**VidLink** is a simple and user-friendly Python script that allows you to effortlessly download high-quality YouTube videos by just pasting the video link. Built using the Pytube library, VidLink ensures a seamless video downloading experience. With minimal input required, users can easily obtain their favourite videos in the best available resolution.

## Stepwise Implementation:
Here's a stepwise breakdown of the code for VidLink:

1. Import the YouTube class from the Pytube library.
2. Prompt the user to input the YouTube video link they want to download.
3. Print a message indicating that the download is in progress.
4. Create a YouTube object by passing the provided video link.
5. Retrieve the stream with the highest available resolution using the get_highest_resolution() method.
6. Inform the user about the title of the video that is being downloaded.
7. Download the video stream to the current working directory using the download() method.
8. Display a message indicating that the download was successful.

With this code, users can quickly and efficiently download YouTube videos in the best quality without any complexity. Just copy and paste the video link, and VidLink will take care of the rest!

## Dependencies

* [Pytube]([https://pypi.org/project/pytube/])

It is recommended to use [Visual Studio Code (version 1.81)](https://code.visualstudio.com/) and use a `Jupyter Notebook`.
