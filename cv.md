# rsschool-cv
## Katsiaryna Stanevich
### Junior Javascript Engineer in Test

---

## Contact Information
- **Location:** Warsaw, Poland
- **Email:** [ek.stanevich@gmail.com](mailto:ek.stanevich@gmail.com)
- **LinkedIn:** [Ekaterina Stanevich](https://www.linkedin.com/in/ekaterina-stanevich)

---
## Self-Introduction
Hello. I recently completed QA automation courses and I'm eager to broaden my expertise into frontend development.


---

## Skills
- **Technologies:** Git, JavaScript, TypeScript, HTML
- **Frameworks:** Cypress, WebDriverIO, Cucumber
- **Testing:** Unit, API, e2e
- **CI/CD:** GitHub Actions, Cypress Cloud, Jenkins

---

## Code Examples

```js
const BasePage = require('./basePage')

class NewsPage extends BasePage {
  reaction(name) {
    return cy.xpath(`//div[@data-reaction="${name}"]`)
  }

  reactionsCounter(name) {
    return this.reaction(name).find('.st-count')
  }

  leaveReaction(name) {
    return this.reaction(name).click()
  }
}

module.exports = new NewsPage()
```

---

## Work Experience
- **September 2023:**  
  Developed a framework for automated testing of a marketplace and news site.  
  Technologies used: Cypress, Cypress Cloud, JavaScript, GitHub Actions.  
  [Project Link](https://github.com/katyastan/FinalWork)

---

## Education
- **May 2023 - September 2023**  
  IT Academy, JavaScript QA Automation Engineer  
  Grade: 9.69  
  [<img src="./images/certificate.png" alt="IT Academy Certificate" style="max-width:200px;" />](./images/certificate.png)


- **September 2013 - July 2018**  
  Belarusian National Technical University, Civil Engineer

---

## English Language
- B1 - Intermediate
