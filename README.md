# Globalfetch
 
fetch('/path/to/resource.json')
 .then(response => {
 if (!response.ok()) {
 throw new Error("Request failed!");
 }
 
 return response.json();
 })
 .then(json => {
 console.log(json);
 });
