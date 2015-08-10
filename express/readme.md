# Express Challenge - Phase 1 - Setup

In this phase you are asked to setup an Express app.

1. Open the `Express\stackoverflow\stackoverflowChallenge\app.js` file

2. Setup the view engine.
      - `app.set('view engine', 'jade')`;

3. setup the views folder.
    - `app.set('views', path.join(__dirname, 'views'))`;

4. setup the static middleware for serving static resources from the public folder
    - `app.use(express.static(path.join(__dirname, 'public')));`

5. create a new router contaning a route for the root path '/'

6. the route should render the *index* view.
    - `res.render("index")`

7. run the project from the command line (you can run `npm start` in the app folder path) or the IDE 

8. browse to [localhost:3000](http://localhost:3000) and make sure that your are seeing the correct view.

