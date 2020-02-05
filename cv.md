# Resume
## Alex Malkov

### Contacts
**alexex@gmail.com** 
*Discord:* Metr_#3992

### Summary
I want to become skillful developer, with main orientation on user interfaces. Because in my opinion excellent user experience is important as much as functionality of an app

### Skills
* HTML/CSS
* JS basics
* Python basics
* OOP

### Code examples:

[Does my number look big in this?](https://www.codewars.com/kata/52597aa56021e91c93000cb0)
```javascript
function moveZeros(arr) {
	let zeros = [];
	for ( let i = 0; i < arr.length; i++ ){
		if ( arr[i] === 0 ) {
			arr.splice(i, 1);
			zeros.push(0);
			i -= 1;
		}
	}
	return arr.concat(zeros);
}
```

[Moving Zeros To The End](https://www.codewars.com/kata/5287e858c6b5a9678200083c)
```javascript
function narcissistic(value) {
	let number = value.toFixed(0);
	let sum = 0;
	for( let x of number ){
		sum += Math.pow(parseInt(x),number.length);
	}
	return sum === value;
}
```

[Your order, please](https://www.codewars.com/kata/55c45be3b2079eccff00010f)
```javascript
function order(words){

	if( words.length === 0 ) return '';
  
	let words_list = words.split(" ");
	let patt1 = /[1-9]/g;
	let new_list = [];
  
	for( let x of words_list ){
		let num = x.match(patt1);
		new_list[parseInt(num)-1] = x;
	}

	return new_list.join(" ");
}
```

### Experience
Worked on couple layouts from psd templates. Had minor experience on creating and administration landing page using Wordpress CMS

### Education (including courses, seminars, lectures, online learning)*
Studied python(courses, myself),C++(university), javascript(myself). Couple courses on codeacademy, htmlacademy, youtube (various technologies).
Currently i am studying in RS school

### English
I have studied english since 1998 (courses, university, online)