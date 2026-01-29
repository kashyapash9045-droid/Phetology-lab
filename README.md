# Phetology-lab
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ashu Phetology Lab Centre</title>
<style>
body{font-family:Arial;margin:0;background:#f4f8fb}
header,footer{background:#0a6ebd;color:#fff;text-align:center;padding:20px}
section{background:#fff;margin:20px;padding:25px;border-radius:10px;box-shadow:0 0 10px rgba(0,0,0,.1)}
h2{color:#0a6ebd}
ul{columns:2;-webkit-columns:2;-moz-columns:2;line-height:1.8}
input,button{padding:8px;font-size:16px}
button{background:#0a6ebd;color:#fff;border:none;border-radius:5px}
</style>
</head>
<body>

<header>
<h1>🔬 Ashu Phetology Lab Centre</h1>
<p>Complete Diagnostic & Pathology Services</p>
</header>

<section>
<h2>🧪 All Blood & Pathology Tests Available</h2>
<ul>
<li>CBC</li>
<li>Hemoglobin (Hb)</li>
<li>ESR</li>
<li>PCV</li>
<li>RBC Count</li>
<li>WBC Count</li>
<li>Platelet Count</li>
<li>Peripheral Smear</li>
<li>Blood Group & Rh</li>
<li>Blood Sugar (Fasting)</li>
<li>Blood Sugar (PP)</li>
<li>Random Blood Sugar (RBS)</li>
<li>HbA1c</li>
<li>Lipid Profile</li>
<li>Liver Function Test (LFT)</li>
<li>Kidney Function Test (KFT)</li>
<li>Serum Creatinine</li>
<li>Blood Urea</li>
<li>Uric Acid</li>
<li>Electrolytes (Na, K, Cl)</li>
<li>Calcium</li>
<li>Phosphorus</li>
<li>Thyroid Profile (T3, T4, TSH)</li>
<li>Urine Routine</li>
<li>Urine Microscopy</li>
<li>Urine Culture</li>
<li>Stool Routine</li>
<li>Stool Occult Blood</li>
<li>Pregnancy Test (UPT)</li>
<li>PT / INR</li>
<li>APTT</li>
<li>Bleeding Time</li>
<li>Clotting Time</li>
<li>CRP</li>
<li>RA Factor</li>
<li>ASO</li>
<li>VDRL</li>
<li>HIV I & II</li>
<li>HBsAg</li>
<li>HCV</li>
<li>Dengue NS1</li>
<li>Dengue IgG / IgM</li>
<li>Malaria (MP)</li>
<li>Widal Test</li>
<li>Typhoid IgM</li>
<li>Vitamin D</li>
<li>Vitamin B12</li>
<li>Iron Profile</li>
<li>Ferritin</li>
<li>PSA</li>
<li>CEA</li>
<li>CA-125</li>
<li>CA 19-9</li>
<li>Prolactin</li>
<li>LH / FSH</li>
<li>Testosterone</li>
<li>Estrogen</li>
<li>Progesterone</li>
<li>All Routine & Special Tests Available</li>
</ul>
</section>

<section>
<h2>💰 Health Packages (Flat 10% OFF)</h2>
<ul>
<li>Basic Health Package – ₹999</li>
<li>Diabetes Care Package – ₹1299</li>
<li>Full Body Checkup – ₹1999</li>
<li>Senior Citizen Package – ₹1499</li>
</ul>
<p style="color:green"><b>🎉 Flat 10% Discount on All Packages</b></p>
</section>

<section>
<h2>📅 Online Test Booking</h2>
<form onsubmit="sendWhatsApp();return false;">
<input id="name" placeholder="Patient Name" required><br><br>
<input id="phone" placeholder="Phone Number" required><br><br>
<input id="test" placeholder="Test / Package Name" required><br><br>
<input type="date" id="date" required><br><br>
<button>Book Test & WhatsApp</button>
</form>
</section>

<section>
<h2>🤖 Smart AI Lab Assistant</h2>
<div id="chat" style="height:150px;overflow:auto;background:#f9f9f9;padding:10px"></div><br>
<input id="userInput" placeholder="Ask about any test, package, price..." style="width:70%">
<button onclick="aiReply()">Send</button>
</section>

<section>
<h2>📞 Contact Details</h2>
<p><b>Phone:</b> 9045478330</p>
<p>Main Market, Village Ramgarh, Chandigarh Road, Ludhiana, Punjab</p>
<p><b>Head Office:</b> Bharat Clinical Lab</p>
<a href="https://wa.me/919045478330">💬 WhatsApp Chat</a>
</section>

<footer>
© 2026 Ashu Phetology Lab Centre
</footer>

<script>
function aiReply(){
let q=document.getElementById('userInput').value.toLowerCase();
let c=document.getElementById('chat');
let r='Please use booking form or WhatsApp for details.';
if(q.includes('cbc')) r='CBC test available.';
if(q.includes('thyroid')) r='Thyroid profile test available.';
if(q.includes('vitamin')) r='Vitamin D & B12 tests available.';
if(q.includes('package')) r='Health packages available with 10% OFF.';
if(q.includes('book')) r='Please fill the booking form above.';
c.innerHTML+=`<p><b>You:</b> ${q}</p><p><b>AI:</b> ${r}</p>`;
}
function sendWhatsApp(){
let m=`New Booking%0AName:${name.value}%0APhone:${phone.value}%0ATest:${test.value}%0ADate:${date.value}`;
window.open('https://wa.me/919045478330?text='+m);
}
</script>

</body>
</html>
