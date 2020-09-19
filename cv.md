## Oleksandr Zelenskyi

* email: zelensk1973@gmail.com
* phone: +380973582250
* telegram: alex_zelenskiy

## About me
I work a teacher physics and computer science. My goal is to keep abreast of current trends IT industries and develop towards Frontend development. I like to study. For more than 10 years I worked as a software engineer in a bank, where I mostly dealt with the support of specialized software and sql. I like teaching the most. But I understand that for teaching you need to understand not only theory, but also be an experienced practitioner.

Programming is my hobby. I have experience in preparing children to participate in programming competitions. I program on a python, c++, pascal, javascript. I have experience in developing on python django as a backend and frontend for it. i work with github. Own tools: PyCharm, git, draw.io, miro, trello and other.

## Example code

<<<<<<< HEAD
```function draw_chordes() {
=======
```
function draw_chordes() {
>>>>>>> rsschool-cv-html

    let ma = (m2.y - m1.y) / (m2.x - m1.x);
    let mb = (m3.y - m2.y) / (m3.x - m2.x);
    let xc0 = (ma * mb * (m1.y - m3.y) + mb * (m1.x + m2.x) - ma * (m2.x + m3.x)) / (2 * (mb - ma));
    let yc0 = -1 / ma * (xc0 - (m1.x + m2.x) / 2) + (m1.y + m2.y) / 2;
    let x12 = (m1.x + m2.x) / 2;
    let y12 = (m1.y + m2.y) / 2;
    let x23 = (m2.x + m3.x) / 2;
    let y23 = (m2.y + m3.y) / 2;
    let r = Math.sqrt((m1.x - xc0) * (m1.x - xc0) + (m1.y - yc0) * (m1.y - yc0));
    let tmp = document.getElementById("calibr_edit").value;
<<<<<<< HEAD

    tmp = tmp.replace(',', '.');
    let mashtab = parseFloat(tmp);
    console.log("mashtab->" + mashtab);
    let kalibr_length = Math.sqrt((k1.x - k2.x) * (k1.x - k2.x) + (k1.y - k2.y) * (k1.y - k2.y));
    let R = r * mashtab / kalibr_length;
    document.getElementById("lbl2").innerText = "R = " + R;

    ctx.beginPath();
    ctx.moveTo(mk_trans(m1.x, x0), mk_trans(m1.y, y0));
    ctx.strokeStyle = "red";
    ctx.stroke();
    ctx.lineTo(mk_trans(m2.x, x0), mk_trans(m2.y, y0));
    ctx.stroke();
    ctx.lineWidth = 3;
    ctx.stroke();
    ctx.moveTo(mk_trans(x12, x0), mk_trans(y12, y0));
    ctx.lineTo(mk_trans(xc0, x0), mk_trans(yc0, y0));
    ctx.stroke()
    ctx.closePath();

    ctx.beginPath();
    ctx.moveTo(mk_trans(m2.x, x0), mk_trans(m2.y, y0));
    ctx.strokeStyle = "blue";
    ctx.stroke();
    ctx.lineTo(mk_trans(m3.x, x0), mk_trans(m3.y, y0));
    ctx.lineWidth = 3;
    ctx.stroke();
    ctx.moveTo(mk_trans(x23, x0), mk_trans(y23, y0));
    ctx.lineTo(mk_trans(xc0, x0), mk_trans(yc0, y0));
    ctx.stroke()
    ctx.closePath();

    ctx.beginPath();
    ctx.lineWidth = 2;
    ctx.strokeStyle = "green";
    ctx.arc(mk_trans(xc0, x0), mk_trans(yc0, y0), r * mmm[mash], 0, 2 * Math.PI);
    ctx.stroke()
    ctx.closePath();
};
```

## Courses and interships
Basics of web development (Ed-Era	HTML, CSS, JavaScript) 2020
Teacher's intership program held by EPAM Systems 2020
CS50: Introduction to Computer Science | Harvard University (online)

=======

    tmp = tmp.replace(',', '.');
    let mashtab = parseFloat(tmp);
    console.log("mashtab->" + mashtab);
    let kalibr_length = Math.sqrt((k1.x - k2.x) * (k1.x - k2.x) + (k1.y - k2.y) * (k1.y - k2.y));
    let R = r * mashtab / kalibr_length;
    document.getElementById("lbl2").innerText = "R = " + R;

    ctx.beginPath();
    ctx.moveTo(mk_trans(m1.x, x0), mk_trans(m1.y, y0));
    ctx.strokeStyle = "red";
    ctx.stroke();
    ctx.lineTo(mk_trans(m2.x, x0), mk_trans(m2.y, y0));
    ctx.stroke();
    ctx.lineWidth = 3;
    ctx.stroke();
    ctx.moveTo(mk_trans(x12, x0), mk_trans(y12, y0));
    ctx.lineTo(mk_trans(xc0, x0), mk_trans(yc0, y0));
    ctx.stroke()
    ctx.closePath();

    ctx.beginPath();
    ctx.moveTo(mk_trans(m2.x, x0), mk_trans(m2.y, y0));
    ctx.strokeStyle = "blue";
    ctx.stroke();
    ctx.lineTo(mk_trans(m3.x, x0), mk_trans(m3.y, y0));
    ctx.lineWidth = 3;
    ctx.stroke();
    ctx.moveTo(mk_trans(x23, x0), mk_trans(y23, y0));
    ctx.lineTo(mk_trans(xc0, x0), mk_trans(yc0, y0));
    ctx.stroke()
    ctx.closePath();

    ctx.beginPath();
    ctx.lineWidth = 2;
    ctx.strokeStyle = "green";
    ctx.arc(mk_trans(xc0, x0), mk_trans(yc0, y0), r * mmm[mash], 0, 2 * Math.PI);
    ctx.stroke()
    ctx.closePath();
};
```

## Courses and interships
* Basics of web development (Ed-Era	HTML, CSS, JavaScript) 2020
* Teacher's intership program held by EPAM Systems 2020
* CS50: Introduction to Computer Science | Harvard University (online)

>>>>>>> rsschool-cv-html
## English
English A2 level. I can read the technical documentation. I have difficulty understanding and speaking.

