# Petful FIFO - Server

## Live App:

https://tucker-petful-client.vercel.app/

## Summary

This project was created with the intent of pairing a pet with a new home. Petful FIFO works in a First in First out basis and matches prospective owners with the cat or dog that has been in the shelter longest and is next in line. By adding your name, you will be added to the list of people in line, and will be allowed to choose either a cat or dog to adopt when you reach the front of the line.

## Endpoints

#### /api/cats

- This endpoint returns a list of cats available for adoption

#### /api/dogs

- This endpoint returns a list of people available for adoption

#### /api/people

- This endpoint returns a list of people who are in the queue

## Have a look :)

<img src="https://user-images.githubusercontent.com/72029209/110018572-6b106380-7cf5-11eb-8013-1ab4d27401d8.jpg" width="200" />
<img src="https://user-images.githubusercontent.com/72029209/110018573-6ba8fa00-7cf5-11eb-8a54-dac5283a6634.jpg" width="200" />
<img src="https://user-images.githubusercontent.com/72029209/110018576-6c419080-7cf5-11eb-9e54-1a8e7b4f09f3.jpg" width="200" />

### Server Repo:

https://github.com/Tucker-Gilligan/petful-server

### Client Repo:

https://github.com/Tucker-Gilligan/petful-client

## Tech Stacks Used

### Backend

- Express for handling API requests
- NodeJS for interacting with the file system
- Mocha, Chai, Supertest for endpoints testing
- Heroku for deployment

### Front End (Client)

- ReactJS
- react-router-dom for routing and in-app navigation
- CSS (vanilla CSS)
- Babel
- Webpack
- Vercel for deployment
- Jest for testing
