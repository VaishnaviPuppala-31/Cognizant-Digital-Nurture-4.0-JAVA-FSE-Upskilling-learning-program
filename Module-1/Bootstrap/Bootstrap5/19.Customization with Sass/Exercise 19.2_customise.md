Steps:

Copy Bootstrap's _variables.scss file from node_modules/bootstrap/scss/_variables.scss into your scss/ folder.

Edit variables in your local _variables.scss before importing Bootstrap.

Example snippet inside your scss/custom.scss:

scss Copy Edit // Override variables before importing Bootstrap $primary: #ff6600; // Custom orange primary color $border-radius: 1rem; // Larger border radius

// Import Bootstrap core @import "../node_modules/bootstrap/scss/bootstrap"; Recompile:

bash Copy Edit npx sass scss/custom.scss css/custom.css Use css/custom.css in your HTML page.