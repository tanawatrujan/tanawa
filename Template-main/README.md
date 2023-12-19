# HTML , CSS, Bootstrap 5

## HTML Basic

### HTML Tags

Tags HTML คือ คำสั้น ๆ ที่ใช้ในการบ่งบอกว่าเนื้อหาในเว็บไซต์ของเรานั้นกำลังพูดถึงเรื่องอะไร รวมไปถึงเรื่องที่ใกล้เคียงกับเนื้อหาทั้งในบทความ หรือตัวของสินค้า โดยทั่วไปแล้ว Tags HTML จะประกอบไปด้วย 2 ส่วน ได้แก่

- ชื่อแท็ก (Tag name) เป็นคำสั้น ๆ ที่ใช้บ่งบอกประเภทของเนื้อหา เช่น h1, p, img, a เป็นต้น
- เนื้อหา (Content) เป็นข้อความหรือวัตถุที่แทรกอยู่ในแท็ก เช่น ข้อความธรรมดา รูปภาพ ลิงค์ เป็นต้น
- ตัวกำหนด (Attribute) ข้อกำหนดค่าของแท็ก

```html

<tags attribute=""> content  </tags>

```

### โครงสร้าง HTML


```html
<!-- ตัวบอกขนิดเอกสาร -->
<!DOCTYPE html>
<!-- html คือ แท็กใหญ่ -->
<html lang="en">
<!-- ส่วนหัว html -->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<!-- ส่วนเนื้อหาที่แสดงในหน้าเว็บ -->
<body>
    <!-- ใส่เนื้อหาใน body -->
</body>

</html>
```

## จัดการข้อความ HTML
```html
<h1>heading 1</h1>
<h2>heading 2</h2>
<h3>heading 3</h3>
<h4>heading 4</h4>
<h5>heading 5</h5>
<h6>heading 6</h6>



<p> paragraph </p>
<b> bold </b>
<i> italic </i>
<u> underline </u>
```

### ผลลัพ

# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6

paragraph

**bold**

*italic*

### จัดการเนื้อหา HTML

```html
<!-- จัดกลุ่มเนื้อหา -->
<div> เนื้อหา </div>


<!-- เว้นบรรทัด -->
<br>

<!-- เส้น -->
<hr>

```

### list
```html

<!-- list แบบไม่เรียง -->
<ul>
    <li></li>
    <li></li>
    <li></li>
</ul>
<!-- list แบบเรียง -->
<ol>
    <li></li>
    <li></li>
    <li></li>
</ol>

```

---
- list 1
- list 2
- list 3

1. list 1
2. list 2
3. list 3


### ใส่รูป
```html
<img src="" alt="" srcset="">

<!-- ใส่ที่อยู่รูปภาพใน src -->

```

### link
```html
<a href="">ข้อความ</a>
<!-- ใส่ลิงค์ใน href -->
```

## CSS

CSS ย่อมาจาก Cascading Style Sheets เป็นภาษาคอมพิวเตอร์ประเภทมาร์กอัป (Markup Language) ที่ใช้สำหรับกำหนดรูปแบบการแสดงผลของเอกสาร HTML โดย CSS จะทำหน้าที่กำหนดลักษณะขององค์ประกอบต่าง ๆ ในเอกสาร HTML เช่น สี ขนาด ตัวอักษร ระยะห่าง พื้นหลัง ฯลฯ

CSS เป็นภาษามาร์กอัป แตกต่างจากภาษาโปรแกรมทั่วไป เช่น Java, Python, C++ ตรงที่ CSS ไม่ได้ใช้ในการควบคุมการทำงานของคอมพิวเตอร์โดยตรง แต่จะใช้ในการกำหนดรูปแบบการแสดงผลของเอกสาร HTML เท่านั้น หน้าที่ของ CSS คือ บอกให้เว็บเบราว์เซอร์รู้ว่าควรแสดงองค์ประกอบต่าง ๆ ในเอกสาร HTML อย่างไร ตัวอย่างเช่น กำหนดให้หัวเรื่องมีสีดำ ตัวอักษรขนาด 16px พื้นหลังสีฟ้า เป็นต้น

### selector

```css
selector {
    property:value;
}
```

