{% include "/includes/header.md" %}

# Mock Interview

## How to Prepare

1. Online branding must be complete
   1. Github homepage (`<username>.github.io`)
      1. Can either be custom homepage or generated HTML resume
   1. Hosted PDF Resume

2. Take home project:
   1. Build an app that uses the [Hacker News API](https://github.com/HackerNews/API) that shows the top stories with a title and link
   2. You can use our CORS-proxy service to get around CORS issues
      1. `https://ni7gssdy8d.execute-api.us-west-1.amazonaws.com/latest/?url=`
         1. eg: https://ni7gssdy8d.execute-api.us-west-1.amazonaws.com/latest/?url=https://hacker-news.firebaseio.com/v0/topstories.json?print=pretty
   3. This is meant to be a timed project (two days). Focus on finishing features asked before adding new
      1. Display a simple list of links and title names
      2. Add a quick CSS framework to make it look nice
      3. IF YOU HAVE TIME! Add some flare like comment counts, rankings, whatever
   4. [Advanced Example for inspiration](https://hack.ernews.info/stories/top)

## What to expect in the interview

Interviewer Might:

1. Print out resume from an online link to a PDF
2. Ask about your side project
   * Quick Demo
   * What was the stack?
   * What was the hardest part?
   * What's your next feature? How will you attack it?
3. Ask a couple code trivia questions
4. Ask for a high level explanation of a full stack web app
5. Whiteboard problem

{% include "/includes/footer.md" %}