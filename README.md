# quercus-bots

This is my repository for the bots that I have developed for Quercus (Canvas for the University of Toronto), based on RESTful API

## Bot-1: Batch grade with comment uploader (importing comments from a file)

Canvas does not have the capability of batch uploading assignment comments. This is an open issue for instructors with about [400 instructors](https://community.canvaslms.com/ideas/4049-import-grade-comments) requesting this feature. When there is a large number of students, instructors have to post comments separately for each student, which is time consuming.

This bot allows instructors/TAs to simultinously submit the grade and comment of each assignment submission automatically from an Excel/csv file. The code can be easily modified for other needs. 

This bot uses the official Canvas API, therefore, it should be compatible with any university LMS that uses Canvas.
