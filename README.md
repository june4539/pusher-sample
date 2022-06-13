# Realtime Comments Widget (Next.js & Pusher)


This project contains the source code for a very simple realtime comments widget application with sentiment analysis. With sentiment analysis, we are able to detect the mood of a person based on the words they use in their comments. 

[View tutorial](https://pusher.com/tutorials/comments-sentiment-analysis-nextjs)

Here is a screenshot of the application.

![App Screenshot](https://i.imgur.com/DtLF0GH.png)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

1. **Install Node on your machine**: Ensure that you have **Node** and **npm** or **Yarn** installed on your machine. To install Node and npm on your machine, see the [Node download page](https://nodejs.org/en/download/). If you prefer using [Yarn](https://yarnpkg.com/) as your package manager to using npm, you can [get Yarn here](https://yarnpkg.com/en/docs/install).

2. **Create a Pusher application**: Create a new application on your [Pusher Dashboard](https://dashboard.pusher.com/) to get your app credentials.

### Setup Instructions

1. **Clone the repository** into a new directory on your machine.

2. **Install the dependencies** by running the following command from the new directory.

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

## demo
![image](https://user-images.githubusercontent.com/106511534/173307539-a5ecd5b7-cf7d-4ddd-9bd0-ccb271baec80.png)

