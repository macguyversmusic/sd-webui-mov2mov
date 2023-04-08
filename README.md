## Mov2mov
##translated by MacGuyver - 08-04-2023
![img.png](images/2.jpg)

Plugin for Automatic1111/stable-diffusion-webui's Mov2mov plugin.

Features:

    Process frames directly from video.
    Pack the processed frames back into a video file.
    Preprocess and post-process videos by performing operations like segmentation, compositing, etc.
    Extract portrait subject.
    Composite transparent background.
    Composite original background.
    Composite green screen.
    Composite specified image background.
    Composite specified video background.
    Process prompt and negative_prompt frame by frame:
        Use *frame_number:prompt|| to mark the beginning and end of the prompt.
        *1:1girl||*100:2girl|| means to use 1girl from frame 1 to frame 99, and use 2girl from frame 100 to the end.
        The same applies to negative_prompt.

Installation:

    Open the Extension tab.
    Click on Install from URL.
    Enter the git repository URL for the extension.
    Click Install.
    Restart WebUI.

Usage:

    You must obtain authorization for the video source yourself. Any problems caused by using unauthorized videos for conversion will be entirely your responsibility and have nothing to do with mov2mov!
    Any videos made using mov2mov that are uploaded to video platforms must clearly indicate the video source in the description. For example, if you are using someone else's video and converting it with AI, you must provide a clear link to the original video; if you are using your own video, you must also provide an explanation in the description.
    You are solely responsible for any infringement issues caused by the input source. Note that many videos clearly state that they cannot be reproduced or copied!
    Please strictly abide by relevant national laws and regulations to ensure that the content is legal and compliant. Any legal liabilities caused by the use of this plugin will be entirely your responsibility and have nothing to do with mov2mov!

Notes:

    The packed video is stored in the directory outputs/mov2mov-images/.
    OpenCV may need to be installed.
    The directory cannot have Chinese characters!!!

FAQ:

    Currently known to conflict with the Additional Networks extension.

Additional information:

    Video tutorials: https://www.bilibili.com/video/BV1Mo4y1a7DF and https://www.bilibili.com/video/BV1rY4y1C7Q5.
    QQ channel: https://pd.qq.com/s/akxpjjsgd.
