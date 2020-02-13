# Deployment Notes

## Steps

- create an empty repository on Github
- clone it
- open it in your code editor
- create a default package.json by typing: `npm init -y`
- `npm i express`
- `git status` => `node_modules` shows up on the list.
- `npx gitignore node` to generate `.gitignore` super file
- `npm i -D nodemon` install nodemon as a Dev dependency. Will not be installed during deployment