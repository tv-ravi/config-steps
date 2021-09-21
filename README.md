ROLIFIQ ACE
Required:
Git (Latest)
Node JS (Latest LTS)
JDK (Latest LTS)
Android Studio  
X Code
Visual Studio Code or WebStorm (With ES lint, Prettier Extensions/Settings - Installed/Enabled)
Environment Setup, follow instructions from official site:

https://reactnative.dev/docs/environment-setup
NPM Packages Global Installation:

npm i -g typescript forcereact eslint yarn prettier
To Install NPM Packages in Project:

yarn
To Install Packages For IOS:

cd ios 
pod install 
To Start Android:

yarn android
To Start IOS:

yarn ios
To Start Server:

yarn start
Each Time Before Committing Code Run Validation:

yarn validate
Naming Convention

Files/Folder Names (Examples)

// Files - (lowerCase)
users.component.tsx
users.style.tsx
user-details.component.tsx
user-details.style.ts
customers.slice.ts
customers.selectors.ts
customers.types.ts
customer-details.thunk.ts
// Folders - (lowerCase)
customers
user-details
Functions, Variables

camelCase
Component names, Types, Constants, Static

PascelCase
Components Line Limit

400
Don't Do's

Unused codes, Commented codes, Unused imports, Unused styles, Unused packages, Unused files
Disabling eslint, tslint, types, prettier