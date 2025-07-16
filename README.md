# Change-Video-Date
Change's video metadata in Windows Explorer's "Date" column, "Date Created", and "Date Modified" based on information reported in the video title. Video title should be formatted as "YYYY MM DD HH mm" where mm is reported in a 24hr format. <br />
<br />
Example: A video titled "2019 06 04 22 54.mp4" will have its metadata changed to report a "Date", "Date Created", and "Date Modified" to June 4th 2019 10:54 PM
# FFmpeg
The code makes use of FFmpeg <br />
Download the FFmpeg executable from https://ffmpeg.org/download.html <br />
Extract its contents to your desired directory <br />
# Powershell and Variables
Take necessary precautions and back up your data before running the code.<br />
Run the code in Windows Powershell <br />
Change the variables $inputFolder, $outputFolder, and $ffmpeg <br />
<br />
$inputFolder: Variable indicating the folder where your videos are stored <br />
$outputFolder: Variable indicating the folder where your modified videos will be placed <br />
$ffmpeg: Variable directing to ffmpeg.exe <br />
