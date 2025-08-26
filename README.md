# Web-engineering-assignment-1
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Merged Marksheet - 10th & 12th</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: #f5f7fb;
      color: #222;
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: 1fr;
      gap: 20px;
    }

    /* For wider screens show side-by-side */
    @media(min-width: 900px) {
      .container { grid-template-columns: 1fr 1fr; }
    }

    .marksheet {
      background: #fff;
      border: 2px solid #000;
      border-radius: 8px;
      padding: 18px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.06);
    }

    .marksheet h2, .marksheet h3 {
      text-align: center;
      margin: 4px 0;
    }

    .details p { margin: 6px 0; }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 12px;
    }
    table, th, td {
      border: 1px solid #000;
    }
    th, td {
      padding: 8px;
      text-align: center;
      font-size: 14px;
    }

    .footer {
      margin-top: 14px;
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:10px;
      flex-wrap:wrap;
    }

    .badge {
      border:1px dashed #444;
      padding:6px 8px;
      border-radius:6px;
      font-size:13px;
    }
  </style>
</head>
<body>

  <h1 style="text-align:center; margin-bottom:18px;">Merged Marksheet — 10th & 12th</h1>

  <div class="container">

    <!-- 12th Marksheet (from provided code) -->
    <div class="marksheet" id="marksheet-12">
      <h2>Board of Secondary Education</h2>
      <h3>Class 12th Marksheet</h3>

      <div class="details">
        <p><strong>Name:</strong> Gaurav rajak</p>
        <p><strong>Roll Number:</strong> 233138445</p>
        <p><strong>School Name:</strong> Govt. Highr Secondary School Unchehra</p>
        <p><strong>Year:</strong> 2022</p>
      </div>

      <table>
        <tr>
          <th>Subject</th>
          <th>Maximum Marks</th>
          <th>Marks Obtained</th>
          <th>Grade</th>
        </tr>
        <tr><td>English</td><td>100</td><td>87</td><td>A</td></tr>
        <tr><td>Mathematics</td><td>100</td><td>92</td><td>A+</td></tr>
        <tr><td>Physics</td><td>100</td><td>85</td><td>A</td></tr>
        <tr><td>Chemistry</td><td>100</td><td>78</td><td>B+</td></tr>
        <tr><td>Hindi</td><td>100</td><td>90</td><td>A+</td></tr>
        <tr>
          <th>Total</th>
          <th>500</th>
          <th>432</th>
          <th>-</th>
        </tr>
      </table>

      <div class="footer">
        <div class="details" style="margin-top:10px;">
          <p><strong>Result:</strong> Pass</p>
          <p><strong>Percentage:</strong> 86.4%</p>
        </div>
        <div class="badge">Source: First provided OneCompiler code</div>
      </div>
    </div>

    <!-- 10th Marksheet (new template to merge with) -->
    <div class="marksheet" id="marksheet-10">
      <h2>Board of Secondary Education</h2>
      <h3>Class 10th Marksheet</h3>

      <div class="details">
        <p><strong>Name:</strong> Gaurav rajak</p>
        <p><strong>Roll Number:</strong> 233138445</p>
        <p><strong>School Name:</strong> Govt. Highr Secondary School Unchehra</p>
        <p><strong>Year:</strong> 2020</p>
      </div>

      <table>
        <tr>
          <th>Subject</th>
          <th>Maximum Marks</th>
          <th>Marks Obtained</th>
          <th>Grade</th>
        </tr>
        <tr><td>English</td><td>100</td><td>81</td><td>A</td></tr>
        <tr><td>Mathematics</td><td>100</td><td>88</td><td>A+</td></tr>
        <tr><td>Science</td><td>100</td><td>84</td><td>A</td></tr>
        <tr><td>Social Science</td><td>100</td><td>79</td><td>B+</td></tr>
        <tr><td>Hindi</td><td>100</td><td>86</td><td>A</td></tr>
        <tr>
          <th>Total</th>
          <th>500</th>
          <th>418</th>
          <th>-</th>
        </tr>
      </table>

      <div class="footer">
        <div class="details" style="margin-top:10px;">
          <p><strong>Result:</strong> Pass</p>
          <p><strong>Percentage:</strong> 83.6%</p>
        </div>
        <div class="badge">Second code: (no code found at provided URL) — template used</div>
      </div>
    </div>

  </div>

</body>
</html>
