# Open Audacity.app on Catalina
Opens Audacity using Terminal for proper usage with Alfred.app on Mac OS 

**You MUST be using Audacity 2.3.3 (or higher) for this to work, since Catalina only supports 64-bit apps and older versions of Audacity are 32.bit apps.**

Since Audacity is not properly supported on Mac OS Catalina, the workaround is to open Audacity using the Terminal to make sure it opens correctly and listens to your microphone. This workflow lets your do that without opening Terminal yourself.

When you first download Audacity 2.3.3 (or higher) and try to open it, Catalina may not let you open it (and give you that unidentified developer error). Here's how to fix that:

Open /Applications in Finder. Cmd+Click on Audacity and choose 'Open', this permanently saves Audacity as an exception so you can open it despite it being from an unidentified developer. After that, you can use `cau` in Alfred to open the app correctly.
