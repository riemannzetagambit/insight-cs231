# insight-cs231
Repository for working through Stanford's CS 231n course material

## virtualenv setup
I've put a ve.req file in this repo that has all the packages I've installed in my virtual
environment I set up for this work. To use it:

1. Set up a virtual environment for this work<br>
`virtualenv -p python2.7 .ve/`
2. Activate the virtualenv<br>
`source .ve/bin/activate`
3. Install all the packages in the .req file<br>
`pip install -r ve.req`<br>
or alternatively, a more brute force way that won't trip on bad dependencies<br>
`while read package; do pip install --upgrade $package; done < ve.req`<br>
(and run that command multiple times until no dependency issues show up).

It would be wise to keep a list of duties here for upcoming meeting. I'll start by copying over
notes from Slack.

--dstone

# Agenda
## June 14, 2017
1. David will present lecture 3
2. Jared will present lecture 4 
3. Joos will present lecture 5
4. Rhee will present lecture 6

15 minutes each, present salient talking points. You should read/watch (google ‘internet archive
stanford cs231n’) lectures beforehand

Assignment #1 should be done by then; put your code for the assignment in the repo that David is
creating. @sheareraj and @ahsan send me your github handles
## June 28, 2017
