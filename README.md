# Creadit-Cards
Vishnu Banking - Banking Made Simple
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>All Banks Credit Card Sales</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {margin:0;font-family:sans-serif;background:#f6f6f9;color:#222;}
        header {background:#01579b;color:#fff;padding:20px 0;text-align:center;}
        .nav {display:flex;justify-content:center;gap:20px;margin-top:10px;}
        .nav a {color:#fff;text-decoration:none;font-weight:bold;}
        .hero {background:#0288d1;color:#fff;padding:40px 10px;text-align:center;}
        .hero h1 {font-size:2.5em;margin-bottom:12px;}
        .cta-btn {background:#fff;color:#0070b2;padding:12px 25px;border-radius:25px;border:none;font-weight:600;cursor:pointer;font-size:1em;}
        .cta-btn:hover {background:#01579b;color:#fff;}
        .cards-container {display:grid;grid-template-columns:repeat(auto-fit,minmax(320px,1fr));gap:20px;padding:40px 2vw;}
        .card {background:#fff;border-radius:12px;box-shadow:0 2px 8px #0001;padding:24px;transition:.3s;}
        .card:hover {transform:translateY(-3px);box-shadow:0 6px 16px #0002;}
        .bank-name {font-weight:bold;margin-bottom:7px;}
        .card-title {font-size:1.3em;color:#01579b;margin-bottom:8px;}
        .features {font-size:.97em;margin-bottom:12px;}
        .apply-btn {background:#0288d1;color:#fff;padding:8px 16px; border:none; border-radius:20px;cursor:pointer;}
        .apply-btn:hover {background:#01579b;}
        .contact-section {background:#fff;padding:34px 2vw 36px 2vw;text-align:center;}
        .contact-section h2 {margin-bottom:14px;color:#0070b2;}
        .footer {text-align:center;background:#222;color:#fff;padding:24px 5px;margin-top:30px;font-size:15px;}
        form {display:inline-block;text-align:left;max-width:340px;width:100%;}
        label {margin-top:13px;display:block;}
        input,textarea {width:100%;padding:9px;margin-top:2px;margin-bottom:9px;border:1px solid #bbb;border-radius:5px;}
        button[type="submit"]{background:#0288d1;color:#fff;padding:9px 20px;border:none;border-radius:5px;font-weight:600;cursor:pointer;}
        button[type="submit"]:hover {background:#01579b;}
        @media (max-width:690px) {
            .hero h1 {font-size:1.4em;}
            .cards-container {grid-template-columns:1fr;}
        }
    </style>
</head>
<body>
    <header>
        <h1>All Banks Credit Card Sales</h1>
        <div class="nav">
            <a href="#cards">Credit Cards</a>
            <a href="#contact">Apply</a>
            <a href="#about">About Us</a>
        </div>
    </header>
    <section class="hero">
        <h1>Find & Apply for the Best Bank Credit Card</h1>
        <p>Compare features, rewards, and offers from top banks. Apply online & get expert help instantly!</p>
        <a href="#cards"><button class="cta-btn">View All Credit Cards</button></a>
    </section>
    <section id="cards" class="cards-container">
        <div class="card">
            <div class="bank-name">HDFC Bank</div>
            <div class="card-title">HDFC Regalia Credit Card</div>
            <div class="features">
                - 6 Reward Points per ₹150 spent<br>
                - Airport lounge access<br>
                - Zero lost card liability
            </div>
            <a href="#contact"><button class="apply-btn">Apply Now</button></a>
        </div>
        <div class="card">
            <div class="bank-name">SBI Card</div>
            <div class="card-title">SBI Card ELITE</div>
            <div class="features">
                - Free movie tickets<br>
                - 2x rewards on international spends<br>
                - Welcome gift vouchers
            </div>
            <a href="#contact"><button class="apply-btn">Apply Now</button></a>
        </div>
        <div class="card">
            <div class="bank-name">ICICI Bank</div>
            <div class="card-title">ICICI Coral Credit Card</div>
            <div class="features">
                - Buy 1 Get 1 free movie tickets<br>
                - Points on every spend<br>
                - Dining discounts
            </div>
            <a href="#contact"><button class="apply-btn">Apply Now</button></a>
        </div>
        <div class="card">
            <div class="bank-name">Axis Bank</div>
            <div class="card-title">Axis Magnus Credit Card</div>
            <div class="features">
                - 12 airport lounge visits<br>
                - 25,000 milestone rewards<br>
                - Travel & dining benefits
            </div>
            <a href="#contact"><button class="apply-btn">Apply Now</button></a>
        </div>
        <div class="card">
            <div class="bank-name">Kotak Mahindra Bank</div>
            <div class="card-title">Kotak Royale Signature Card</div>
            <div class="features">
                - 4x reward points<br>
                - Complimentary lounge access<br>
                - Fuel surcharge waiver
            </div>
            <a href="#contact"><button class="apply-btn">Apply Now</button></a>
        </div>
        <div class="card">
            <div class="bank-name">American Express</div>
            <div class="card-title">Amex Platinum Travel Card</div>
            <div class="features">
                - 10,000 bonus points<br>
                - Free airport lounge access<br>
                - Premium travel vouchers
            </div>
            <a href="#contact"><button class="apply-btn">Apply Now</button></a>
        </div>
    </section>
    <section id="contact" class="contact-section">
        <h2>Apply or Contact for Credit Card Assistance</h2>
        <form>
            <label>Full Name</label>
            <input type="text" required>
            <label>Email</label>
            <input type="email" required>
            <label>Phone</label>
            <input type="text" required>
            <label>Preferred Bank / Card</label>
            <input type="text" placeholder="(Optional)">
            <label>Your Message</label>
            <textarea rows="3"></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>
    <div class="footer">
        &copy; 2025 All Banks Credit Card Sales | All Rights Reserved | For information only - Offers subject to terms.
    </div>
</body>
</html>
