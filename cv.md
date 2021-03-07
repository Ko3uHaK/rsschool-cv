## Daniil Kachura

### Contacts

- **_tel(MTS)_**: +375336050858
- **_tel(Life)_**: +375297663739
- **_mail_**: den2001888@yandex.by

### About me

I'm a beginner id Frontend development <br/>
My main goal is to become a specialist in this field<br/>

### My skills

- _HTML5_
- _CSS3 (SCSS)_
- _JS (ES6)_
- _Git_
- _SQL_
- _Photoshop, Figma, Avacode_

### My code

let money = prompt("Ваш бюджет на месяц?",""),
time = prompt("Введите дату в формате YYYY-MM-DD","");

let appData = {
budget : money,
timeData: time,
optionalExpenses : {},
expenses :{},
income : [],
savings : false
}

for (let i = 0; i < 2; i++) {
let a = prompt("Введите обязательную статью расходов в этом месяце", ""),
b = prompt("Во сколько обойдется?", "");
if ((typeof(a)==="string") && (typeof(a)) != null && (typeof(b)) != null && a != "" && b != "" && a.length < 50){
console.log("done");
appData.expenses[a] = b;
} else ;
}

### Work experience

without work experience
