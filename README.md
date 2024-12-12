# outerFunction
function outerFunction() {  
    const message = "Hello, this is a closure!";  
 function innerFunction() {  
 console.log(message);  
    }  
return innerFunction;  
}  
const logMessage = outerFunction();  
logMessage();   
