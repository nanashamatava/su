# su
davaleba
<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>შოთა რუსთაველი</title>
  <style>
    /* საერთო სტილი */
    body {
      font-family: "DejaVu Sans", sans-serif;
      margin: 0;
      line-height: 1.7;
      transition: background-color 0.5s, color 0.5s;
    }

    /* ღამე/მუქი რეჟიმი (საერთო საწყისი) */
    body.dark {
      background-color: #0e0e10;
      color: #f1f1f1;
    }

    body.dark header, body.dark footer {
      background: linear-gradient(90deg, #2d2d3a, #18181b);
      color: #f8f8f8;
      box-shadow: 0 2px 10px rgba(0,0,0,0.6);
    }

    body.dark section {
      color: #ddd;
    }

    body.dark h2 {
      color: #00c4ff;
      border-left: 4px solid #00c4ff;
      padding-left: 10px;
    }

    body.dark aside {
      background-color: #18181b;
      border-left: 4px solid #00c4ff;
      box-shadow: 0 0 15px rgba(0,0,0,0.5);
    }

    body.dark footer ul li::before {
      color: #00c4ff;
    }

    /* ღია რეჟიმი */
    body.light {
      background-color: #f8f8f8;
      color: #111;
    }

    body.light header, body.light footer {
      background-color: #ffffff;
      color: #111;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    body.light section {
      color: #222;
    }

    body.light h2 {
      color: #0077cc;
      border-left: 4px solid #0077cc;
      padding-left: 10px;
    }

    body.light aside {
      background-color: #f0f0f0;
      border-left: 4px solid #0077cc;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    body.light footer ul li::before {
      color: #0077cc;
    }

    /* Header */
    header {
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      letter-spacing: 1px;
    }

    header h3 {
      margin-top: 10px;
      font-weight: normal;
      color: inherit;
    }

    /* Section */
    section {
      padding: 30px 20px;
      max-width: 950px;
      margin: auto;
    }

    p {
      text-align: justify;
      margin-bottom: 15px;
    }

    strong {
      font-weight: bold;
    }

    span {
      font-weight: bold;
    }

    /* Aside */
    aside {
      margin: 40px auto;
      max-width: 850px;
      padding: 20px 25px;
      border-radius: 8px;
    }

    blockquote {
      margin: 0;
      font-style: italic;
      font-size: 1.2em;
      line-height: 1.6;
    }

    /* Gallery */
    .gallery {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 25px;
      margin-top: 20px;
    }

    img {
      width: 320px;
      height: auto;
      border-radius: 10px;
      transition: transform 0.3s ease;
      
    }

    img:hover {
      transform: scale(1.05);
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 30px 20px;
    }

    ul {
      list-style-type: none;
      padding: 0;
      margin: 15px 0 0;
    }

    li {
      padding: 5px 0;
    }

    li::before {
      content: "• ";
    }

    /* ღილაკი რეჟიმის შეცვლისთვის */
    #toggle-theme {
      position: fixed;
      top: 20px;
      right: 20px;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      background-color: #00c4ff;
      color: #111;
      transition: background-color 0.3s, color 0.3s;
    }

    #toggle-theme:hover {
      background-color: #0077aa;
      color: #fff;
    }
  </style>
</head>
<body class="dark">

  <button id="toggle-theme">დღის რეჟიმი</button>

  <header>
    <h1>შოთა რუსთაველი</h1>
    <h3>დაახლ. 1160 - 1220</h3>
  </header>

  <section id="biography">
    <h2>ბიოგრაფია</h2>
    <p>
      <strong>შოთა რუსთაველი</strong> იყო <span>ქართული კულტურისა და ლიტერატურის უდიდესი წარმომადგენელი</span>.  
      დაიბადა XII საუკუნის მეორე ნახევარში, სავარაუდოდ სოფელ რუსთავში, საიდანაც მიიღო გვარი — <strong>„რუსთაველი“</strong>.  
      მოღვაწეობდა თამარ მეფის ეპოქაში, როცა საქართველო კულტურულად და ეკონომიკურად აყვავებაში იყო.
    </p>

    <p>
      რუსთაველი იყო <strong>მაღალი განათლების მქონე</strong>, სწავლობდა უცხოეთში და ფლობდა ბერძნულ, სპარსულ და არაბულ ენებს.  
      იგი მსახურობდა თამარ მეფის კარზე და ითვლებოდა ერთ-ერთ განათლებულ მოხელედ.  
      მისი შემოქმედება გაჟღენთილია <span>სიყვარულის, ერთგულებისა და სამართლიანობის</span> იდეალებით.
    </p>

    <p>
      მისი უკვდავი ქმნილებაა <strong>„ვეფხისტყაოსანი“</strong> —  
      პოემა, რომელიც კაცობრიობის ერთ-ერთ უდიდეს ლიტერატურულ მემკვიდრეობად ითვლება.  
      რუსთაველი ასწავლის, რომ ადამიანის ნამდვილი ძალა მდგომარეობს <strong>სიბრძნესა და ღირსებაში</strong>.
    </p>
  </section>

  <aside>
    <blockquote>
      „სჯობს სიცოცხლე ხანმოკლე და სახელოვანი, ვიდრე სიცოცხლე გრძელი და უსახელო.“
    </blockquote>
  </aside>

<section id="gallery">
  <h2>გალერეა</h2>
  <div class="gallery">
    <img src="data:image/jpeg;base64,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" alt="შოთა რუსთაველის პორტრეტი">
    <img src="data:image/jpeg;base64,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" alt="„ვეფხისტყაოსნის“ ილუსტრაცია">
  </div>
</section>


  <footer>
    <h2>ცნობილი ნამუშევრები</h2>
    <ul>
      <li>„ვეფხისტყაოსანი“ — სიყვარულის, ერთგულებისა და ღირსების პოემა</li>
      <li>ფილოსოფიური გამონათქვამები — „სიბრძნე სიყვარულისა“</li>
      <li>ლირიკული სტროფები და ზნეობრივი იდეალები</li>
    </ul>
  </footer>

  <script>
    const toggleButton = document.getElementById('toggle-theme');
    const body = document.body;

    toggleButton.addEventListener('click', () => {
      body.classList.toggle('dark');
      body.classList.toggle('light');

      if(body.classList.contains('dark')) {
        toggleButton.textContent = '☀️ღამე';
      } else {
        toggleButton.textContent = '🌚დღე';
      }
    });
  </script>
</body>
</html>
