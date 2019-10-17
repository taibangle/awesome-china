# Bypassing Censorship on Chinese Social Media (e.g. WeChat)

Social media platforms use different kinds of tools to censor content. The most effective and primitive ones are to automatically shadowban (meaning the content will only appear visible to the person who posted it) messages that contain a banned phrase, such as "Tiananmen Square Massacre", and the file hash of images and videos.

If no one appear to like or comment on your post, then you can check if it's visible on your friend's account.


## Circumvent Sensitive Phrases

You will in most cases be able to prevent having your post shadowbanned while discussing sensitive topics by using simple techniques. For instance, if you wanted to post something containing the phrase "Tiananmen Massacre", then you could post it as such:

- Tiananmen Masssacre (purposely misspell the sensitive words)
- Ti.ananm.en Mass.acre (insert symbols or spaces in-between sensitive words)


## Circumvent Sensitive Image/Video Files

All files have a unique MD5 hash, which will never change unless the file has changed. This is used to prevent storing duplicated files, as well as to prevent people from uploading files that are banned for whateverreason. If you tried to download the Tank Man image below, and posted it on WeChat, then your post would undoubtedly be shadowbanned. However, any change to the image will give it a new MD5 hash - no matter how small the change is.

You would therefore be able to post the picture using one of these simple techniques:

- Open the picture in a drawing app and put a dot (changing a single pixel will give it a new MD5 hash)
- Slightly resize or rotate the picture
- Take a screenshot of the picture and upload the screenshot
- Open the picture on another device and take a picture of the picture
- Save the picture in a new format

As for videos, you can:
- Record your phone screen while playing the video, and then upload your screen recording
- Play the video on another device and then record the playback with your phone
- Use a video editing app to slightly trim/edit the video
- Use a video editing app to save the video in a different format

Remember, you must perform these actions outside the Chinese app.

In most cases, then it will be possible to beat the system using these simple techniques.


I have heard that WeChat also do post-processing of images where they try to detect similarities with blacklisted images, and will then manually review the images that has a match percentage reaching a certain threashold.
This means that even if a picture/video hasn't been added to the blacklist yet, then it's a good idea to take the steps above. Why? Because if you share a picture then it's likely one of your friends will download the picture and share it as well. Your friends friend may do the same, and this process could repeat itself over a thousand times. But if everyone is sharing the exact same image file (same MD5 hash) then it will become impossible for the picture to spread further once the MD5 hash has been added to their blacklist.

For instance, imagine these scenarios:

Scenario 1: You have an image with this MD5 hash: f3ed31ea55ac1d3fa8ed4dc969eb1dcf. This image has been shared 1000 times and is then added to the blacklist. Everyone who try to share it further won't be able to do so, because they are all trying to share the file with the exact same MD5 hash.

Scenario 2: You have an image which has been slightly modified in 10 different ways (by different people), so you have 10 different MD5 hashes of a picture that looks identical. Each modified picture has been further shared with 100 people, meaning it has been shared 1000 times in total. One of the images' MD5 hash is added to the blacklist, and it will thus be impossible to share that picture (which has already been shared 100 times) further. However, the other 9 MD5 hashes (which have already been shared 900 times) have not been blacklisted yet, and can therefore still be shared.

As you can see, by slightly modifiying the image before sharing it, then you greatly increase the chance that it will be able to spread to more people.


![Tank Man](https://raw.githubusercontent.com/taibangle/awesome-china/master/images/tankman.jpg)