const express = require('express');
const app = express();

let counter = 1;

app.get('/', (req, res) => {
  // Send the current counter value as the response
  res.send(counter.toString());
  
  // Increment the counter and reset to 1 if it reaches 5
  counter = (counter % 5) + 1;
});

app.listen(3000, () => {
  console.log('Server is running on port 3000');
});
