# Dental Product Orders

This tool will offer a GUI that allows the user to create dental equipment orders.
The user will choose various products from drop down menus, etc, which are stored in a database.

## Tooling

- HTML
- CSS
- JavaScript
- AWS
  - API Gateway
  - RDS database
  - S3 for webfiles
  - Lambda
  - Cost Analysis
  - Cognito
  - Cloudfront
  - WAF
  - R53
  - Certificate Auth

## Usage

1. Create a user account if user account does not yet exist.
2. Log in to user account.
3. Purchase a subscription.
4. Create a new client profile.
   - Name the new profile, for example, after the dentist for whom the order is for.
5. Navigate through the dropdowns to add the desired dental equipment to the client's profile.
6. Save the client profile.
7. (Possibly) Print out the items in the client profile.
8. (In future) Share a template containing the client profile info via email. This could be a confirmation email of the items purchased sent to the client?



## ToDos
1. ~~Create basic web interface~~
2. Create login structure
3. Build out database
4. Set up API Gateway
5. Items in dropdowns should reflect items stored in database
6. Print out any output? Print to PDF?
7. Create subscription structure