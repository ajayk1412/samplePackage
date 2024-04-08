# Javascript npm package for React Native applications or javascript based framework.

# install

yarn add git+https://github.com/ajayk1412/samplePackage.git

# Package description

my-custom-package is a package name have printName function which console the paased parameter

# Sample code for App.js to use this printName function

import \* as React from 'react';

import { StyleSheet, View, Text } from 'react-native';
import {printName} from 'my-custom-package';

export default function App() {

React.useEffect(() => {
printName('ajay')
}, []);

return (
<View style={styles.container}>
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
