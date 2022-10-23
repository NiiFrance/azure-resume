# azure-resume
My own azure resume following ACG Azure Cloud Resume Challenge Project

## First Steps
- Frontend folder contains the website
- main.js contains site visitors counter code

``` js
const functionApi = '';

const getVisitCount = () => {
    let count = 30;
    fetch (functionApi). then (response => {
        return response.json()
    }). then (resposne =>{
        console.log ("Website called function API.");
        count = response.count;
        document.getElementById ("counter"). innerText = count;
    }).catch(function(error){
        console.log(error)
    });
    return count;
```    