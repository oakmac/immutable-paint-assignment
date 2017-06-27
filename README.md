# Immutable Paint Application

Create a [Paint] application using [React] backed with an [persistent data
structure].

## Required Features

- Built using [React]
- Use [mori] or [Immutable] for the persistent data structure.
- You can use any state management approach you want for this application, but
  you might find that using a single source of state or something like [Redux]
  makes things easier.
- The drawing area should support 500,000 pixels **at a minimum**.
- Pixels should support 256 colors (ie: [8-bit]) **at a minimum**.
- There should be an "infinite undo" feature. Any action the user takes should
  be able to "undo".
- The user should be able to save their drawing to [localStorage] to be recalled
  later.
- When a drawing is recovered from a saved state, the last 20 operations of
  "undo" should be remembered (you do not have to remember "infinite undo")
- There should be a adjustable-pixel brush, a circle tool, a rectangle tool, and
  a bucket tool **at a minimum**. Feel free to add other fun brushes as time allows.

### Bonus Features

- Save user's drawings to an online database like [Firebase], [Amazon S3], or
  other service.
  - Note: this might be a good time to invest in a shared hosting account
    service like [a2hosting] or similar.
- Support loading a user's drawing via URL. ie: `my-paint-app.com/3887` or
  `my-paint-app.com/index.html?id=8991`, etc

[Paint]:https://en.wikipedia.org/wiki/Microsoft_Paint
[persistent data structure]:https://en.wikipedia.org/wiki/Persistent_data_structure
[React]:https://facebook.github.io/react/
[functional, stateless components]:https://facebook.github.io/react/docs/components-and-props.html#props-are-read-only
[8-bit]:https://en.wikipedia.org/wiki/Color_depth
[localStorage]:https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
[mori]:http://swannodette.github.io/mori/
[Immutable]:https://facebook.github.io/immutable-js/
[Firebase]:https://firebase.google.com/
[Amazon S3]:https://aws.amazon.com/s3/
[a2hosting]:https://www.a2hosting.com/
[Redux]:http://redux.js.org/
