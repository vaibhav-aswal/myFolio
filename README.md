
#  MyFolio Portfolio Template [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

Dynamic Responsive portfolio template made with express. [Live preview](https://portfoliowebsite2002.herokuapp.com/)

![App Screenshot](https://raw.githubusercontent.com/VaibhavAswal/myFolio/main/public/assets/img/ezgif.com-gif-maker2.gif)




## Tech Stack 

**Server:** Node, Express

**Templating Engine:** pug

**External Resources used:** [ScrollRevealJs](https://github.com/jlmakes/scrollreveal), [MixItup](https://github.com/patrickkunka/mixitup/), [SwiperJs](https://github.com/nolimits4web/swiper)

**Design Idea:** [bedimcode](https://github.com/bedimcode/responsive-portfolio-website-Ansel)





## Features

- Dynamic (Automatically fetch projects from your git hub repositories)
- Responsive | designed for devices of all siges
- Light/Dark theme
- Light weight
- For demo [click here](https://portfoliowebsite2002.herokuapp.com/)


# How to use

### Run locally

Clone the project

```bash
  git clone https://github.com/VaibhavAswal/myFolio.git
```

Go to the project directory

```bash
  cd myFolio
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


### Cutomise

**To fetch projects from your Github**

Credential are stored in Config.js edit it with your Github token and username

```javascript
let config = {};

config.githubToken = 'YOUR GITHUB TOKEN HERE';
config.githubUsername = 'YOUR USERNAME HERE';

module.exports = config;
```

**For editing page contents**

Go to /views to access the index and projects of two pug templates.
Projects are dynamic while the index is static. Both can be modified to suit your requirements.

**For adding images and other static files**

You can store your files at /public from where your can dierectly link them in pug using. You can see linked css files in the projects for example




## Contributing

Contributions are always welcome!

You can create requests on dev branch

Please adhere to this project's `code of conduct`.


## Authors

- [@vaibhav aswal](https://github.com/VaibhavAswal)

## License [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

[GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)

![App Screenshot](https://raw.githubusercontent.com/VaibhavAswal/myFolio/main/public/assets/img/ezgif.com-gif-maker.gif)
