# Fetch json api
A vanilla javascript alternative to ajax for fetching a json api.

# How to:
ES6
```
import fetchJsonApi from './fetchJsonApi.jsx';

fetchJsonApi('https://api.github.com/users/rishoej/repos', ((response) => {
  console.log(response);
}));
```
