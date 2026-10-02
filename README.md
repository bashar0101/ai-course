<div dir="rtl" style="text-align: right;">

<h1>الذكاء الاصطناعي من الصفر: نسخة لموقعك</h1>

<hr>

<p>هذا المجلد موقع ثابت كامل. لا يحتاج خادماً خاصاً، ولا قاعدة بيانات.</p>

<h2>المحتوى:</h2>

<ul>
  <li><code>index.html</code> : الصفحة الرئيسية للدورة.</li>
  <li><code>lessons/</code> : الدروس الـ 59. الصفحة تحمّل كل درس عند فتحه.</li>
  <li><code>notebooks/*.ipynb</code> : دفتر كود لكل درس. زر <strong>«حمّل الكود من هنا»</strong> في كل درس يحمّل دفتره مباشرة.</li>
  <li><code>notebooks/all.json</code> : كل الدفاتر معاً. زر <strong>«تحميل كل الدفاتر»</strong> يجمعها في ملف مضغوط.</li>
  <li><code>vendor/jszip.min.js</code> : مكتبة صغيرة لصنع الملف المضغوط في المتصفح.</li>
</ul>

<h2>مهم</h2>

<p>
الصفحة لا تعمل إذا فتحتها بالنقر المزدوج من جهازك،
لأن المتصفح يمنع تحميل الدروس من الملفات المحلية.
</p>

<p>
شغّلها من خادم، أو من موقعك مباشرة.
</p>

<h2>في مدونتك (فايت وفيرسل)</h2>

<ol>
  <li>
    ضع المجلد كما هو داخل:
    <br>
    <code>public/courses/ai-from-zero/</code>
  </li>

  <li>
    شغّل المدونة محلياً، وافتح:
    <br>
    <code>http://localhost:5173/courses/ai-from-zero/index.html</code>
  </li>

  <li>
    انشر كالمعتاد. الرابط على موقعك:
    <br>
    <code>/courses/ai-from-zero/index.html</code>
  </li>
</ol>

<p>
كل ما فيه نقطة في رابطه لا يمر بقاعدة إعادة التوجيه في ملف إعدادات فيرسل،
لذلك يعمل هذا الرابط بلا أي تغيير.
</p>

<h2>اختياري: رابط أقصر بلا index.html</h2>

<p>
أضف <code>courses/</code> إلى الاستثناءات في ملف <code>vercel.json</code>:
</p>

<pre dir="ltr"><code>{
  "source": "/((?!assets/|img/|ds/|courses/|.*\\..*).*)"
}</code></pre>

<p>
بعدها يعمل أيضاً:
</p>

<pre dir="ltr"><code>/courses/ai-from-zero/</code></pre>

<h2>تجربة سريعة بلا مدونة</h2>

<p>من داخل المجلد الذي فيه <code>ai-from-zero</code>:</p>

<pre dir="ltr"><code>python -m http.server 8000</code></pre>

<p>ثم افتح:</p>

<pre dir="ltr"><code>http://localhost:8000/ai-from-zero/</code></pre>

</div>

