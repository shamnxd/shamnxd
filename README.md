### Hey there!
```javascript
function Character(name, age, hobby) {
  this.name = name;
  this.age = age;
  this.hobby = hobby;
}

Character.prototype.bio = function() {
  return `Hi there, I'm ${this.name}, a ${this.age}-year-old Full Stack Developer who loves ${this.hobby}!`;
}

Character.prototype.interests = [
  'full-stack development',
  'building scalable web apps',
  'learning new technologies',
  'backend & cloud architecture',
  'modern React development'
];

const shamnad = new Character('Shamnad', 20, 'exploring tech');

console.log(shamnad.bio());
console.log(`My interests include: ${shamnad.interests.join(', ')}.`);
```

- How to reach me: [Email](mailto:shamnadthayyil8@gmail.com), [WhatsApp](https://wa.me/+919656633324)
