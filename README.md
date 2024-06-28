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

```json
{
  "id": 1,
  "name": "John Doe",
  "socialMediaHandle": "@johndoe",
  "profileImgSrc": "https://assets.embarknext.com/assets/d37c2ffb-dcc6-4513-8b13-3356b01d02d0",
  "bio": "I'm a software engineer who loves to code and build things.",
  "location": "Grantham, UK",
  "website": "https://johndoe.com"
}
```

With an id parameter of 2 this endpoint will return the following data:

```json
{
  "id": 2,
  "name": "Jane Smith",
  "socialMediaHandle": "@janesmith",
  "profileImgSrc": "https://assets.embarknext.com/assets/ac6ca7d9-3049-4155-bceb-5ba9b53d70d9",
  "bio": "I’m a creative graphic designer with over five years of experience specializing in brand identity, print design, and digital media, known for my attention to detail and innovative approach.",
  "location": "London, UK",
  "website": "https://janesmith.com"
}
```

If you feel uncomfortable using mockoon as a mocked server - please feel free to use this JSON data however you see best to meet the brief criteria.

## Brief:

_We have created this brief to help us understand your current level of understanding. If you feel as if you have a portfolio that will demonstrate this better, please feel free to send us a Github link to this repository as a submission piece instead._

As part of our technical assesment - we would like you to create a user detail route that renders a 'profile card'.

Please use any framework you feel comfortable with to meet this assessment criteria. (All of our applications currently use Angular 17)

### High level objectives:

- Create a new application in your chosen framework, that is publically available for us to view via Github.
- Setup a user detail route - that will take a 'userId' as an optional parameter route.
- On page initialisation, please call the provided mock server endpoint to call for a user object, using the route parameter.
- Use the provided data to build the design, please take into consideration mobile responsiveness.
- In changing the userId route parameter from 1 to 2 - this should render a different users information.
- Using Jest - please add code coverage for your implementation,

### Bonus objective:

- Implement a dark mode & light mode toggle to update the styles to an alternative theme.

Please feel free to use any additional third party framework such as:

- Bootstrap 5
- Angular Material
- Tailwind
- Prime NG

(All of our applications currently use Bootstrap 5)

Thank you.