### selector type
```css
/* selector by tags name */
/* เข้าถึงด้วย ชื่อแท็ก */
h1 {
    color:red;
}

/* selector by class name */
/* เข้าถึงด้วย .  */
.text-red {
    color:red;
}

/* selector by id */
/* เข้าถึงด้วย # */
#app {
    display:flex;
}
```

### property basic
```css

div {
    color:red; /* สีฟอนท์ */
    background-color:black;  /* สีพื้นหลัง */
    font-size:36px; /* ขนาดตัวอักษร */

    margin:10px; /* ช่องว่างรอบตัว */
    padding:10px; /* ช่องว่างในตัว */
}
```


## Bootstrap 5
Bootstrap 5 คือ เฟรมเวิร์ก (Framework) ที่ใช้สำหรับพัฒนาเว็บไซต์ โดยรวบรวมชุดคำสั่งของ HTML, CSS และ JavaScript ไว้ด้วยกัน เพื่อช่วยให้การพัฒนาเว็บไซต์เป็นไปอย่างง่ายดายและมีประสิทธิภาพมากขึ้น

Bootstrap 5 ประกอบด้วยไฟล์ 2 ประเภทด้วยกัน คือ ไฟล์ CSS Stylesheet และไฟล์ JavaScript (JS) โดยแบ่งหน้าที่การทำงาน ไฟล์ CSS จะทำหน้าที่ช่วยออกแบบหน้าเว็บไซต์ (Read more: อธิบาย CSS) และไฟล์ JavaScript จะทำหน้าที่ช่วยเพิ่มประสิทธิภาพและฟีเจอร์ต่าง ๆ ให้กับเว็บไซต์ (Read more: อธิบาย JavaScript)

จุดเด่นของ Bootstrap 5 อยู่ที่การใช้งานที่ง่ายดายและมีประสิทธิภาพ โดย Bootstrap 5 มาพร้อมกับชุดคำสั่งและปุ่มต่าง ๆ ที่พร้อมใช้งานทันที ทำให้ผู้พัฒนาสามารถเริ่มต้นสร้างเว็บไซต์ได้อย่างรวดเร็ว นอกจากนี้ Bootstrap 5 ยังรองรับการตอบสนอง (Responsive) ได้ดี ทำให้เว็บไซต์สามารถแสดงผลได้อย่างเหมาะสมกับทุกอุปกรณ์

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bootstrap Class Example</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tTdvKuhfTAU6auU8tTdvKuhfTAU6auU8tTdvKuhfTAU6auU8tTdvK" crossorigin="anonymous">
</head>
<body>
  <div class="container">
    <div class="row">
      <div class="col-md-4 bg-primary">
        <h2>สีพื้นหลัง</h2>
      </div>
      <div class="col-md-4 m-5 p-5">
        <h2>Margin และ Padding</h2>
      </div>
      <div class="col-md-4 text-white bg-dark">
        <h2>สีพื้นหลังและสีข้อความ</h2>
      </div>
    </div>
  </div>
</body>
</html>

```

**บรรทัดที่ 9-10:** กำหนดคลาส row ให้กับองค์ประกอบ div เพื่อกำหนดให้องค์ประกอบ div แสดงผลเป็นแถว

**บรรทัดที่ 12-13:** กำหนดคลาส col-md-4 ให้กับองค์ประกอบ div แต่ละองค์ประกอบ เพื่อกำหนดให้องค์ประกอบ div แต่ละองค์ประกอบมีขนาดเท่ากับ 1 ใน 3 ของหน้าจอ

**บรรทัดที่ 15-16:** กำหนดคลาส bg-primary ให้กับองค์ประกอบ div แรก เพื่อกำหนดให้องค์ประกอบ div แรกมีสีพื้นหลังเป็นสีน้ำเงิน

**บรรทัดที่ 18-19:** กำหนดคลาส m-5 p-5 ให้กับองค์ประกอบ div ที่สอง เพื่อกำหนดให้องค์ประกอบ div ที่สองมี Margin ด้านบนและด้านล่าง 5rem และ Padding ด้านบน ข้าง และ ล่าง 5rem

**บรรทัดที่ 21-22:** กำหนดคลาส text-white bg-dark ให้กับองค์ประกอบ div ที่สาม เพื่อกำหนดให้องค์ประกอบ div ที่สามมีสีพื้นหลังเป็นสีดำและสีข้อความเป็นสีขาว