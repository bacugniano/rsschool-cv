# Vitaly Bakuntsev, Front-end Developer #

![Vitaly Bakuntsev](/img/photo.png)

Hi, my name is Vitaly and I am a novice web developer.I have small commercial experience in website development - there are two small projects. I am good at site layout, but my JavaScript level is low.  That's why I want to improve my knowledge in JavaScript, learn some framework (like React or Vue) and find a job as a Front-end developer.

## Contacts ##
* [Telegram](https://t.me/bm0112)
* [LinkedIn](https://www.linkedin.com/in/vitaly-bakuntsev-7b3b91165/)
* [Github](https://github.com/bacugniano/)
* <bakuntsev@gmail.com>

## Skills ##
* HTML
* CSS
* BEM
* SCSS
* Basic JS
* English A1

## Expirience ##
* [Rocat](https://bacugniano.github.io/rocat/)
* [Straw](https://bacugniano.github.io/straw/)

## Education ##

2018, Francisk Skorina Gomel State University, Software Engineer


## Example code ##
```javascript

let tab = function () {
    let tabNav = document.querySelectorAll('.tab-navigation__item'),
        tabContent = document.querySelectorAll('.details'),
        tabName;

    tabNav.forEach(item => {
        item.addEventListener('click', selectTabNav)
    });

    function selectTabNav() {
        tabNav.forEach(item => {
            item.classList.remove('tab-navigation__item--active');
        });
        this.classList.add('tab-navigation__item--active');
        tabName = this.getAttribute('data-tab-name');
        selectTabContent(tabName);
    }

    function selectTabContent(tabName) {
        tabContent.forEach(item => {
            item.classList.contains(tabName) ? item.classList.add('details--active', 'animate__animated', 'animate__fadeIn') : item.classList.remove('details--active', 'animate__animated', 'animate__fadeIn');
        })
    }

};

```


