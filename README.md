## Running the application
 - `npm install` - for getting the required libs  
 - `npm start` - for opening the application in browser
 
 ## About the application

Stateless Functional Component

Given info about profiles, users and movies :

#### profiles  
`const profiles = [
   {
     id: 1,
     userID: '1',
     favoriteMovieID: '1',
   },
   {
     id: 2,
     userID: '2',
     favoriteMovieID: '1',
   },
   {
     id: 3,
     userID: '4',
     favoriteMovieID: '5',
   },
   {
     id: 4,
     userID: '5',
     favoriteMovieID: '2',
   },
   {
     id: 5,
     userID: '3',
     favoriteMovieID: '5',
   },
   {
     id: 6,
     userID: '6',
     favoriteMovieID: '4',
   },
 ];
`


#### users    
const users = {
  1: {
    id: 1,
    name: 'Jane Jones',
    userName: 'coder',
  },
  2: {
    id: 2,
    name: 'Matthew Page',
    userName: 'mpage',
  },
  3: {
    id: 3,
    name: 'Autumn Green',
    userName: 'user123',
  },
  4: {
    id: 3,
    name: 'John Doe',
    userName: 'user123',
  },
  5: {
    id: 5,
    name: 'Lauren Johnson',
    userName: 'user123',
  },
  6: {
    id: 6,
    name: 'Nicholas Lain',
    userName: 'user123',
  },
};


#### movies  
`const movies = {
   1: {
     id: 1,
     name: 'Planet Earth 1',
   },
   2: {
     id: 2,
     name: 'Selma',
   },
   3: {
     id: 3,
     name: 'Million Dollar Baby',
   },
   4: {
     id: 4,
     name: 'Forrest Gump',
   },
   5: {
     id: 5,
     name: 'Get Out',
   },
 };`

Show result as follow:

`[Moview name 1]`   
 Liked by:  
    * `[user name 1]`  
    * `[user name 2]` 
    
`[Moview name 2]`  
 Liked by:  
    * `[user name 21]`  
    * `[user name 22]` 

![ScrenShot](src/img/screenshot.png)