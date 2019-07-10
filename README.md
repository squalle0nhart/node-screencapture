# node-screencapture
Provide easy way to take screenshot. Support multiple screen.

# install
    npm install --save node-screenshotcapture
    
# usage
  ```
  import screencapture from 'node-screenshotcapture';
  screencapture((err, imagePath) => {
    // do whatever you want
     console.log(err, imagePath); 
  });
  ```