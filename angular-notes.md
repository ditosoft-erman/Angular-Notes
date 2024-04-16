# angular notes

-To create a file inside the existing folder
ng new appName --directory ./ --no-standalone

# no stand alone

since angular 17 is standalone by default and no angular module. You needed the
"--no-standalone"

# How to update current angular version

ng update @angular/cli@^<major_version> @angular/core@^<major_version>

# update angular cli

npm uninstall -g @angular-cli
npm install -g @angular/cli@latest

# How to create components in angular 17

ng g c components/mycomponents

# How to create a module in a component

#ng generate module [module-name]

# If encountered 'no-tslib'

- Go to tsconfig.json and change importHelpers -> false

# Uninstall packages

- npm uninstall [name-of-package]
