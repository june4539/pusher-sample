# Realtime Comments Widget (Next.js & Pusher)


This project contains the source code for a very simple realtime comments widget application with sentiment analysis. With sentiment analysis, we are able to detect the mood of a person based on the words they use in their comments. 

[View tutorial](https://pusher.com/tutorials/comments-sentiment-analysis-nextjs)

Here is a screenshot of the application.

![App Screenshot](https://i.imgur.com/DtLF0GH.png)


```sh
npm install
```

or using `yarn`

```sh
yarn add
```

3. **Create a `.env` file** in the root of the new directory with the following content.

```ini
# Pusher App Credentials

PUSHER_APP_ID=YOUR_APP_ID
PUSHER_APP_KEY=YOUR_APP_KEY
PUSHER_APP_SECRET=YOUR_APP_SECRET
PUSHER_APP_CLUSTER=YOUR_APP_CLUSTER
```

4. **Start the app** by running the following command. The app will runs on port 3000 except that port is already in use.

```sh
npm run dev
```

For `production`

```sh
npm start
```
