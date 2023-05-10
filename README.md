# React-Native-Twitter-Card

## About The Project

<!-- ![](https://github.com/kanakdesai/react-native-twitter-card/blob/main/light.png) -->
<a href="url"><img src="https://github.com/kanakdesai/react-native-twitter-card/blob/main/dark.png" align="center" height="841" width="500" ></a>
<a href="url"><img src="https://github.com/kanakdesai/react-native-twitter-card/blob/main/light.png" align="center" height="841" width="500"></a>

<br/>
<br/>

This npm package is for people who want to add a Twitter tweet card in their React Native apps. 

There is support for both light and dark mode. 
You can also add/remove the verification icon and also the Like button.



### Installation

_You can directly install this package in your existing react native project.


 Install NPM package
   ```sh
   npm i react-native-twitter-card
   ```
Sometimes you may have to restart metro to use this package.



<!-- USAGE EXAMPLES -->
## Usage

After your installation is completed you can import the package.
```sh
   import Twitter from 'react-native-twitter-card';
   ```
   
   ```sh
       import {View, Text, StyleSheet} from 'react-native';
       import React from 'react';
       import Twitter from 'react-native-twitter-card';

       export default function Test() {
       return (
           <View style={styles.container}>
               <Twitter></Twitter>
           </View>
        );
       }
       const styles = StyleSheet.create({
       container: {
       flex: 1,
       alignItems: 'center',
       justifyContent: 'center',
       },
       });

   ```
   ```sh
       accountName={'AccountName'} 
       userName={"userName"}
       proPicture={require('yourImageUrl')}
       verified={true}
       time={"9:30 PM"}
       date={"22 Nov 2023"}
       dark={true}
       like={true}
       tweet={"Your tweet"}

   ```
   
   You have to pass data in the <Twitter> component
  
        accountName: Your account name
        userName: Your username
        proPicture: profile picture you want to add
        verified={true}
        time={"9:30 PM"}
        date={"22 Nov 2023"}
        dark={true}
        like={true}
        tweet={"Your tweet"}>





<!-- CONTACT -->
## Contact

Email: kanakdesai1@gmail.com
If you encounter any bugs then please write to me on my email.


