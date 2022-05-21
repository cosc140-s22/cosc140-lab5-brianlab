# COSC140 lab 5

## Lab feedback

 * How long did you spend on this lab?

3-4 hours

 * What did you think about it?  What was good?  What could be improved?

I thought it was pretty straightforward. I spent most of my time getting the form to render in the review template but I got it to work eventually. 

## Feedback

N

There's one bug: if you don't fill in anything valid in the review form, you get a server crash.  The fix is to dedent the last two lines in your `createreview` function so that you will just re-render the form.  Right now, you won't render anything because of the structure of the code in that function (and that's what causes the crash).

