Rewrite the following nested if() statements in a single line:
if (year % 4 == 0) {
    if (year % 100 != 0) {
      // DO STUFF
    } // end inner if statement
 } // end outer if statement
if ( year % 4 == 0 && year % 100 != 0) { // DO STUFF } // end inner if statement } // end outer if statement

Label each as either correct or incorrect syntax. If incorrect, rewrite below:
if (x == y) {

corect

if [x == 10] {

incorrect if (x == 10) {

if x = 10 then {

incorrect if (x = 10) {

if (x equals 42) {

incorrect if (x == 42) {

if (x => y) {

correct

Fix the error in the code below:
Scanner console = new Scanner(System.in);
System.out.print("What is your favorite color? ");
String name = console.next();
if (name == "blue") {
    System.out.println("Mine, too!");
}
