# 05 - Flex Panel Gallery - JavaScript30 Challenge

Practising css animation with vanilla javascript.

using code like
CSS:

```css
.active :last-child {
      transform: translateY(100%);
}
```

JS:

```javascript
function toggleActive(e) {
    console.log(e.propertyName);
    if (e.propertyName.includes('flex')) {
    this.classList.toggle('open-active');
    }
}

panels.forEach(panel => panel.addEventListener('transitionend', toggleActive));
```


## Getting Started

Clone or download the repository to your local drive.

### Prerequisites

What you need to install:

This project was created using Gulp automation tool, you can run the following command to the local repo directory to install all the dev dependencies 

```
npm install
```

Write gulp in the terminal / command line to run the live server.

## Authors

* **Mohamed Dewidar** - *practising the mentioned methods* - [Linkedin](https://www.linkedin.com/in/mohamed-dewidar-331252153/)

## License

This project is licensed under the MIT License. (open-source)

## Acknowledgments

* Wesbos - *creator of the challenge* - (https://github.com/wesbos/JavaScript30)