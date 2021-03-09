<p align="center">
  <img src="./images/cover.png" />
</p>

<h1 align="center">Vishnu C Prasad</h1>

<p>
Logical and results-driven Junior Web Developer dedicated to building and optimizing user-focused websites for customers with various business objectives. Judicious and creative when crafting effective websites and platforms to propel competitive advantage and revenue growth. Technically proficient and analytical problem solver with calm and focused demeanor.
</p>

<hr>

```js
class Developer {
    constructor(props) {
        this.name = props.name;
        this.title = props.title;
        this.birthday = props.birthday;
        this.location = props.location;
    }
    whoAmI() {
        return {
            name: this.name,
            title: this.title,
            location: this.location
        }
    }
}

class Me extends Developer {
    constructor(props, skills) {
        super(props);

        this.skills = skills;
    }
    whoAmI() {
        let me = super.whoAmI();

        if(this.skills) {
            me.skills = this.skills;
        }

        return me;
    }
}

const props = {
    name: 'Vishnu C Prasad',
    title: 'Web Developer',
    birthday: '25 August 2001',
    location: 'Kanjirappally, Kottayam, Kerala, India'
};

const skills = {
    languages: ['HTML', 'CSS', 'JavaScript', 'NodeJS'],
    frameworks: ['React', 'Express', 'Bootstrap'],
    viewEngines: ['handlebars'],
    databases: ['MongoDB'],
    others: ['Git', 'Java', 'C', 'C++']
};

const me = new Me(props, skills);

console.log(me.whoAmI());
```

#### Output (ie, Me)
```
{
  name: 'Vishnu C Prasad',
  title: 'Web Developer',
  birthday: '25 August 2001',
  location: 'Kanjirappally, Kottayam, Kerala, India',
  skills: {
    languages: [ 'HTML', 'CSS', 'JavaScript', 'NodeJS' ],
    frameworks: [ 'React', 'Express', 'Bootstrap' ],
    viewEngines: [ 'handlebars' ],
    databases: [ 'MongoDB' ],
    others: [ 'Git', 'Java', 'C', 'C++' ]
  }
}
```
<br>
<hr>
<br>
<h2 align="center">You can reach me at</h2>
<br>

<p align="center">
  
  <a href="https://www.linkedin.com/in/mrvishnucp001/">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="Angel Santiago Jaime Zavala's LinkedIn Profile" height="30" width="30">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://vishnucprasad.github.io">
    <img src="https://www.vectorlogo.zone/logos/wikipedia/wikipedia-icon.svg" alt="Angel Santiago Jaime Zavala's LinkedIn Profile" height="30" width="30">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://instagram.com/vishnu_c_prasad/">
    <img src="https://www.vectorlogo.zone/logos/instagram/instagram-icon.svg" alt="Angel Santiago Jaime Zavala's Stack Exchange Profile" height="30" width="30">
  </a>

</p>

<br>
<hr>

<div align="right">

[Vishnu C Prasad](https://github.com/vishnucprasad)

</div>