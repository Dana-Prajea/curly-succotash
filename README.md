[![Actions Status](https://github.com/DanaBear/curly-succotash/workflows/.github/workflows/dotnetcore.yml/badge.svg)](https://github.com/DanaBear/curly-succotash/actions)

# curly-succotash

This is a simple (and useless) WPF app that contains even less useful tests. The purpose of this project was to test Github actions. The yaml file does the following: 

* Checks out the code 
* Builds project using a build file (which uses msbuild). The code that uses msbuild directly is also there, though commented out. 
* Runs the tests 
* Signs the resulting file with a pfx certificate
* Uploads the signed app to AWS S3. 

Feel free to use the yaml file as inspiration in your Github Actions journey. 
