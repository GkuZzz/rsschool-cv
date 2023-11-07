Gleb Kuzyak

Junior Frontend Developer

***

Hello!
I am starting my career as a frontend developer. Currently I am looking for an intern or junior position. I have no experience in a commercial development, but I constantly practice and develop my skills. I'll be happy to do a test task and join your team.

***
## Contact information
* Phone
+79295719531
* email
g.kuzyak@yandex.ru 
* Telegram
[@GlebKuzyak](адрес "https://t.me/GlebKuzyak")

***

## Summary

Last year I’ve decided to change my life and started to learn a Frontend-development. I’ve started with a project management in IT course (RedCamp course).
IT became interesting for me and I have decided to go further and started to learn the Frontend development in htmlacademy and hexlet simulators.
Then, in order to structure my knowledge, I have taken a RSSchool course, where I strengthened my knowledge in layout and began to study JS.

***

## Key Expertise

* HTML
* CSS/SCSS
* JavaScript
* Git
* Agile development methodologies
* English(b2)

## Courses
1. RS School «JavaScript/Front-end» 2023.
2. Udemi "JavaScript and React"
3. RedCamp «Base of project management» 2022.


***

## Code example:

Function from my pet project:

```
  const displayItems = () => {
  const html = items
    .map((item) => {
      return `
                <li class="pizza-item">
                    <button value="${item.id}"class="delete">&times;</button>
                    <div class="pizza-item-image">
                        <img src="${item.image}" alt="${item.title}">
                    </div>
                    <div class="pizza-items-details">
                        <div class="pizza-items-details-top">
                            <div class="itemHeader">
                                <input 
                                    value="${item.id}" 
                                    type="checkbox"
                                    ${item.selected === true ? 'checked' : ''}>
                                <span class ="itemName">${item.title}</span>
                            </div>
                            <span class="itemPrice">${item.price}</span>
                        </div>
                        <span class="pizza-items-details-bottom">${item.description}</span>
                    </div>
                </li>
            `;
    })
    .join("");

  list.innerHTML = html;
};

```

***

Languages:
* Russian - Native
* English - B2