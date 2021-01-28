# Notes for data science courses at University of Birmingham

These are a series of notes, largely ported from the 2019 version of these
courses at <https://github.com/matthew-brett/cfd2019>.

They currently mostly refer to the 2020 course, at
<https://github.com/matthew-brett/cfd2020>.

## Editing subtitles

* Panopto canvas section, e.g <https://canvas.bham.ac.uk/courses/47250/external_tools/12214>>
* Click on Settings for video of interest.
* Select Captions from list at left.
* Click on "Available Captions" "English (United Kingdom)".
* "Download file".  This gives a filename `GenerateSRT.ashx` by default.  In
  fact this is in [SRT
  format](https://www.ai-media.tv/what-is-an-srt-file-and-how-to-use-one).  Put
  into version control in `captions` folder, with suitable name.
* Edit.  I use Vim to edit on one screen, with the Panopto video playing in the
  other, in a browser window.  Play at 0.75 speed.  May be worth doing a first
  pass through for obvious stuff before reviewing.
* Save.
* Go back to Panopto Canvas section, Settings for video.
* Delete original captions.
* Upload captions select English (United Kingdom)
* Browse, select edited SRT file.
* Upload.
* Click on some other option on list to left, then Captions, to refresh.  You should see you have available captions again.
* You may have to wait a few seconds for Panopto to finish "Embedding captions".
* Play the video with captions to check you have the right ones.
