# ***Ivan Pasternak***

## ***Front-end developer (React/React-Native)***

### **Contact me** 
****
****
#### Phone: *+375 (25) 702-18-85* 
#### Telegram: *[@paster_ivan](https://t.me/paster_ivan)*
#### Email: *paster-ivan@yandex.by*

### **PRO SKILLS**
****
****
#### *React/React Native*
#### *Redux (Toolkit)*
#### *Express/MongoDB*
#### *JavaScript/TypeScript*
#### *Axios/REST API*
#### *MUI/Tailwind*
#### *HTML/CSS*
#### *Git/GitHub*

### **EXPERIENCE**
****
****
#### **My work**
****
#### *[Intry](https://intry.me/)*
#### *[Sporty Pool](https://game.sportypool.cool/)*
#### *[Hostel 2028](https://hostel2028.com/)*
#### *[Hutor Stepnoi](http://hutorstepnoi.ru/)*
#### **Code example**
****

```
const snail = (array) =>{
  let newArray = []
  while(array.length){
    newArray.push(...array.shift())
    for (var i = 0; i < array.length; i++){
      newArray.push(array[i].pop())
    }
    newArray.push(...(array.pop() || []).reverse())
    for (var i = array.length -1; i >= 0; i--){
      newArray.push(array[i].shift())
    }
  }
  return newArray
}
```


