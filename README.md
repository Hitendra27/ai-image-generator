# OpenAI Image Generator

This is a simple image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.

## screenshots of the OpenAI Image Generator.

<img width="1440" alt="Screenshot 2023-03-30 at 20 38 41" src="https://user-images.githubusercontent.com/73651340/228946737-6a5b163b-3aa7-4a0e-95c5-79020f427ce7.png">
<img width="1440" alt="Screenshot 2023-03-30 at 20 39 06" src="https://user-images.githubusercontent.com/73651340/228946756-72d02e49-20c3-45b2-83e5-34ecc2b8e79b.png">

## Usage

Rename the `example.env` file to `.env`.

Generate an API KEY at [OpenAI](https://beta.openai.com/) and add it to the `.env` file.

Install the dependencies

```bash
npm install
```

Run server

```bash
npm start
```

Visit `http://localhost:5000` in your browser.

The endpoint is at `POST http://localhost:5000/openai/generateimage`.
