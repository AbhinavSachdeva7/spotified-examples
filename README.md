# spotified-examples

The Node.js and React examples of [Spotified](https://github.com/Abdullah-Malik/spotified)

### Running the Node.js Example

To run the Node.js example:

1. Download Spotified.
2. Navigate to the `node-example/` directory.
3. Create a `.env` file in this directory with your Spotify API credentials:
   ```
   client_id=your_client_id
   client_secret=your_client_secret
   ```
4. Run `npm build` to build the project.
5. Run `npm run start` to start the example.

### Running the React Example

To run the React example:

1. Download Spotified.
2. Navigate to the `react-example/` directory.
3. Create a `.env` file in this directory with your Spotify API client ID:
   ```
   REACT_APP_SPOTIFY_CLIENT_ID=your_client_id
   ```
4. Run `npm start` to start the React development server.
5. The app will run on `localhost:3000`.

Make sure you have added the appropriate callback URL (`http://localhost:3000/callback`) to your Spotify Developer Dashboard for the React example to work correctly.
