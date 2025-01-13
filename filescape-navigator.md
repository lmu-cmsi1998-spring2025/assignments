**CMSI 1998** Special Studies: Software Carpentry, Spring 2025*

*_The phrase “software carpentry” was coined by Greg Wilson and Brent Gorda in 1998:
https://software-carpentry.org/_

# Episode 0122: Filescape Navigator
For the first episode of your hit podcast/video channel, you will demonstrate your ability to zip around your computer’s file system solely using the command line. To provide you with some structure, we’ll ask everyone to embark on the same general journey. However, the particulars of past code you have written and how you organize your files will distinguish your individual video from those of the rest of the class:
1. Pick a past programming project and note where it’s located on your computer
2. Starting with a command line located in your home folder, `cd` into that past project’s location and show the audience around:
   * Describe your project briefly: What does it do? When did you write it? etc.
   * Upon arriving at the project’s folder, use `ls` to show the viewer its top-level files. As applicable, describe the files and the roles they play in your project
   * Use `more`/`less` to skim through some files of interest, especially the source code! Feel free to pick segments that you’d like to show
   * When using `more`/`less`, show that you can move backward/forward through the file (<kbd>j</kbd>, <kbd>k</kbd>, <kbd>b</kbd>, <kbd>space</kbd>), and that you can jump to certain parts via search (<kbd>/</kbd>-query and <kbd>n</kbd>, etc.)
   * If your project has additional folders, don’t hesitate to `cd` further into them to show additional files of interest
3. When you’re done showing your project, let’s switch to a programming language that you have on your device:
   * Use the `which` command to figure out where it’s located (e.g., `which python`)
   * `cd` to that location, then use a combination of `ls`, `cd`, and `more`/`less` to peek around the files that comprise your language’s implementation
   * It’s understood that you won’t necessarily understand what you see here; but the point is to show that you can navigate through “unexplored territory” on your computer via the command line
4. In addition to the specific commands/actions listed above, make sure to find opportunities to do the following as well:
   * Use `pwd` to confirm where you are located on the file system
   * Use arrow keys to navigate through your history if you need to perform the same or similar command again
   * Use <kbd>control</kbd>-<kbd>r</kbd> to do the same, via search
   * Edit your command as needed, using keyboard shortcuts when possible (e.g., <kbd>control</kbd>-<kbd>a</kbd>, <kbd>control</kbd>-<kbd>e</kbd>, <kbd>meta</kbd>-<kbd>f</kbd>, <kbd>meta</kbd>-<kbd>b</kbd>, <kbd>meta</kbd>-<kbd>d</kbd>, etc.)
   * Use <kbd>tab</kbd> for autocomplete to save on typing
   * Anything else that might have caught your eye in class

## Video Specifications
To make sure that we get the key information that we need from your video, all non-interstitial segments (i.e., the parts where you’re showing your command-line skillz) should be formatted as follows:
* The contents of your command line window should be easily readable, including commands that you are in the middle of typing
* You must be visible live onscreen (thumbnail, overlay, etc.), and what you say should be sync-ed up with the audio and what you’re typing
In other words, it must be clear that what’s happening on the command-line screenshare is going on live with your in-person spoken commentary. Any evidence to the contrary will have…undesirable consequences

> Although no particular video software is prescribed for the course, note that the above requirements are easily met by using Zoom. Start a new “meeting” that includes yourself, turn on your camera, share your window or screen, and record. That should pretty much do it

Mistakes are perfectly OK! No need to re-record yourself if you mistype something. In fact, showing how you recover from mistakes live is a good way to reinforce your skills, because such mistakes _will_ happen in real life. If your command has a typo or somehow fails, just try it again and keep going

That said, it’s also perfectly OK to “practice” beforehand. Navigate through the folders and look at files on your own first, before recording the video. That will give you a sense of what you’ll see, such that when you do it with the camera/mic on, you’ll be generally prepared. Casual mistakes will also be easier to recover from if you practice beforehand

## How to Turn it In
Upload the final video file to the corresponding assignment slot in Brightspace. If the file is too large, find an alternative way to host the file then link to it in your Brightspace submission. Ideally this won’t be necessary

## Specific Point Allocations
For this particular episode, graded categories are as follows:

| Category | Points |
| -------- | -----: |
| Expected content | 25 points total |
| • Brief description of a past programming project | 5 points |
| • Navigation of a past programming project | 10 points |
| • Navigation of a programming language installation | 10 points |
| Proficiencies to demonstrate | 75 points total |
| • Moving around folders (`cd` etc.) | 15 points |
| • Displaying text files (`more`/`less` and keyboard controls within) | 15 points |
| • Using <kbd>tab</kbd> autocomplete to save on typing | 15 points |
| • Locating where programs reside (`which`) | 10 points |
| • Using command history to save on typing (arrow keys, <kbd>control</kbd>-<kbd>r</kbd>, etc.) | 10 points |
| • Editing the current command (moving back and forth, making changes) | 10 points |
| Fun factor (counted only if content and proficiencies are complete) | extra credit |
| Sus-looking footage | deduction only |
| Punctuality | deduction only |
| **Total** | **100** |

Regarding the fun factor extra credit, as noted in the syllabus, entertainment value makes informative videos better but it does not redeem uninformative ones. Make sure that your episode has the requested content and you show the desired proficiencies first before spending time on sprucing things up. Otherwise, extra credit will not be included

Graders reserve the right to impose additional overall deductions if anything that seriously detracts from effective fulfillment of the assignment’s objectives is noted, even if it does not match any specific category above
