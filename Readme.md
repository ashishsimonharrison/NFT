
##### Submitted By : Ashish Simon Harrison
##### Email Id : harras02@pfw.edu
##### Github Repository Link : https://github.com/ashishsimonharrison/NFT

---

# Setting project on local
#### Setting Morlais Server on Local
Since moralis v2 has no longer support for web3 server on local, we will have to setup a web3 moralis server on local. [Link to documentation](https://moralis.io/how-to-set-up-a-self-hosted-web3-server/)

#### Cloning the repository
Cloning the repository given in the video

### Setting up variables
There are two variables that needs to be set in the `Logic.js` file to configure Moralis

    Moralis.initialize("012345"); // Application id from moralis.io
    Moralis.serverURL = "http://127.0.0.1:1337/server"; //Server url from moralis.io
    
Over here the moralis app id is the id we set in the local server, and serverURL is the path to local server.

### Installing the dependencies and running the build.

Run `yarn install` to installl the dependecies and then `yarn build` to create a build folder
    
### Step 5 : Running the application and logging in to Morlais
Run the application using the `yarn dev` command and filling in the form and click metamask to login.
Note : While logging in, we are getting an due to mismatch of moralis version (V2) and the Javascript SDK (V1) in the python applicaiton. Hence, was not able to proceed further.