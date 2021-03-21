# Javascript handbook   
###### by *Yan Babagbeto*

&nbsp;
<details>
    <summary>Whats is Javascript</summary>

    Javascript is a scripting language which is used to dynamically modify HTML and CSS via the DOcument Objet Model API. It's considered an interpreted language and can be used on client-side with vanilla javascript or server-side through Node.js
</details>

<details>
    <summary>Adding javascript to your page</summary>

Javascript can be added using the script tag in the head section of an html document, or can be added using inline javascript with html tag (not recommended ) or simply be references using the script tag on the body of a document by referencing src to an external .js file. This is the most prefered method. 

*async*: You can use async when you have to load and run multiple independants javascript scripts which are not dependant on any other script should be loaded while the html page is still loading. 

*defer*: You should use defer when you need to load multiple javascript scripts in a certain order. The scripts are then run in the order they appear in the page and executed as soon as they are all the scripts and content are downloaded.  


```js
    <script async src="script1.js"></script>

    <script defer src="script2.js"></script>

```
</details>


<details>
    <summary>for..in VS for..of</summary>
    
We use *for..in* to loop through objects and *for..of* to loop through arrays.
</details>
  
 <details>
    <summary>falsy values</summary>
    
|Falsy|
|-----|
|undefined|
|null|
|''|
|false|
|0|
|NaN|

</details>
