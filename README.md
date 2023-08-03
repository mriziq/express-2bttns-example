# Read Me

This is a basic, example implementation of Express and 2bttns. Play a food preference sorting game and view the results.

## Usage

To run this app, you'll need to run both the 2bttns console and the node server used to interact with the console. You can use the basic HTML file to interface.

1. Run 2bttns 

```bash
cd 2bttns
```

```bash
npm i
npm run dev
```

2. Run Node Server for interacting with 2bttns on client side

Make sure you have these `.env` variables where your node server is if not successfully pulled from github. 

```
TWOBTTNS_BASE_URL="http://localhost:3001" 
TWOBTTNS_APP_ID="example-app" 
TWOBTTNS_APP_SECRET="example-secret-value"
```

```bash
cd web-app
```

```bash
npm i
node server.js
```

3. Open the index.html page in your browser

4. Play a game (currently set to food preference ranking)

5. Go back to index.html and click Get Results to view your scores. Play more rounds to see how your rankings change.


## Configuring a New Game in 2bttns

1. Get other example data using the @2bttns/object CLI.

```bash
# anywhere
npx @2bttns/objects
```

2. Open 2bttns Console at http://localhost:3001/

3. Log in with admin credentials (u: admin, pwd: admin)

4. Upload & Tag your objects (Learn how [here](https://www.2bttns.com/docs/📕%20Console%20Guide/Objects/intro))

5. Create a game (Learn how [here](https://www.2bttns.com/docs/📕%20Console%20Guide/Games/create-games))