# Javascript

- __[Framework](url)__ - an application skeleton. It requires you to approach software design in a specific way and insert your own logic at certain points.
- __[Library](url)__ - a javascript file that contains a bunch of functions which accomplish a task in a webpage.
![framework vs library](https://www.programcreek.com/wp-content/uploads/2011/09/framework-vs-library.png)
 

|  Library       | Logo          | Description              |                                          
| -------------  |:-------------:| ------------------------:|  
| React          |               | Building user interfaces | 

### Code

// class HelloMessage extends React.Component {
  render() {
    return <div>Hello {this.props.name}</div>;
  }
}

// ReactDOM.render(
  <HelloMessage name="John" />,
  document.getElementById('container')
);

| Library| Logo        | Description                                                       |
| ------ |:-----------:| -----------------------------------------------------------------:|  
| jquery |             | revolutionized client-side development by introducing CSS selector|

### Code 
[More Samples](https://www.taniarascia.com/simple-jquery-examples-with-code-and-demos/)

// Clicking on the accordion header title...
	$(".accordion").on("click", ".accordion-header", function() {
	
	// will (slide) toggle the related panel.
 	$(this).toggleClass("active").next().slideToggle();
 });



|  Library            |   Logo      |    Description                                                    |
| ------------------- |:-----------:| -----------------------------------------------------------------:|  
| Lodash & Underscore | 	    |  provide hundreds of functional JavaScript utilities              |

### Code
[More Samples](http://underscorejs.org/)

// _.each(list, iteratee, [context])


