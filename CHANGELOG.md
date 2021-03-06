### Unrelease
### 4.0.3
-  Bug fix. `fetchAFullTopic` should return a promise.

### 4.0.2
- Reduce the action sent while fetchAFullPost
  - Do nothing if the post we want to fetch is fully fetched and is the current selected post

### 4.0.1
- Enable pagination on posts action and reducer

### 4.0.0 
- Move bookmark feature to @twreporter/registration

### 3.0.0
- Create bookmark feature for registration

### 2.1.5
- Add gulpfile
- Update topics actions and reducers
- Update topics action and reducer tests

### 2.1.4
- Remove is_feature:true param in fetchPhotographyPostsOnIndexPage function

### 2.1.3
- Add isFetching in topics and topic reducers

### 2.1.2
- Fetch topics if topics exist but is empty object
- Fix indexpage to fit lint and test

### 2.1.1
- Add isFetching for GET_CONTENT_FOR_INDEX_PAGE

### 2.1.0
- Add process.env.API_HOST, process.env.API_PORT, process.env.API_PROTOCOL and process.env.API_DEFAULT_VERSION
variables for clients to overwrite the api config

### 2.0.1
- store slug in payload if action error occurs

### 2.0.0
- code refactoring, especially change the redux-state-fields data structure

### 1.0.7
- expose formatAPIURL function
- update fetchPhotographyPostsOnIndexPage function. Fetch featured posts.
- Update utils/form-api-url.js. Give toEncode param
