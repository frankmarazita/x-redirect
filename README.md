# x-redirect

A http(s) interface to custom url scheme.

The redirect can be accessed at: [https://frankmarazita.github.io/x-redirect/](https://frankmarazita.github.io/x-redirect/).

### Usage

To use the redirect, simply append the custom url scheme to the end of the url. For example, to redirect to `obsidian://open?vault=Obsidian&file=TODO`, the url would be [https://frankmarazita.github.io/x-redirect/?obsidian://open?vault=Obsidian&file=TODO](https://frankmarazita.github.io/x-redirect/?obsidian://open?vault=Obsidian&file=TODO).

### Who's this for?

This is for anyone who wants to create a link to a custom url scheme that can be shared with others. This is especially useful for creating links that can be opened on mobile devices.

Popular use cases for the project include using it for both Obsidian (which is what I was interested in) or Notion (which is what the original project was created for).

### My Use Case

My use case was that I wanted to link to my specific Obsidian notes from within my personal project workflows. For example, I have some scripts set up to send me reminders to do tasks with specific instructions. These reminders can sometimes be monthly or yearly and I may forget where to look inside of my notes. By linking directly to the note, I can easily access the information I need.

The notifications system I have setup can send notifications of all different types, including emails, text messages, and push notifications, discord messages, etc. By using this redirect, I can easily link to my notes from any of these notification types since they all support opening a standard url.

---

**_Note: This code is based off of [https://github.com/ewerx/x-redirect/](https://github.com/ewerx/x-redirect/)_**
