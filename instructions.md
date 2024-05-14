# JavaScript IF Statements Practice
## Instructions

- Review the if statement examples shown below
- Then write your own if statements per the instructions

## Your GitHub Repo

1. Create a new GitHub repo: ***if-statements-js***

>Please make your repo **PUBLIC**.

2. Add your project files to your repo.
3. Publish your code and code updates to your online repo.
4. Submit the URL that points to your online repo on Google Classroom.

## Examples

### An IF statement

```javascript
const youEatMeat = true;
// If the user eats meat, tell them to order a hamburger!
if (youEatMeat) {
    console.log("Order a big, greasy hamburger!");
}
```

### A simple IF/ELSE statement
```javascript
const firstName = prompt("Please enter your first name:\n");
alert(`Greetings, ${firstName}!`);

if (firstName.length > 6) { 
	alert (`Wow, ${firstName}! Your first name contains ${firstName.length} characters!`);
} else {
	alert(`You have a short first name, ${firstName}!`);
}
```

### An IF/ELSE IF statement
```javascript
function checkNationality(nationality) {
  if (nationality === "US") {
    alert("You are American.");
  } else if (nationality === "UK") {
    alert("You are British.");
  } else if (nationality === "CA") {
    alert("You are Canadian.");
  } else {
    alert("Your nationality is not listed.");
  }
}

// Prompt the user for their nationality
const userNationality = prompt("Enter the code that represents your nationality: (US, UK, CA)\n");

// Call the function to check and display nationality
checkNationality(userNationality.toUpperCase()); // Convert input to uppercase using the JS toUpperCase ( ) method
```
