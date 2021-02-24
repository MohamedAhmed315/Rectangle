# Rectangle
Compute the area and circumference of a rectangle

const readline = require('readline').createInterface({
    input: process.stdin,
    output: process.stdout
  })
  
  readline.question(`Enter rectangle length: `, (length) => {
    readline.question(`Enter rectangle width: `, (width) => {

    let area = length * width;
    let Circumference = (Number(length) + Number(width)) * 2;

    console.log("----------------------");
    console.log("Area = " + area);
    console.log("Circumference = " + Circumference);
    readline.close();
    })
  });
