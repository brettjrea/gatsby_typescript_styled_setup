# Gatsby_Typescript_Styled_Components

## Prerequisites:

* [Install NVM](https://github.com/brettjrea/Debian_Install_NVM)

---

## Commands:

```
sudo apt install git
npm install -g typescript
npm install -g gatsby-cli
gatsby new my-frontend https://github.com/brettjrea/gatsby_typescript_styled_setup
cd my-frontend
npm install styled-components gatsby-plugin-styled-components babel-plugin-styled-components
npm i --save-dev @types/styled-components
npm install --save gatsby-plugin-react-helmet react-helmet
echo "14.16.0" > .nvmrc
npm run develop
```

*The above command used echo to set this apps node version in a .nvmrc file so you need to run the app with NPM instead of yarn with the following command.*

```

```

*Quickly start after a shutdown or reboot.*

```
cd my-frontend
npm run develop
```

---

You might now want to [install Theia](https://github.com/brettjrea/Debian_Theia_IDE_Patched) a browser based IDE built on Typescript.
