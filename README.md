
### Exercise

1. In App.js you'll find a list of countries
   and their description (as an array)
   Build a sit with the following structure:

  - A hompage (/home) that contains a list
    of all countries and a link to the page
    of the respective country (/country/:index)
  - Use (countries.map) to generate the links
  - A country page should render the name
    of the country as an h1 and the description
    as a paragraph.
    Get the array index of the country using
    the useParams() hook
  - (BONUS) Add Prev/Next links that point to
    the previous and next country page,
    If at the beginning or the end of the Array,
    circle around to the other end.

2. Create an alternative link on the homepage
   next to the normal link, pointing to
   (/country/byName/:name).
   Create a route that will not collide
   with the (/country/:index) route.


### `npm install`

Will install the required nodeJS modules. **This is nessecary!**

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

