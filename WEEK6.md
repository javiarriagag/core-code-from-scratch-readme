<p align="center">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme#readme">Back to index</a>)</p>
<p align="right">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme/blob/main/WEEK2.md">Go to Next week</a>)</p>

#  $$\textcolor{skyblue}{\text{WEEK 6}}$$


## **DAY 1, MONDAY 22/8/2022**


### **TypeScript Unions :**<br>

```javascript
interface User {
    name: string;
    age: number;
    occupation: string;
}

interface Admin {
    name: string;
    age: number;
    role: string;
}

export type Person = User | Admin;

export const persons: Person[] /* <- Person[] */ = [
    {
        name: 'Max Mustermann',
        age: 25,
        occupation: 'Chimney sweep'
    },
    {
        name: 'Jane Doe',
        age: 32,
        role: 'Administrator'
    },
    {
        name: 'Kate Müller',
        age: 23,
        occupation: 'Astronaut'
    },
    {
        name: 'Bruce Willis',
        age: 64,
        role: 'World saver'
    }
];

export function logPerson(user: Person) {
    console.log(` - ${user.name}, ${user.age}`);
}

persons.forEach(logPerson);

```

<p align="right">(<a href="#top">back to top</a>)</p>


## **DAY 1, TUESDAY 23/8/2022**


### **Interpreted And Compiled Programming Languages :**<br>
