\<\!DOCTYPE html\>  
\<html lang="he" dir="rtl"\>  
\<head\>  
\<meta charset="UTF-8"\>  
\<meta name="viewport" content="width=device-width, initial-scale=1.0"\>  
\<title\>האחים מכונית בע"מ\</title\>

\<style\>  
body {  
  margin: 0;  
  font-family: Arial, sans-serif;  
  background: \#f4f6f8;  
  color: \#222;  
}

/\* HERO \*/  
.hero {  
  position: relative;  
  height: 360px;  
  background: url("carwash.jpg") center/cover no-repeat;  
  display: flex;  
  align-items: center;  
  justify-content: center;  
}  
.hero::after {  
  content: "";  
  position: absolute;  
  inset: 0;  
  background: rgba(0,0,0,0.45);  
}  
.hero-content {  
  position: relative;  
  text-align: center;  
  color: white;  
}  
.hero h1 {  
  margin: 0;  
  font-size: 42px;  
}  
.hero p {  
  margin-top: 10px;  
  font-size: 20px;  
}

/\* FORM CARD \*/  
.card {  
  background: white;  
  max-width: 900px;  
  margin: \-80px auto 40px;  
  padding: 30px;  
  border-radius: 14px;  
  box-shadow: 0 10px 30px rgba(0,0,0,0.15);  
}  
.form-row {  
  display: grid;  
  grid-template-columns: 1fr 2fr;  
  gap: 12px;  
  align-items: center;  
  margin-bottom: 15px;  
}  
label {  
  font-weight: bold;  
}  
input, select {  
  padding: 12px;  
  border-radius: 8px;  
  border: 1px solid \#ccc;  
  font-size: 16px;  
}  
button {  
  margin-top: 10px;  
  width: 100%;  
  padding: 16px;  
  background: \#5aa23c;  
  border: none;  
  border-radius: 10px;  
  color: white;  
  font-size: 20px;  
  cursor: pointer;  
}  
button:hover {  
  background: \#4a8c32;  
}

/\* REVIEWS \*/  
.reviews {  
  max-width: 1000px;  
  margin: 40px auto;  
  text-align: center;  
}  
.rating {  
  font-size: 22px;  
  margin-bottom: 20px;  
}  
.cards {  
  display: grid;  
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));  
  gap: 20px;  
}  
.review-card {  
  background: white;  
  padding: 20px;  
  border-radius: 12px;  
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);  
}  
.stars {  
  color: gold;  
  margin-bottom: 10px;  
}  
\</style\>  
\</head\>

\<body\>

\<\!-- HERO \--\>  
\<div class="hero"\>  
  \<div class="hero-content"\>  
    \<h1\>האחים מכונית בע"מ\</h1\>  
    \<p\>קביעת תור לשטיפת רכב\</p\>  
  \</div\>  
\</div\>

\<\!-- FORM \--\>  
\<div class="card"\>  
  \<form\>  
    \<div class="form-row"\>  
      \<label\>תאריך\</label\>  
      \<input type="text" value="יום שישי" readonly\>  
    \</div\>

    \<div class="form-row"\>  
      \<label\>שעה\</label\>  
      \<select\>  
        \<option\>09:00\</option\>  
        \<option\>09:35\</option\>  
        \<option\>10:10\</option\>  
      \</select\>  
    \</div\>

    \<div class="form-row"\>  
      \<label\>שם\</label\>  
      \<input placeholder="משה כהן"\>  
    \</div\>

    \<div class="form-row"\>  
      \<label\>טלפון\</label\>  
      \<input placeholder="050-1234567"\>  
    \</div\>

    \<button\>קבע תור\</button\>  
  \</form\>  
\</div\>

\<\!-- REVIEWS \--\>  
\<div class="reviews"\>  
  \<h2\>רווחת דעת לקוחות\</h2\>  
  \<div class="rating"\>  
    ⭐⭐⭐⭐⭐ \<strong\>4.8\</strong\> (112 ביקורות)  
  \</div\>

  \<div class="cards"\>  
    \<div class="review-card"\>  
      \<div class="stars"\>⭐⭐⭐⭐⭐\</div\>  
      \<strong\>יוסי לוי\</strong\>  
      \<p\>שירות מצוין, האוטו יצא מבריק\!\</p\>  
    \</div\>

    \<div class="review-card"\>  
      \<div class="stars"\>⭐⭐⭐⭐⭐\</div\>  
      \<strong\>דונית מ.\</strong\>  
      \<p\>מהיר, מקצועי ומחיר הוגן.\</p\>  
    \</div\>

    \<div class="review-card"\>  
      \<div class="stars"\>⭐⭐⭐⭐⭐\</div\>  
      \<strong\>אבי ד.\</strong\>  
      \<p\>ממליץ בחום, אחזור שוב.\</p\>  
    \</div\>  
  \</div\>  
\</div\>

\</body\>  
\</html\>

