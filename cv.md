# Chernobrovkin Andrey
* Phone: 89080460753
* Email: adam.holo@mail.ru
### My purpose is to become a Frontend-development and get a job at EPAM and develop to the Senior level, then become a fullstack-development.
### My personal strengths:
  * Sociable
  * I always try to understand my own or someone else's work
  * As much as possible ready to learn new skills
### I have no experience working in IT companies. 
### Skills:
  * I can work with node.js(npm, npx)
  * ability to make up sites on the principle of mobile first, desktop first
  * ability to make up cross-browser sites
  * ability to work with ReactJS, webpack
### Sample JavaScript code:
```javascript
class Notification {
    constructor(text, idButton, textButton) {
        this.text = text;
        this.textButton = textButton;
        this.idButton = idButton;
    }

    createNotification() {
        document.body.style.backgroundColor = "rgba(0,0,0,.3)"
        this.center = document.createElement("center");
        this.notification = document.createElement("div");
        this.button = document.createElement("button");
        this.textStart = document.createElement("p");

        this.center.classList.add("center")

        this.notification.classList.add("notification");

        this.textStart.id = "textStart";
        this.textStart.innerHTML = this.text;

        this.button.id = this.idButton;
        this.button.classList.add("buttonStart");
        this.button.innerText = this.textButton;

        document.body.appendChild(this.center);
        this.center.appendChild(this.notification);
        this.notification.appendChild(this.textStart);
        this.notification.appendChild(this.button);
    }

    deleteNotification() {
        this.notification.style.animation = "unshow 1s 1";
        document.querySelector(".notification").remove();
        document.querySelector(".center").remove();
    }
}
```
### Education: UDSU(IMITIF)
### English level: a2 pre-intermediate
