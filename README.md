# CRA with Storybook with preset-create-react-app

This project was bootstrapped with
[Create React App](https://github.com/facebook/create-react-app).

## How was Storybook initialized

Ran sb init without any options and let it detect CRA:

```shell
npx sb init
```

The added the following overrides in `package.json`:

```json
{
  "overrides": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-refresh": "0.13.0"
  }
}
```

## Running Storybook

```shell
npm run storybook
```

## Running the app

```shell
npm start
```

