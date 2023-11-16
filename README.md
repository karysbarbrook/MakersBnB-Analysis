# MakersBnB Analysis

## Headline specifications
Any signed-up user can list a new space.
- Users should be able to name their space, provide a short description of the space, and a price per night.
- Users should be able to offer a range of dates where their space is available.
- Users can list multiple spaces.
- Any signed- up user can request to hire any space for one night, and this should be approved by the user that owns that space.
- Nights for which a space has already been booked should not be available for users to book that space.
- Until a user has confirmed a booking request, that space can still be booked for that night.

## Potential test areas
- Users require all fields to be input to sign up
- Users must use valid email address
- Password and password confirmation fields must match
- Incorrect or unaccepted entries should highlight specific field and provide an instruction how to resolve the issue
- Users should be able to ‘click’ About link and be taken to About page
- Users should be able to ‘click’ ‘Log- in’ link and be taken to Log- in page
- User should be able to move between (tab between) elements and form fields without the use of a mouse or trackpad
- User should receive confirmation after submission that there sign up has been successful-  in this case redirected to the ‘Log- in’ Page
- Keyboard focus should provide TWO clear visual focus markers
- Fields contain placeholders/ or not 
- Users can list multiple spaces:
- Can users see listed spaces?
- Can users see an add space that is interactable
- Is there a limit on number of spaces
- Are they all on one page?
- Is the user able to see ‘Book a space’ without being logged in?
- Do the spaces Scroll? Can we refresh
- Users should be able to name their space, provide a short description of the space, and a price per night:
  - Are there valid and invalid space names?
  - Is there a word limit on the description field?
  - Is there a minimum and/or maximum price per night?
  - Can a user see the names, descriptions, and ppn of other spaces?
  - Can users view images -  provide alt text for all images
  - Are the space details updated immediately?
- Users should be able to offer a range of dates where their space is available:
  - Is there a limit on available dates?
  - Are the date ranges interactable for booking users?
  - What happens if a user tries to book an unavailable date?
  - Users once they’ve signed up can login through the login page with their details.
  - Users can approve requests made to hire their space for a period of time.
  - Only a signed up user should be able to request a space.
  - Nights for which a space has already been booked should not be available for users to book that space.
  - If a user attempts to book a space, but doesn’t have it confirmed by the user who owns that space, another user is allowed to book that space.
## Risks
  ### Security.
- How can we confirm that someone actually has a space? Authentication?
- Logins -  keeping accounts safe, making sure people can’t login with other’s details.
- Potential risk of people not logged in are able to access and book spaces.
- Data breach -  leaked accounts details.
- Someone books a space and doesn’t show up -  lack of contacting space requester. Need ability to contact owner too.
- Double booking.
- No username for log- in. Verification for logged in users 
  ### Bad user experience.
- Bad accessibility.
- No alt text on site.
- Accurate descriptions and no way to confirm legitimacy of space.
- Hard to navigate.
- Slow website.
- Poorly written -  unclear description.
- Inappropriate description and/or photos -  needs to be a filtering system.
- Restrict size and number of photos
- Environmental factors.
## Assumptions and/or questions
- Contact details should be free for users to see for the host of a space.
- User identification method to ensure user is logged in before interacting with spaces.
- Contact/feedback form to report website or User experience problems


## Most Important things we would like to test:
- Password and password confirmation fields must match in order to sign up for an account
- Incorrect or unaccepted entries should highlight both the error and the specific field effected and provide an instruction how to resolve the issue
- Login authentication (What are valid login details and what is invalid?)
- What kind of data can the description field take?
- How much text can the description field take?
- Can users see all spaces and their details?
- Can User access their requests and respond?
- Can users see updated request lists?
- Test double booking
- Can user cancel pre booked requests
- Test that users can only book a space if they are logged in.
- Test that users cannot ‘double book’ a space and the website reflects that.
- Test that users are able to see any requests for their spaces.
- Test that users can see requests they have made.
- Test whether users can access fields and elements without the use of a mouse or trackpad
- Test booked dates against previously booked dates to avoid double booking -  try booking the same space & location from different accounts after a request has been confirmed.

## Planned 90 Minute Exploratory Testing:
- Test that users cannot ‘double book’ a space and the website reflects that:
  - Try booking the same space & location from different accounts after a request has been confirmed.
  - Date picker should reflect unavailable dates when date range is input
  - The booked dates should not be interactable
- Can users see updated request lists?
  - Make requests from multiple accounts and check to see that the requests are reflected in lists.
  - Make identical requests from different accounts and check to see that they are in the request list.
  - Book and confirm a request then, repeat searches from same account/ new account
- Login/signup authentication (What are valid login details and what is invalid?)
  - Password and password confirmation fields must match in order to sign up for an account:
    - Input matching valid passwords
    - Input different valid passwords
    - Input easy to guess passwords
  - Test password and email validity criteria:
    - Input different complexities of passwords
    - Input different kinds of emails
    - Do Passwords contain number of characters/symbols / numbers etc to provide high password security
    - Incorrect or unaccepted entries should highlight both the error and the specific field effected and provide an instruction how to resolve the issue
  - Testing Login functionality:
    - Input valid email and valid password
    - Input invalid email and invalid password
    - Input valid email and invalid password
    - Input invalid email and valid password
    - Does the page allow predictive input
    - Try 10 times
- Navigating the website -  do all buttons and links lead to the correct locations?
  - Are they correctly labelled/correct tags in the html
  - See that clicking the requests page link leads to the request page



