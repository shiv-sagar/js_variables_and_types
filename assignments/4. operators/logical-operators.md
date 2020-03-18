# Logical Operator

1. 🥇What's the output of the following, write the output next to the code as comment.

* [ ] Logical AND operation

```js
true  && true;                      //true
true  && false;                     //false
false && true;                      //false
false && false;                     //false
"foo" && "bar";                     //"bar"   
"bar" && "foo";                     //"foo"
"foo" && "";                        //""
""    && "foo";                     //""
" "   && "John" && "" && false      //""      
false && "Hey" && undefined         //false
"undefined" && false && 42          //false
```

* [ ] Logical OR operation
```js
true  || true;                      //true
true  || false;                     //true
false || true;                      //true
false || false;                     //false
"foo" || "bar";                     //"foo"
"bar" || "foo";                     //"bar"
"foo" || "";                        //""
""    || "foo";                     //"foo"
" "   || "John" || "" || false      //" "
false || "Hey" || undefined         //"Hey"
"undefined" || false || 42          //"undefined"
```

2. 🥈You have two variables i.e `isGuestOneVeg` and  `isGuestTwoVeg` according to the value using logical && and || opeartor do the following.

* [ ] If both are veg "Only offer up vegan dishes."
* [ ] At least one veg  "Make sure to offer up some vegan options."
* [ ] Else, "Offer up anything on the menu"
```js
let isGuestOneVeg = false;
let isGuestTwoVeg = false;
// Your code goes here
if (isGuestOneVeg && isGuestTwqVeg) {
    console.log("only offer up vegan dishes.")
} 
elseif (isGuestOneVeg || isGuestTwoVeg) {
    console.log("Make sure to offer up some vegan options.")
} else {
    "offer up anything on the menu
} 
```


3. 🎖Using the variable `temperature` and logical operators do the following
* [ ] If temperature is less then 32 alert "It is freezing outside"
* [ ] If the temperature is greater then 110 alert "It is hot outside"
* [ ] else 'Go for it. It is pretty nice out'
```js
let temperature = 4;
// Your code goes here
if (temperature < 32) {
    alert("It is freezing outside");
}
else if (temperature > 110) {
    alert("It is hot outside");
}
else {
    alert("Go for it. It is pretty nice out")
}
```

4. 🎖 Output of this and the reason behind the output.
```js
alert( alert(1) || 2 || alert(3) );

logical or operator looks for first truthy value , because alert(1) returns undefined logical or goes for next value 2 which is truthy value so the final output will be the result of alert(undefined || 2)  which is 2 .

```