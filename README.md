## npm i

## npm start

## APIs Used

In this project, I have utilized the following APIs:

1. **RESTful API**: I have implemented a RESTful API using Express.js framework to handle CRUD operations for managing data.

2. **Redux Toolkit API**: Redux Toolkit is a powerful library that simplifies the process of managing state in a React application. I have used its API to create reducers, actions, and selectors for managing the application's state.

3. **AsyncThunk API**: AsyncThunk is a middleware provided by Redux Toolkit that allows handling asynchronous actions in a Redux store. I have used this API to dispatch asynchronous actions for fetching data from the server.

4. **Axios API**: Axios is a popular JavaScript library used for making HTTP requests. I have used its API to send HTTP requests to the server and handle the responses.

5. **React Router API**: React Router is a library that provides routing capabilities to a React application. I have used its API to define and handle different routes in the application.

These APIs have been instrumental in building a robust and efficient application that interacts with the server, manages state, and handles routing effectively.

## APIS explained

--Used mockapi.io as an endpoint for storing the data.
--Inside userDetail.js, I have used the useEffect hook to fetch the data from the server and store it in the Redux store.
--Inside userDetail.js, I have used the useSelector hook to retrieve the data from the Redux store.
--Inside userDetail.js, I have used the useDispatch hook to dispatch the action for fetching data from the server.
--Inside userDetail.js, I have used the useParams hook to retrieve the id of the user from the URL.
--ive used post method to create data and get method to retrieve data from the server.
--fetch api is fetching data from the endpoint and displaying in all posts
--delete method is used to delete the data from the server
