JavaScript is a programming language that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed


JavaScript is a powerful programming language that can add interactivity to a website. It was invented by Brendan Eich.

JavaScript is versatile and beginner-friendly. With more experience, you'll be able to create games, animated 2D and 3D graphics, comprehensive database-driven apps, and much more!


Note that variables may hold values that have different data types:


Functions
function multiply(num1, num2) {
  let result = num1 * num2;
  return result;
}
multiply(4, 7);
multiply(20, 20);
multiply(0.5, 3);

Events
document.querySelector("html").addEventListener("click", function () {
  alert("Ouch! Stop poking me!");
});
document.querySelector("html").addEventListener("click", () => {
  alert("Ouch! Stop poking me!");
});