# Horiseon-Refactor

The purpose of the Horiseon code refactor is to ensure that the agency's website follows accessibility standards. This is necessary to ensure that site is optimized for search engines. 

### Code Refactor 

In index.html document began making site more accessible by adding &lt;alt&gt;text to all images on website to follow accessibility standards.  
``` html
<img src="./assets/images/online-reputation-management.jpg" 
    class="float-right" 
    alt="Laptop with word Reputation on screen" 
/>
```

#### CSS Code Refactor
Several opportunities within the CSS code to consolidate multiple code blocks into one single block, and still achieving the same results.
``` css
.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}
```

``` CSS
 .benefit-lead h3, .benefit-brand h3, .benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}
 ```

## GitHub Repository
* [See Repository Here](https://github.com/CTep09/Horiseon-Refactor)

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Deployed Link

* [See Live Site](https://ctep09.github.io/Horiseon-Refactor/)


## Authors

* **Cassandra Tepper** 

- [Link to Github](https://github.com/CTep09)
- [Link to LinkedIn](https://www.linkedin.com/in/cassie-tepper/)

## License

This project is licensed under the MIT License 

