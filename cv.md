# Ivanov Sergey

---

## Junior Frontend Developer

---

#### _Contact information:_

**Location:** Ukraine, Sumy  
 **Phone number:** +380664152609  
 **Email:** IvanovSergey.94.28@gmail.com

&ensp;&ensp;&ensp;&ensp;[![Telegram logo](img/SVJ/telegram32px.png)](https://t.me/Ivan0vS27 "Link to my telegram page") &ensp;&ensp;&ensp;&ensp;[![Facebook logo](img/SVJ/facebook32px.png)](https://www.facebook.com/profile.php?id=100017419020667 "Link to my facebook page")

---

**University:** Sumy State University,
faculty of Electronics and Information Technology

---

**About me:**

> _&ensp;&ensp;&ensp;&ensp;I have good interpersonal skills, am an excellent team worker and very willing to learn and develop new skills._

---

**Skills:**

- HTML
- CSS
- Markdown
- javaScript

---
**Code example**

&ensp;&ensp;&ensp;&ensp;***KATA from CODEWARS:*** _This function replaces every letter with its position in the alphabet. If anything in the text isn't a letter, ignore it and don't return it._

```
function alphabetPosition(text) {
  let newArr = text
    .toLowerCase()
    .split("")
    .reduce((acc, item) => {
      if (item.charCodeAt() > 96 && item.charCodeAt() < 123) {
        return acc + ` ${item.charCodeAt() - 96}`;
      } else {
        return acc;
      }
    }, "");

  return newArr.slice(1);
}
```
