# StepByStep

- Npm init
- git init
- npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/preset-react

## Babel Config (basic) <!--https://babeljs.io/docs/usage->

- touch .babelrc (in root)
- config presets
- {
    "presets": 
    [
      "@babel/preset-env",
      [
        "@babel/preset-react", 
          {
            "runtime": "automatic"
          }
      ]
    ]
  }
