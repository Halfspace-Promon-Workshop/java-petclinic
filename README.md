# hs-promon-workshop
Halfspace workshop for Promon

# How to run
## Backend
### Dependencies (Global)
```sh
Java 17+
```
### Spin up the backend with Maven
```sh
cd backend
./mvnw spring-boot:run
```

## Frontend
Now the backend should be running in the terminal. 
So open a new terminal and cd to the frontend folder
```sh
cd frontend
```
### Dependencies (Global)
```sh
node 18+
npm 8+
```
check with 
```sh
node --version
npm -version
```
to see what version you currently have
### Spin up the development server frontend with `npm` and `npx`
Install local project package
````
npm install --legacy-peer-deps
````
You can see current local dependencies in [package.json](package.json) file.

Run 
````
npx ng serve
````

To spin up the dev server. 

Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Answer `N` to the following question:
````
? Would you like to share pseudonymous usage data about this project with the Angular Team
at Google under Google's Privacy Policy at https://policies.google.com/privacy. For more
details and how to change this setting, see https://angular.io/analytics.
````
