# FrontEnd-Interview-Data

## Setup instructions:

1. Run the following command: `npm ci` to install all required packages.
2. Run the following command to start the mockoon server:
   `npx mockoon-cli start --data ./paylink_interview.json`

This will start a mocked server running on your local machine - that you can reach via localhost:3000.

##### Endpoint Available:

With the mocked server running - there is one endpoint available to you.
`GET http://localhost:3000/user/:id`

With an id parameter of 1 - this endpoint will return the following data:
`{
    "id": 1,
    "name": "John Doe",
    "socialMediaHandle": "@johndoe",
    "profileImgSrc": "https://images.unsplash.com/photo-1529665253569-6d01c0eaf7b6?q=80&w=2585&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D",
    "bio": "I'm a software engineer who loves to code and build things.",
    "location": "Grantham, UK",
    "website": "https://johndoe.com"
}`

With an id parameter of 2 this endpoint will return the following data:
`{
    "id": 2,
    "name": "Jane Smith",
    "socialMediaHandle": "@janesmith",
    "profileImgSrc": "https://images.unsplash.com/photo-1483884105135-c06ea81a7a80?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D",
    "bio": "I'm a graphic designer.",
    "location": "London, UK",
    "website": "https://janesmith.com"
}`

If you feel uncomfortable using mockoon as a mocked server - please feel free to use this JSON data however you see best to meet the brief criteria.

## Brief:

_We have created this brief to help us understand your current level of understanding. If you feel as if you have a portfolio that will demonstrate this better, please feel free to send us a Github link to this repository as a submission piece instead._

- Please create a new Angular (v16 or above) application.
- Within this application, please setup a user detail route using a userId as a parameter
- Please create the provided user profile card design, using the JSON data provided.
- Changing the userId in the parameter of this route, should render a different users information.
- Using Jest, please add some code coverage for your implementation, including a unit test for the http methods you have used.

_Please feel free to use any additional third party framework such as Bootrap, Angular Material or Tailwind to support building this design._

##### Bonus:

- Implement a light mode & dark mode toggle.
