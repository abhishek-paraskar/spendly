Add two links to the footer in @templates/base.html :

- "Terms and Conditions"
- "Privacy Policy"

Both should be plain text links, no styling needed for now.
href should be pointed to "#" as the pages where it should be redirected does not exists yet.

Do not modify anything else in the page.



#New Prompt for Terms and Conditions
Create a "Terms and Conditions" page for this project.
1. Add a new route in [app.py](http://app.py/):
GET /terms -> renders templates/terms.html

2. Create templates/terms.html with generic terms and conditions content appropriate for a personal expense applicaiton.
Include sections like - Acceptance of terms, Use of Services, User Data, Limitations of Liability and Changes in Terms.
Extend base.html if it exists, otherwise match the style of landing.html

3. In @template/landing.html, update the "Terms and Conditions" link href to redirect to "/terms" route.



#New Prompt for Privacy
Create a "Privacy Policy" page for this project.
1. Add a new route in [app.py](http://app.py/):
GET /privacy -> renders templates/privacy.html

2. Create templates/privacy.html with generic privacy policy content appropriate for a personal expense applicaiton.
Include sections like - Data we collect, How we use your data, Data storage, Third party services and Contact Us.
Extend base.html if it exists, otherwise match the style of landing.html

3. In @template/landing.html, update the "Privacy Policy" link href to redirect to "/privacy" route.