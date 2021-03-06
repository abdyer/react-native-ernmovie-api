# javascript

react-native-ernmovie-api - JavaScript client for javascript
Top Rated Movies
This SDK is automatically generated by Electrode React Native API generator.
It uses swagger to gernerate bridge code for Swift, Android and React Native.

- API version: 1.0.0
- Package version: 0.0.7

## Installation

### For [Node.js](https://nodejs.org/)

#### npm

To publish the library as a [npm](https://www.npmjs.com/),
please follow the procedure in ["Publishing npm packages"](https://docs.npmjs.com/getting-started/publishing-npm-packages).

Then install it via:

```shell
npm install javascript --save
```

#### git
#
If the library is hosted at a git repository, e.g.
https://github.com/GIT_USER_ID/GIT_REPO_ID
then install it via:

```shell
    npm install GIT_USER_ID/GIT_REPO_ID --save
```

## Getting Started

Please follow the [installation](#installation) instruction and execute the following JS code:

```javascript
import { react-native-ernmovie-api } from 'javascript';

const api = new react-native-ernmovie-api.MoviesApi()

api.getMovieDetail(movieId).then(function(data) {
  console.log('API called successfully. Returned data: ' + data);
}, function(error) {
  console.error(error);
});

```

## Documentation for API Endpoints

All URIs are relative to *https://api.imdb.movies.com/v1*

Class | Method |request type | Description
------------ | ------------- | ------------- | -------------
*react-native-ernmovie-api.MoviesApi* | [**getMovieDetail**](docs/MoviesApi.md#getMovieDetail) | **request** /movieDetails | MovieDetails
*react-native-ernmovie-api.MoviesApi* | [**getTopRatedMovies**](docs/MoviesApi.md#getTopRatedMovies) | **request** /movies | List&lt;Movie&gt;

## Documentation for Models
 - [react-native-ernmovie-api.BirthYear](docs/BirthYear.md)
 - [react-native-ernmovie-api.Movie](docs/Movie.md)
 - [react-native-ernmovie-api.Person](docs/Person.md)
 - [react-native-ernmovie-api.Synopsis](docs/Synopsis.md)

## Documentation for Authorization

 All endpoints do not require authorization.

