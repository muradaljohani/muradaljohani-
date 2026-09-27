<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="color-scheme" content="light dark">
  <title>مراد الجهني | مطور برمجيات</title>
  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      min-height: 100vh;
      display: grid;
      place-items: center;
      padding: 24px;
      background: #f6f8fa;
      color: #1f2328;
      font-family: system-ui, "Segoe UI", Arial, sans-serif;
      line-height: 1.9;
    }

    main {
      width: 100%;
      max-width: 650px;
      padding: clamp(24px, 6vw, 48px);
      background: #fff;
      border: 1px solid #d1d9e0;
      border-radius: 24px;
    }

    .label { color: #59636e; font-size: 14px; }
    h1 { margin: 8px 0; font-size: clamp(30px, 7vw, 44px); }
    h2 { margin-top: 28px; font-size: 19px; }
    p { margin: 12px 0; }
    .subtitle { margin-top: 0; color: #59636e; }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      padding: 0;
      list-style: none;
    }

    .skills li {
      padding: 5px 13px;
      border: 1px solid #d1d9e0;
      border-radius: 999px;
      font-size: 14px;
    }

    nav { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 30px; }

    a {
      display: inline-block;
      padding: 9px 18px;
      border: 1px solid #d1d9e0;
      border-radius: 10px;
      color: inherit;
      text-decoration: none;
      font-weight: 600;
    }

    a:hover { background: #eaeef2; }
    a:focus-visible { outline: 3px solid #0969da; outline-offset: 4px; }

    @media (prefers-color-scheme: dark) {
      body { background: #0d1117; color: #f0f6fc; }
      main { background: #151b23; border-color: #3d444d; }
      .label, .subtitle { color: #b1bac4; }
      .skills li, a { border-color: #3d444d; }
      a:hover { background: #262c36; }
    }
  </style>
</head>
<body>
  <main>
    <span class="label">تعرّف عليّ</span>
    <h1>مراد الجهني</h1>
    <p class="subtitle">مطور برمجيات ومصمم · طالب علوم حاسب</p>

    <p>
      أجمع بين البرمجة والتصميم لبناء منتجات رقمية عملية،
      بواجهات واضحة وتجربة استخدام تهتم بالتفاصيل.
      أدرس علوم الحاسب في كليات الخليج، وأطوّر معرفتي
      من خلال التعلم المستمر والعمل على مشاريعي.
    </p>

    <h2>مهاراتي واهتماماتي</h2>
    <ul class="skills" aria-label="المهارات والاهتمامات">
      <li>تطوير المواقع والتطبيقات</li>
      <li>تصميم واجهات المستخدم</li>
      <li>تحسين تجربة المستخدم</li>
      <li>دمج خدمات الذكاء الاصطناعي</li>
      <li>تطوير تجربة الجوال</li>
    </ul>

    <h2>مشاريعي</h2>
    <p>
      أعمل على تطوير <strong>سند الحرمين</strong>
      و<strong>كلاوك</strong>، مع التركيز على توسيع الإمكانات،
      وتحسين الأداء، وتبسيط تجربة الاستخدام.
    </p>

    <h2>طريقتي في العمل</h2>
    <p>
      أؤمن بالتطوير التراكمي: أبني على ما يعمل،
      وأعالج المشكلات، وأضيف مزايا تقدم قيمة واضحة للمستخدم.
      أهتم بأن يجتمع التصميم المتقن مع تجربة مستقرة وسهلة.
    </p>

    <nav aria-label="روابطي">
      <a href="https://ip-murad.com/u/ipmurad">ملفي الشخصي</a>
      <a href="https://github.com/muradaljohani">GitHub</a>
      <a href="https://klaok.ip-murad.com">كلاوك</a>
    </nav>
  </main>
</body>
</html>
