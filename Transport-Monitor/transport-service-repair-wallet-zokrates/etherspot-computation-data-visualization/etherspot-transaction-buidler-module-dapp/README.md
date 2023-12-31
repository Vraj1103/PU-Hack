
# Account Abstraction with Etherspot Transaction Builder

Account Abstraction Plugins for Transport DAO enables customization of verification logic via Etherspot Transaction builder with a rule/logic setting, tabulation, organization, visualization tool namely SocialCalc spreadsheet. This allows users to set up rules which their account has to abide by when executing transactions while being able to reconfigure them in the future. The process improves account security by restricting permissions certain keys have while remaining adaptable to the user's changing needs. Implementation areas of Account Abstraction plugins in Transport DAO using EtherSpot Transaction Builder, Socialcalc:

- Enforcing a spending limit for vital transport assets based on the key used for the transaction.

- Restricting interaction with a certain citizen wallet or DAO dApp to a specific key.

- Defining session keys, which are allowed to initiate service or repair transactions for only a limited period of time.


### Three different types of transactions:
#### 1. Swap (Same Chain)
#### 2. Swap (Cross-Chain)
#### 3. Send


## IMPORTANT 📢 

The implementation of the transactions has been carried out by using the [BUILDer Component](https://www.npmjs.com/package/@etherspot/react-transaction-buidler) 


## Theme Change
If you wish to change the theme of your builder application, you can do that by passing the theme props **themeOverride** props to the component.
an example of the themeOverride prop is given below

```
let theme = {
      color: {
        background: {
          main: "#221f33",
          topMenu: "#443d66",
          topMenuButton: "#ff884d",
          card: "#2b2640",
          button: "#ff884d",
          closeButton: "#ff884d",
          selectInputToggleButton: "#ff884d",
          selectInput: "#443d66",
          selectInputExpanded: "#1a1726",
          selectInputImagePlaceholder: "#443d66",
          textInput: "#1a1726",
          switchInput: "#1a1726",
          switchInputActiveTab: "#443d66",
          switchInputInactiveTab: "transparent",
          pill: "#2b2640",
          checkboxInputInactive: "#665c99",
          dropdownHoverColor: "#443d66",
          selectInputExpandedHover: "#443d66",
        },
        text: {
          selectInput: "#ffeee6",
          selectInputOption: "#ffeee6",
          selectInputOptionSecondary: "#ffeee6",
          searchInput: "#998ae6",
          searchInputSecondary: "#998ae6",
          outerLabel: "#998ae6",
          innerLabel: "#998ae6",
          topMenu: "#998ae6",
          main: "#ffeee6",
          topBar: "#998ae6",
          buttonSecondary: "#998ae6",
          card: "#ffeee6",
          cardTitle: "#ffeee6",
          button: "#fff",
          errorMessage: "#ff4d6a",
          textInput: "#ffeee6",
          textInputSecondary: "#ffeee6",
          switchInputActiveTab: "#ffeee6",
          switchInputInactiveTab: "#bbb8cc",
          selectInputImagePlaceholder: "#ffeee6",
          cardDisabled: "#605e5e",
          pill: "#bbb8cc",
          pillValue: "#ffeee6",
        },
      },
    }
```
You can pass the above ☝️ theme to the **themeOverride** prop to customize the theme and feel free to put your own colors 😁.
An implementation of the same can be found in the [ThemeOverride](https://github.com/etherspot/etherspot-react-transaction-buidler/blob/master/example/src/pages/ThemeOverride.tsx) page


## Available Scripts

In the project directory, add a file called ".env"
To this file add this line: REACT_APP_WEB3AUTH_CLIENT_ID = "fake_id"
Replace fake_id with a real client ID from https://dashboard.web3auth.io/home/web3auth if you want social logins to work. Otherwise continue without it and login with a keybased wallet.

Then start your dapp using this:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
