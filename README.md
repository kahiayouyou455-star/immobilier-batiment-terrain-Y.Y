
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Im. B.T.YA - Immobilier</title>
<style>
body{font-family:Arial,sans-serif;margin:0;background:#f3f5f7;color:#222}
header{background:#123b35;color:white;text-align:center;padding:24px 12px}
header h1{margin:0 0 10px}
nav{background:#20564d;padding:12px;text-align:center}
nav a{color:white;margin:8px;text-decoration:none}
main{max-width:850px;margin:auto;padding:15px}
section{background:white;border-radius:10px;padding:18px;margin-bottom:18px}
h2{color:#20564d}
input,select,textarea,button{width:100%;box-sizing:border-box;padding:12px;margin:7px 0;border:1px solid #ccc;border-radius:6px;font-size:16px}
button{background:#20564d;color:white;border:0;cursor:pointer}
.property{border:1px solid #ddd;border-radius:8px;padding:12px;margin:12px 0}
.property img{width:100%;max-height:260px;object-fit:cover;border-radius:6px}
.small{font-size:13px;color:#666}
footer{text-align:center;background:#123b35;color:white;padding:20px}
</style>
</head>
<body>

<header>
<h1>Im. B.T.YA</h1>
<p>Immobilier • Maisons • Appartements • Terrains</p>
<p>بيع وشراء المنازل والشقق والأراضي</p>
</header>

<nav>
<a href="#listings">العقارات</a>
<a href="#submit">أضف عقارك</a>
<a href="#contact">اتصل بنا</a>
</nav>

<main>
<section id="listings">
<h2>🏠 العقارات المتاحة للبيع</h2>
<p>هنا تظهر العقارات المقبولة بعد مراجعتها.</p>
<div id="properties">
<p>لا توجد إعلانات منشورة حاليًا.</p>
</div>
</section>

<section id="submit">
<h2>📝 أرسل إعلان عقارك</h2>
<form id="propertyForm">
<label>الاسم واللقب *</label>
<input name="owner" required>

<label>رقم هاتف صاحب العقار *</label>
<input name="phone" type="tel" required>

<label>نوع العقار *</label>
<select name="kind" required>
<option value="">اختر النوع</option>
<option>منزل</option>
<option>شقة</option>
<option>أرض</option>
<option>محل تجاري</option>
<option>فيلا</option>
</select>

<label>الولاية *</label>
<input name="wilaya" required>

<label>البلدية *</label>
<input name="city" required>

<label>السعر بالدينار الجزائري *</label>
<input name="price" type="number" min="1" required>

<label>وصف العقار *</label>
<textarea name="description" rows="4" required></textarea>

<label>صور المنزل أو الأرض *</label>
<input name="photos" id="photos" type="file"
accept="image/*" multiple required>

<label>صورة وثيقة الهوية *</label>
<input name="identity" type="file"
accept="image/jpeg,image/png,image/webp" required>

<p class="small">
وثيقة الهوية وثيقة شخصية حساسة. لا ترفع وثائق حقيقية
في هذه النسخة التجريبية؛ فالملف لا يوفر تخزينًا آمنًا
ولا يرسلها إلى الإدارة.
</p>

<button type="submit">إرسال الإعلان للمراجعة</button>
</form>
<div id="message"></div>
</section>

<section id="contact">
<h2>📞 اتصل بنا</h2>
<p>للاستفسار عن العقارات والإعلانات:</p>
<a href="tel:0782270261">اتصل بالإدارة: 0782 27 02 61</a>
</section>
</main>

<footer>
<p>Im. B.T.YA – Immobilier</p>
<p>العقارات في الجزائر</p>
</footer>

<script>
document.getElementById("propertyForm").addEventListener("submit",function(e){
 e.preventDefault();
 document.getElementById("message").textContent =
 "شكرا المعلوماتك على قيد المعالجة

</body>
</html>

التوفيق
