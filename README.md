
# GraphQL Hello World

Hello World! example of GraphQL

## Setup

-  Go into server directory

```
cd server
```

-  Install packages

```
npm install
```

-  Run app

```
node server.js
```

Verify GraphiQL is running by going to displayed url which should be http://localhost:9000.

## Run

### GraphiQL

Inside of GraphiQL make sure **Explorer** is selected on the left hand menu.

Run the following querry inside of the **Operation** section.

```
query  {
  greeting
}
```

You should see the following result if successful.

```
{
  "data": {
    "greeting":  "Hello World!"
  }
}
```

### index.html

Open the index.html file located inside the client folder to load it in the browser.

As long as it displays **Hello World!** after the "*The server says:*" text the GraphQL call from the client side worked.
