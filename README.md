## 🧩 Bootstrap Components  

![HTML Badge](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)
![CSS Badge](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)
![Bootstrap Badge](https://img.shields.io/badge/Bootstrap-5.0-purple?logo=bootstrap&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Made by Harshi](https://img.shields.io/badge/Made_by-Harshi_Rajyaguru-pink)

---


## 📘 Aim  

To design a *webpage using Bootstrap components* such as Cards, Accordions, Buttons, Tables, and Badges to create a structured and responsive layout.

---

## 🧠 Objective  

- To understand and apply the *Bootstrap grid system* and components.  
- To develop a webpage that demonstrates *Cards, Accordions, Buttons, and Tables*.  
- To practice *responsive web design* using Bootstrap 5.  

---

## 🧰 Technologies Used  

| Technology | Description |
|-------------|-------------|
| *HTML5* | Page structure |
| *CSS3* | Styling elements |
| *Bootstrap 5* | Framework for layout and responsive design |

---

## 🗂 Project Structure

webtech-lab7/ │ ├── index.html ├── style.css  (optional) ├── images/ │   ├── img1.jpg │   ├── img2.jpg │   ├── img3.jpg │   └── img4.jpg └── README.md

---

## ⚙ Implementation  

### 1️⃣ Bootstrap Card Layout  

Displays four cards in a row with images, titles, and buttons.

```html
<div class="card-group">
  <div class="card">
    <img src="images/img1.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Card Title 1</h5>
      <p class="card-text">This is a short description for the card.</p>
      <a href="#" class="btn btn-primary">Read More</a>
    </div>
  </div>
  <div class="card">
    <img src="images/img2.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Card Title 2</h5>
      <p class="card-text">Another card with image and button.</p>
      <a href="#" class="btn btn-success">Explore</a>
    </div>
  </div>
</div>


---

2️⃣ Accordion Component

Accordion used to collapse and expand content.

<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show">
      <div class="accordion-body">
        This is the first accordion item content.
      </div>
    </div>
  </div>
</div>


---

3️⃣ Badges and Buttons

Bootstrap buttons and color-coded badges.

<h4>Badges Example:</h4>
<span class="badge bg-primary">Primary</span>
<span class="badge bg-success">Success</span>
<span class="badge bg-warning text-dark">Warning</span>
<span class="badge bg-danger">Danger</span>


---

4️⃣ Tables

Bootstrap styled table with striped rows and headings.

<table class="table table-striped">
  <thead class="table-dark">
    <tr>
      <th>ID</th>
      <th>Name</th>
      <th>Username</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Alice</td>
      <td>@alice01</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Tom</td>
      <td>@tommy</td>
    </tr>
    <tr>
      <td>3</td>
      <td>John</td>
      <td>@john99</td>
    </tr>
  </tbody>
</table>


---


🧾 Result

Successfully created a Bootstrap-based responsive webpage that includes:

Cards

Accordion

Buttons & Badges

Table


All components are interactive, responsive, and designed with Bootstrap 5 classes.


---


🏁 Conclusion

This lab helped understand the core Bootstrap components, grid layout, and responsive UI design practices used in modern web development.


---

