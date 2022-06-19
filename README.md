# CRA with Storybook

This project was bootstrapped with
[Create React App](https://github.com/facebook/create-react-app).

## How was Storybook initialized

Storybook was added using `sb init` without any options. This lets it detect CRA
and add preset-create-react-app and webpack5 builder automatically:

```shell
npx sb init
```

After this I had to add the following overrides to `package.json` to overcome
dependency conflicts:

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
