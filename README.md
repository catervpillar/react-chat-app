# react-chat-app

A Facebook-Messenger-like chat app made with React and Fastify (Node.js) to try out the [Stream](https://getstream.io/) API.

## Usage

### Server

Navigate to the `/server` folder.\
Install dependencies by running the command:

```
npm install
```

Create a `.env` file with the following:

```
PORT=your-port-number(example: 3000)
CLIENT_URL=your-client-url(example: http://localhost:5173)
STREAM_API_KEY=your-stream-api-key
STREAM_PRIVATE_API_KEY=your-stream-secret-key
```

Start the server by running the command:

```
npm run dev
```

### Client

Navigate to the `/client` folder.\
Install dependencies by running the command:

```
npm install
```

Create a `.env` file with the following:

```
VITE_SERVER_URL=your-server-url(example: http://localhost:3000)
VITE_STREAM_API_KEY=your-stream-api-key
```

Start the client by running the command:

```
npm run dev
```
