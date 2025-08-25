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
  "course": NgRx_Store_&_Effects,
  "institution": "Ultimate Courses",
  "date": "August 2021",
  "id": 15
},
{
  "course": RxJS_masterclass,
  "institution": "Ultimate Courses",
  "date": "July 2021",
  "id": 14
},
{
  "course": JS_advanced,
  "institution": "Udemy",
  "date": "July 2021",
  "id": 13
},
{
  "course": Ultimate_Angular,
  "institution": "Ultimate Courses",
  "date": "July 2021",
  "id": 12
},
{
  "course": UX_UI_design,
  "institution": "Udemy",
  "date": "July 2021",
  "id": 11
},
{
  "course": RxJS_basics,
  "institution": "Ultimate Courses",
  "date": "June 2021",
  "id": 10
},
{
  "course": TypeScript_master_class,
  "institution": "Ultimate Courses",
  "date": "June 2021",
  "id": 9
},
{
  "course": TypeScript_basics,
  "institution": "Ultimate Courses",
  "date": "May 2021",
  "id": 8
},
{
  "course": Design_thinking,
  "institution": "Udemy",
  "date": "May 2021",
  "id": 7
},
{
  "course": SASS_workflow,
  "institution": "Udemy",
  "date": "May 2021",
  "id": 6
},
{
  "course": Angular_4+,
  "institution": "Code with Mosh",
  "date": "April 2021",
  "id": 5
},
{
  "course": JavaScript_es6,
  "institution": "Udemy",
  "date": "March 2021",
  "id": 4
},
{
  "course": Redux_architecture,
  "institution": "Code with Mosh",
  "date": "July 2021",
  "id": 3
},
{
  "course": React_library,
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

```txt
From: 17 August 2025 - To: 24 August 2025

No activity tracked
```

<!--END_SECTION:waka-->
