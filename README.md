![GitHub stats](https://github-readme-stats.vercel.app/api?username=mcote7&show_icons=true&theme=highcontrast)

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
> #### <code>🚀&nbsp;https://mcote7.github.io/michael-cote-profile/&nbsp;</code>

<img src="guages.svg" alt="g" width="300"/>&nbsp;

<hr>

<!--  -->
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mcote7&layout=compact&theme=highcontrast)

<br>

![](https://visitor-badge.laobi.icu/badge?page_id=mcote7.mcote7)&nbsp;&nbsp;
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
  "certification": TypeScript_master_class,
  "institution": "Ultimate Courses",
  "date": "June 2021"
},
{
  "certification": TypeScript_basics,
  "institution": "Ultimate Courses",
  "date": "May 2021"
},
{
  "certification": Design_thinking,
  "institution": "Udemy",
  "date": "May 2021"
},
{
  "certification": SASS_workflow,
  "institution": "Udemy",
  "date": "May 2021"
},
{
  "certification": Angular_4+,
  "institution": "Code with Mosh",
  "date": "April 2021"
},
{
  "certification": JavaScript_es6,
  "institution": "Udemy",
  "date": "March 2021"
},
{
  "certification": Redux_architecture,
  "institution": "Code with Mosh",
  "date": "July 2021"
},
{
  "certification": React_library,
  "institution": "Code with Mosh",
  "date": "June 2020"
},
{
  "certification": Full-stack_web_development,
  "institution": "Coding Dojo",
  "date": "June 2020"
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
