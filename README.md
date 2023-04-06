# Microsoft 365 vs Google Workspace 

January 2020 until September 2021 I used Google Workspace (aka GSuite).

Since September 2021 I use Office 365, since my new employer uses it.

To make it short: I am not happy with Microsoft Office 365.

I list here some notes.

Background: My major goal for an online office suite is to be able to take some nicely formated notes. And from time to time I need a simple spreadsheet. Nothing fancy. I hardly print documents, and if I do so, it is only for me. The formatting does not need to be perfect. Ease of use is much more important for me.

The following text is highly opinionated.


# Where Google is better

In o365 I click on "OneDrive", then the URL is "sharepoint.com". If I click on "Excel" the URL is "office.com". Not a big problem. But that's not nice.

In o365 (Word) I write "related_name ..." and Word thinks it is super smart and changes this to "Related_name". No, I don't want this smartness. I want this word to be lower-case.

In o365 (Word) the opions to change the font is easy to see. This has the draw-back that is less likely that I will use the right way: Define a line as "heading" or "title". I prefer to change the meaning of a text (like "Heading 1").

In Google Drive recently used files are visible at the top. I like this.

In o365 (OneDrive) when I am looking at the list of recently used files, then I am not able to add a new file.

In o365 (Word) opening a hyperlink is less intuitive. In Google Workspace I get a small popup window showing me two options: edit the link, open the link.

In o365 (general) there are much more lines and characters on the screen compared to the corresponding screens in Google Workspace. I think Google had one big goal: Reduce cognitive load. I think Microsoft had a different goal. Maybe "Make all features of our native desktop applications avaiable via the browser". But my background is different. I don't need all these features which the desktop version of MS-Word has. I prefer simple to fancy GUIs.

