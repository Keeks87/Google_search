# Specification

Your website must meet the following requirements:

- Your website should have at least three pages: one for regular Google Search (which must be called index.html), one for Google Image Search, and one for Google Advanced Search.
  - On the Google Search page, there should be links in the upper-right of the page to go to Image Search or Advanced Search. On each of the other two pages, there should be a link in the upper-right to go back to Google Search.

- On the Google Search page, the user should be able to type in a query, click “Google Search”, and be taken to the Google search results for that page.
  - Like Google’s own, your search bar should be centred with rounded corners. The search button should also be centred, and should be beneath the search bar.

- On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page.

- On the Google Advanced Search page, the user should be able to provide input for the following four fields (taken from Google’s own advanced search options)
  - Find pages with… “all these words:”
  - Find pages with… “this exact word or phrase:”
  - Find pages with… “any of these words:”
  - Find pages with… “none of these words:”

- Like Google’s own Advanced Search page, the four options should be stacked vertically, and all of the text fields should be left aligned.
  - Consistent with Google’s own CSS, the “Advanced Search” button should be blue with white text.
  - When the “Advanced Search” button is clicked, the user should be taken to the search results page for their given query.

- Add an “I’m Feeling Lucky” button to the main Google Search page. Consistent with Google’s own behaviour, clicking this link should take users directly to the first Google search result for the query, bypassing the normal results page.
  - You may encounter a redirect notice when using the “I’m Feeling Lucky” button. Not to worry! This is an expected consequence of a security feature implemented by Google.

- The CSS you write should resemble Google’s own aesthetics.

## Hints

- To determine what the parameter names should be, you’re welcome to experiment with making Google searches, and looking at the resulting URL. It may also be helpful to open the “Network” inspector (accessible in Google Chrome by choosing View -> Developer -> Developer Tools) to view details about requests your browser makes to Google.
  - Any <input> element (whether its type is text, submit, number, or something else entirely) can have name and value attributes that will become GET parameters when a form is submitted.
  - You may also find it helpful to look at Google’s own HTML to answer these questions. In most browsers, you can control-click or right-click on a page and choose “View Page Source” to view the page’s underlying HTML.

- To include an input field in a form that users cannot see or modify, you can use a “hidden” input field.

## How to Submit

1. Visit this link, log in with your GitHub account, and click Authorize cs50. Then, check the box indicating that you’d like to grant course staff access to your submissions, and click Join course.

2. Install Git and, optionally, install submit50.

    When you submit your project, the contents of your web50/projects/2020/x/search branch should match the file structure of the unzipped distribution code as originally received. That is to say, your files should not be nested inside of any other directories of your own creation (search or project0, for example). Your branch should also not contain any code from any other projects, only this one. Failure to adhere to this file structure will likely result in your submission being rejected.

    By way of example, for this project that means that if the grading staff visits <https://github.com/me50/USERNAME/blob/web50/projects/2020/x/search/index.html> (where USERNAME is your own GitHub username as provided in the form, below) your submission for index.html for this project should be what appears. If it doesn’t, reorganize your repository as needed to match this paradigm.

3. If you’ve installed submit50, execute
submit50 web50/projects/2020/x/search
Otherwise, using Git, push your work to <https://github.com/me50/USERNAME.git>, where USERNAME is your GitHub username, on a branch called web50/projects/2020/x/search.

4. Record a screen cast not to exceed 5 minutes in length (and not uploaded more than one month prior to your submission of this project), in which you demonstrate your project’s functionality. Your URL bar must remain visible throughout your demonstration of the project. Be certain that every element of the specification, above, is demonstrated in your video. There’s no need to show your code in this video, just your application in action; we’ll review your code on GitHub. Upload that video to YouTube (as unlisted or public, but not private) or somewhere else. In your video’s description, you must timestamp where your video demonstrates each of the seven (7) elements of the specification. This is not optional, videos without timestamps in their description will be automatically rejected.

5. Submit this form.

You can then go to <https://cs50.me/cs50w> to view your current progress!
