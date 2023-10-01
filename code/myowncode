// Start here

// Step 1 - Welcome and introduction
// Your code goes here
alert(
  `Welcome to our Javascript Pizzeria. Ready to Start? - Click 'OK' to begin.`
)

const userName = prompt("Please enter your name:");
alert(`Nice to meet you, ${userName}! Time to order some food!`);

// Step 2 - Food choice
// Your code goes here

// Prompt and ask which food the user want's to order
const foodChoice = prompt(`
What type of food would you like to order?
Enter a number:
1 - Pizza
2 - Pasta
3 - Salad

`);
// Initialize a variable to store the selected food.
let selectedFood = "";

// Determine the selected food based on the user's input.
if (foodChoice === "1") {
  selectedFood = "Pizza";
} else if (foodChoice === "2") {
  selectedFood = "Pasta";
} else if (foodChoice === "3") {
  selectedFood = "Salad";
} else {
  alert("Invalid choice, please start again and select an option. Bye 👋");
  exit(1);
}

// Display and confirm the user's selection

alert(`You've chosen ${selectedFood}!`);

// Step 3 - Subtype choice
// Your code goes here

/* Depending on the previously chosen food type, 
present the user with subtype options specific to that specific food
The prompt() method should be used to get the user's input. 
The program should then determine the chosen subtype and provide feedback 
using the alert() method to confirm the selection. Tip: Use conditional statements for this.
*/


let foodType = "";
let foodNames = [];

switch (selectedFood) {
  case "Pizza":
    foodType = prompt(
      `Select a Pizza type:
      Enter a number:
      1 - Napolitana
      2 - Hawaian
      3 - Pepperoni
      `
    );
    foodNames = ["Napolitana", "Hawaian", "Pepperoni"];
    break;

  case "Pasta":
    foodType = prompt(`Select a Pasta type:
    Enter a number:
      1 - Spaghetti Carbonara
      2 - Fettuccine Alfredo
      3 - Cheesy Tortellini
      `);
    foodNames = ["Spaghetti Carbonara", "Fettuccine Alfredo", "Cheesy Tortellini"];
    break;

  case "Salad":
    foodType = prompt(`Select a Salad type:
    Enter a number:
    1 - Caesar Salad
    2 - Caprese Salad
    3 - Greek Salad
    `);
    foodNames = ["Caesar Salad", "Caprese Salad", "Greek Salad"];
    break;

  default:
    alert("Invalid choice, please start again and select an option. Bye 👋");
    exit(1);
}


// Display and confirm the user's selection

if (foodType === "1") {
  alert(
    `You've chosen ${foodNames[0]}!`
  );
} else if (foodType === "2") {
  alert(
    `You've chosen ${foodNames[1]}!`
  );
} else if (foodType === "3") {
  alert(
    `You've chosen ${foodNames[2]}!`
  );
}


// Step 4 - Age
// Your code goes here

/*
In this iteration, the program should prompt the user to specify if the food is intended 
for a child or an adult. The prompt() method should be used to present the question 
and get the user's input. Based on the user's answer, an appropriate order message 
should be constructed. The program should use the alert() method to display the order 
message and the associated cost. The user's confirmation should be obtained 
using the prompt() method.
*/

let age = prompt("Is this food for a child or an adult? Type your age:");

let confirmationStatus;
if(age > 17) { 
confirmationStatus = prompt(`
One adult sized ${selectedFood} will be prepared for you. That'll be €15. 
Are you sure you want to order this? Enter a number to confirm:
1 - Yes
2 - No
`);
} else {
  confirmationStatus = prompt(`One child sized ${selectedFood} will be prepared for you. That'll be €10. 
  Are you sure you want to order this? Enter a number to confirm:
  1 - Yes
  2 - No`);
}



// Step 5 - Order confirmation
// Your code goes here

/*
The final iteration involves confirming the user's order based on their previous choices. 
The program should evaluate the user's confirmation and if the user confirms, 
a thank you message should be displayed using the alert() method, indicating 
that their meal will be prepared. If the user declines, a polite farewell 
message should be displayed using the alert() method, encouraging them to 
return for future orders.

*/


if (confirmationStatus === "1") {
  alert(
    `Thank you for your order! Your delicious meal will be prepared. See you soon!`
  );
} else if (confirmationStatus === "2") {
  alert(
    `No problem, come back and order anytime you want!`
  );
} else {
  alert(
    `Invalid choice, please start again and select an option.`);
    exit(1);
};
