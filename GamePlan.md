# Project Plan & Management

## Goal
This is an AI-powered image recognition tool. Users can log on or sign up to use this tool. The point of having this tool be account-based is that user data will be stored so that they can return to the tool with their information and past uses saved. This account-based capability will be facilitated by AWS. I will use AWS to create user authentication and cloud-based data storage for this tool. Hopefully, by the end of this project I have learned how to integrate AI functionality in a web-based service, gained useful experience with a cloud-computing service (AWS), and improved my front-end development skills with something like React. 

## Flow
1.	A user enters the site
2.	Account page
a.	User logs in – go to 3.
b.	User creates account – go to 4. 
3.	Main Menu
a.	Settings – Settings menu pops up
b.	Create/Choose Topic – all subsequent image uploads will be categorized under this topic
c.	User uploads image – AI will begin processing the image, and then create a textual summary of what it sees
d.	

## Development Plan
<ol>
    <li>Control flow diagram ✅</li>
    <li>Create wireframe to identify features ✅</li>
    <li>Understand how to implement AWS features</li>
    <ul>
        <li>Goal is to understand the order in which development should occur</li>
    </ul>
    <ol>
        <li>Amplify</li>
        <li>Cognito</li>
        <li>Rekognition</li>
        <li>S3</li>
        <li>Lambda</li>
    </ol>
</ol>

## Resources to Use 
> Subject to change
### Languages
- React
- HTML
- CSS

### AWS Features
- Amplify (Web hosting)
- Cognito (Account handling)
- S3 (Image Storage)
- Rekognition via Lambda (Image processing)
- Lambda + API Gateway? (Backend shenanigans)
