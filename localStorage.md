# Local Storage 
The local storage uses the localStorage object to store data for your entire website, permanently. That means the stored local data will be available on the next day, the next week, or the next year unless you remove it.
# Object
As stated earlier, the localStorage object stores the data with no expiration date. Each piece of data is stored in a key/value pair. The key identifies the name of the information (like 'first_name'), and the value is the value associated with that key (say 'Peter').
Example
```if(localStorage){
    // Store data
    localStorage.setItem("first_name", "Peter");
 
    // Retrieve data
    alert("Hi, " + localStorage.getItem("first_name"));
} else{
    alert("Sorry, your browser do not support local storage.");
}
```