In o365 (Word) the screen is flickering during the first seconds. The [Cumulative Layout Shift](https://web.dev/cls-web-tooling/) could be improved.

Office 365 is usable, but if I could choose, I would use the easier to use solution from Google.

In o365: I am looking at an appointment which is linked to a video-call. I click the link, and get an annoying popup which asks me if I want to open the video call in the browser or in the native GUI. I prefer the google way: web browser only. The browser is my new desktop. I don't like native GUIs.

In "Word for web" I found no way to disable the spell checking. My doc contained a lot of strings which are in no dictionary. I wanted to disable all these red lines. Even my favorite search engine did not help. With Google Docs, that's easy. I found the way to disable it immediately.

In o365: I created a word document, but then realized that I don't need this. I want to delete the file. I don't find an option to delete the file.

In o365 VideoCall: I am in a Teams videocall. I want to invite someone. I copy+paste my URL. But this does not work. You need to go to the people-icon and then create a hyperlink for sharing. Grrrr. Copy+Pasting the URL of a Google Meet videocall works fine.

In o365 I see file extensions like ".docx". This looks ugly, and provides no benefit, since the icon already signals that this is a word document.

## Blur background in Video-Call

In Google Meet videocalls I can blur my background. This does not work for me (Ubuntu Linux) in o365.

## Calendar: Time not visible

In Google Calendar I see the HOUR:MINUTE an appointment starts. I like this.![image](https://user-images.githubusercontent.com/414336/145541079-501e13fd-1ced-4a9e-80cb-b7f27048d934.png)


In o365 I don't see this. I use the view where I can see monday-sunday. The time is visible left to the column of monday. This means it is hard to see the exact time on entries which are at the end of the week:
![image](https://user-images.githubusercontent.com/414336/145540977-61985b0c-447e-47a7-befd-b64766233c52.png)

## Calendar: Current day of the week easier to see

If you look at one week in Google calendar (via a desktop browser), the current day is highlighted via a big blue circle around the current day of the month. This is intuitive. MS-365 uses a blue line to highlight the current day. I prefer the solution of google, since it is more visual concise.

## Calendar: Update event without sending a mail.

I could not find a way to update an event without sending a mail.

I just want to add an URL to the description to the event, so that I have it, during
the meeting. The other participants don't need to have a look at the even before the event.

This is possible with Google calendar, but not with o365.

## Calendar: Accept invite, default is "send mail"

In o365: If I accept an invite via the calendar, then o365 has the default to send an email. I don't want to send an email. This
means I need to disable the "send email" flag every time. I found no way to change the default to "don't send an email".

![image](https://user-images.githubusercontent.com/414336/145776326-3bb53913-d404-43ef-a3f5-7d2896efa9f6.png)

# Writing an Email: one TAB to get from "To" to "Subject"

If I write an email in Gmail I enter the "to" field, then I press TAB and then I can write the subject.

In o365 I need to press TAB four times to get to the subject.

I prefer the Gmail solution: one TAB.

# Multiple URLs for same Online Office Doc. 

Grrr the same document has several URLs in Microsoft. This is annoying, since the autocomplate in the browser's
addressbar shows the same doc several times:

![image](https://user-images.githubusercontent.com/414336/149491469-49fca8a4-397c-4970-9ece-cc6da3595e89.png)

# Microsoft Teams Client for Linux: 300% CPU (VideoCall)

The Microsoft Teams client on Linux eats a lot of CPU. The fan is constantly running which is grrr.

The video calls in Google (in Chromium) need much less resources.

# Native Teams Client consumes CPU, altough I do nothing

I rebooted my machine two days ago. Since then I have not used the native teams client once.

Via the linux command `top` and then "T" I can see which process used the most CPU. There are several
teams processes on the top of this list.

Now I know why my laptop battery gets empty so soon.

This CPU usage is much to much. This burns the planet, wastes energy and money.

Google Workspace has no native client, which means that the solution from Google does not waste resources.

# Snooze Mails

There is a hany feature: [snooze mails until later](https://support.google.com/mail/answer/7622010?hl=en).

ms365 has the same feature. Except, it does not work, at least not always. Often when I snooze an email in ms365,
the mail which I want to reappear in two weeks, reappears in one minute.

# Mail to myself arrives fast with Google

Sometimes I write a mail to myself, just to use the snooze feature immediately afterwords.

A mail to myself arrives much faster with Gmail.

# Google wants my Feedback

It is straight forware to send a feedback message to Google if something does not work as expected. In Gmail it is a "question-mark in a circle icon"
and in Google docs it is via the menu item "help".

I have not seen something like this in MS o365. I would like to tell Microsoft that the resubmit-feature of emails is broken since some days. I resubmit an email to next week, and five minutes later the email is in my inbox again. This worked in the past, but since some days it is broken. I would like to tell MS this, but they don't provide an easy way to send feedback.

# Anonymous Login does not work since I left the company

I left the company which uses ms365 three months ago. I have only my personal (free) ms365 account.

Now I receive an invite to a video call, and this company uses ms365. If I click on the link, the login page of Microsoft
shows the old email address of my former employer. I tried several minutes to log-in with my personal account, but it does not work. My college how has never had a ms365 account can join the call easily.

I get: 

> AADSTS50020: User account 'me@examplecom' from identity provider 'live.com' does not exist in tenant 'old employer' and cannot access the application 
> '5e3ce6c0-2b1f-4285-8d4b-75ee78787346'(Microsoft Teams Web Client) in that tenant. 
> The account needs to be added as an external user in the tenant first. 
> Sign out and sign in again with a different Azure Active Directory user account.

Of course I am not able to "Sign out and sign in", since I don't work for the former company... Grrr.

I solved it by using an incognito tab in chrome. This worked out of the box. But that's just a work-around for the strange bugs of Microsoft.

# Where Microsoft is better

Microsoft is better at reading/writing their docx format. But I don't need this feature.

You can copy images from a online word document. In Google docs, you can't copy an image and paste it into an other application. At least not in a straight forward way. There is a work-around: You need to export the image to google-notes (via right-click). In google-notes you can copy the image.

# Why Microsoft?

Don't ask me why so many companies (at least here in Germany) choose Microsoft-365 without looking at Google-Workplace.


# Related

* [Güttli working-out-loud](https://github.com/guettli/wol)
