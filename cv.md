# Chernobrovkin Andrey
* Phone: +79080460753
* Email: adam.holo@mail.ru
* Discord: Adam_An#2938
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
function formatDuration (seconds) {
  if(seconds === 0) return "now";
  
  const date = new Date(seconds * 1000 )
  let second  = date.getSeconds();
  let minutes = date.getMinutes();
  let hour    = date.getHours();
  let days    = Math.floor(seconds / (60 * 60 * 24)) % 365;
  let years   = date.getFullYear() - (new Date(0)).getFullYear();
  
  second  = (second === 0)  ? "" : (second === 1)  ? `${second} second` : `${second} seconds`;
  minutes = (minutes === 0) ? "" : (minutes === 1) ? `${minutes} minute`: `${minutes} minutes`;
  hour    = (hour === 0)    ? "" : (hour === 1)    ? `${hour} hour`     : `${hour} hours`;
  days    = (days === 0)    ? "" : (days === 1)    ? `${days} day`      : `${days} days`;
  years   = (years === 0)   ? "" : (years === 1)   ? `${years} year`    : `${years} years`;
  
  let arr = [years, days, hour, minutes, second].filter(i => i !== "");
           
  let dateStr = arr[0];
  for(let i = 1; i < arr.length; i++){
    if(i === arr.length - 1) 
      dateStr = `${dateStr} and ${arr[i]}`;
    else 
      dateStr = `${dateStr}, ${arr[i]}`;
  }

  return dateStr;
}
```

### Completed projects: 
  * Match-match game (https://rolling-scopes-school.github.io/adam0091-JSFE2021Q1/match-match-game/)

  * Photo-filter (https://rolling-scopes-school.github.io/adam0091-JSFE2021Q1/photo-filter/)

  * Virtual-piano (https://rolling-scopes-school.github.io/adam0091-JSFE2021Q1/virtual-piano/)

  * Wildlife (https://rolling-scopes-school.github.io/adam0091-JSFE2021Q1/wildlife/)

  * CoursesDev (https://adam0091.github.io/portfolio/CoursesDev/)

  * YEBO Bicycle Theme (https://adam0091.github.io/portfolio/BicycleTheme/)

  * ToxinHotel (https://adam0091.github.io/portfolio/ToxinHotel/room_details/)


### Education: UDSU (IMITIF)
### English level: A2 (pre-intermediate)