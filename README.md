# IOTA App

## Prerequisites

1. Download [NodeJS](https://nodejs.org/en/download/)

2. Install [Electron](http://electron.atom.io):

  ```
  npm install -g electron-prebuilt
  ```

3. Install [Bower](https://bower.io/):

  ```
  npm install -g bower
  ```

## Instructions

1. Create a new directory: 

  ```
  mkdir iota
  ```

2. Go to the `iota` directory:

  ```
  cd iota
  ```

3. Clone repositories:

  ```
  git clone https://github.com/iotaledger/wallet
  git clone https://github.com/iotaledger/iri
  ```

  Note: iri project does not exist yet -- make an IRI directory manually and place IRI.jar in it.
  
4. Install components

  ```
  npm install
  ```

5. Run the app:

  ```
  npm start
  ```