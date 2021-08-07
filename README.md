![GitHub stats](https://github-readme-stats.vercel.app/api?username=mcote7&show_icons=true&theme=react)

<hr>

### <code>🌎 Hello World&nbsp;</code>
> ## I'm Michael, a software developer.
---
### <code>🎯 I am currently focused on&nbsp;...&nbsp;</code>
> ### &bull;&nbsp;&Topf;ype&Sopf;cript<br>
>> ### &bull;&nbsp;&Aopf;ng&uopf;lar<br>
>>> ### &bull;&nbsp;&Sopf;ass<br>
>>>> ### &bull;&nbsp;&Fopf;ire&bopf;ase<br>
>>>>> ### &bull;&nbsp;&Wopf;eb &Dopf;esi&gopf;n<br>
##
> #### <code>🚀&nbsp;https://mcote7.github.io/michael-cote/&nbsp;</code>
---

<br>

<img src="gauges.svg" alt="guadges" width="360"/>&nbsp;

<hr>

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mcote7&layout=compact&theme=react)

<br>

![visitors](https://visitor-badge.laobi.icu/badge?page_id=mcote7.mcote7)&nbsp;&nbsp;
[![Github](https://img.shields.io/github/followers/mcote7?label=Follow&style=social)](https://github.com/mcote7)&nbsp;&nbsp;
<img src="ai-orb-transparent.gif" alt="my" width="30"/>&nbsp;
<img src="ai-orb-transparent.gif" alt="my" width="30"/>&nbsp;
<img src="ai-orb-transparent.gif" alt="my" width="30"/>&nbsp;

#

<details>
<summary>&nbsp;📜&nbsp;&nbsp;&nbsp;Certifications</summary>
<br>

```json
{
  "certification": RxJS_masterclass,
  "institution": "Ultimate Courses",
  "date": "July 2021",
  "id": 14
},
{
  "certification": JS_advanced,
  "institution": "Udemy",
  "date": "July 2021",
  "id": 13
},
{
  "certification": Ultimate_Angular,
  "institution": "Ultimate Courses",
  "date": "July 2021",
  "id": 12
},
{
  "certification": UX_UI_design,
  "institution": "Udemy",
  "date": "July 2021",
  "id": 11
},
{
  "certification": RxJS_basics,
  "institution": "Ultimate Courses",
  "date": "June 2021",
  "id": 10
},
{
  "certification": TypeScript_master_class,
  "institution": "Ultimate Courses",
  "date": "June 2021",
  "id": 9
},
{
  "certification": TypeScript_basics,
  "institution": "Ultimate Courses",
  "date": "May 2021",
  "id": 8
},
{
  "certification": Design_thinking,
  "institution": "Udemy",
  "date": "May 2021",
  "id": 7
},
{
  "certification": SASS_workflow,
  "institution": "Udemy",
  "date": "May 2021",
  "id": 6
},
{
  "certification": Angular_4+,
  "institution": "Code with Mosh",
  "date": "April 2021",
  "id": 5
},
{
  "certification": JavaScript_es6,
  "institution": "Udemy",
  "date": "March 2021",
  "id": 4
},
{
  "certification": Redux_architecture,
  "institution": "Code with Mosh",
  "date": "July 2021",
  "id": 3
},
{
  "certification": React_library,
  "institution": "Code with Mosh",
  "date": "June 2020",
  "id": 2
},
{
  "certification": Full-stack_web_development,
  "institution": "Coding Dojo",
  "date": "June 2020",
  "id": 1
}
```

</details>

#

<details>
<summary>&nbsp;🍕&nbsp;&nbsp;&nbsp;Class</summary>
<br>

```typescript
  
interface SizesInterface {
  availableSizes: string[];
}
abstract class Sizes implements SizesInterface {
  constructor(protected sizes: string[]) {}
  set availableSizes(sizes: string[]) {
    this.sizes = sizes;
  }
  get availableSizes() {
    return this.sizes
  }
} 
interface PizzaInterface extends SizesInterface {
  readonly name: string;
  toppings: string[];
  updateSizes(sizes: string[]): void;
  addTopping(topping: string): void;
}
export class Pizza extends Sizes implements PizzaInterface {
  public name: string;
  toppings: string[] = [];
  constructor(readonly name: string, sizes: string[]){
    super(sizes);  
  }
  public updateSizes(sizes: string[]) {
    this.sizes = sizes;
  }
  public addTopping(topping: string) {
    this.toppings.push(topping);
  }
}  
const pizza = new Pizza('pepperoni', ['small','x-large']);
pizza.addTopping('pepperoni');
pizza.updateSizes(['large']); 
class Coupon {
  static allowed = ['pepperoni','large'];
  static create(percentage: number) {
    return `PIZZA_COUPON_${percentage}%_OFF`;
  }
}
Coupon.create(25);

```

</details>

#

![stuff](https://github-profile-trophy.vercel.app/?username=mcote7&theme=darkhub&margin-w=10&column=7)

#

<!--START_SECTION:waka-->
```text
Week: 31 July, 2021 - 06 August, 2021

TypeScript   16 hrs 15 mins  ███████████░░░░░░░░░░░░░░   43.74 % 
SCSS         10 hrs 47 mins  ███████▒░░░░░░░░░░░░░░░░░   29.03 % 
JSX          7 hrs 30 mins   █████░░░░░░░░░░░░░░░░░░░░   20.19 % 
HTML         1 hr 47 mins    █▒░░░░░░░░░░░░░░░░░░░░░░░   04.83 % 
JavaScript   40 mins         ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.82 % 
```
<!--END_SECTION:waka-->
