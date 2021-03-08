# Gatsby_Typescript_Styled_Components

```
sudo apt update -y && sudo apt upgrade -y && sudo apt autoremove -y
```

```
sudo apt install curl git
```

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```

```
nvm install --lts
```

```
npm install -g typescript
```

```
npm install -g gatsby-cli
```

```
gatsby new my-frontend https://github.com/brettjrea/gatsby_typescript_styled_setup
```

```
cd my-frontend
```

```
npm install styled-components gatsby-plugin-styled-components babel-plugin-styled-components
npm i --save-dev @types/styled-components
```

```
npm install --save gatsby-plugin-react-helmet react-helmet
```

```
gatsby develop
```

*If you want to run other versions of Node you can set this apps version in a .nvmrc file with the following command.*
```
echo "14.16.0" > .nvmrc
```

*For this app gatsby develop will still use npm and use the set version.*

*Quickly start after a shutdown or reboot.*

```
cd my-frontend
gatsby develop
```
