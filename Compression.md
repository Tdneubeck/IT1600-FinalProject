# Storage and Compression

### Storage
A big emphasis of Digital audio is the trade-off between the quality of the digital audio sound and the amount of space it takes up on the drive. this is such a big emphasis because the difference between sizes is so large that it makes a difference. To find the amount of data each file of digital Audio takes up we use this formula:
> #### Formula for the Size of Audio file
> Size (Bytes) = Frequency(samples/second) * **Bytes/Sample** * length of audio (seconds) * Channels of audio
>

This formula is the reason for the large difference in file size based on frequency and the bits per sample. For example, if there are 8 bits per sample rather than 16 bits per sample, that is 44,100 less bytes per second of audio. 

### Lossy vs. Lossless Compression
![loss](https://i.pcmag.com/imagery/encyclopedia-terms/lossless-compression-lossy.fit_lim.size_1050x.gif)
#### Lossy
There are two ways that audio files are compressed much like images. In lossy compression, the audio gets manipulated in different ways to reduce the file size. One of the most popular forms of lossy compression is an MP3 file. this compresses the file by removing the samples that are near the same value and is unable to hear the change between the samples. this reduces the size by up to 95%.
#### Lossless
The other form of compression is lossless compression. This focuses on keeping all of the data of the file intact while reducing the size. This is popular with audio that has to be manipulated like movies and music editing. A popular type of Lossless compression is FLAC (Free Lossless Audio Codec). FLAC uses encoded data in frames to reduce the size of the file to 50% of its original file.

[Next](audiotypes.md)
[Back](DigitalAudio_overview.md)
[Home](README.md)
