<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Plans</title>
    <link rel="stylesheet" href="styles.css">
  <script src="https://js.chargebee.com/v2/chargebee.js" data-cb-site="chargebee-assessment4-test" ></script>
</head>
<body>
    <div class="pricing-container">
        <div class="pricing-card">
            <h2 class="plan-name">Sprout Plan</h2>
            <p class="price">$20</p>
            <ul class="features">
                <li>10 GB Storage</li>
                <li>Basic Support</li>
                <li>1 Website</li>
            </ul>
         <a href="javascript:void(0)" data-cb-type="checkout" data-cb-item-0="Go-Plan-USD-Monthly" >subscribe</a>
        </div>

        <div class="pricing-card featured">
            <h2 class="plan-name">Garden Plan</h2>
            <p class="price">$40</p>
            <ul class="features">
                <li>50 GB Storage</li>
                <li>Priority Support</li>
                <li>5 Websites</li>
            </ul>
            <a href="javascript:void(0)" data-cb-type="checkout" data-cb-plan-id="garden" data-cb-plan-quantity="1" >
            <button class="cta-button">Sign Up</button>
            </a>
        </div>

        <div class="pricing-card">
            <h2 class="plan-name">Forest Plan</h2>
            <p class="price">$60</p>
            <ul class="features">
                <li>Unlimited Storage</li>
                <li>24/7 Support</li>
                <li>Unlimited Websites</li>
            </ul>
            <a href="javascript:void(0)" data-cb-type="checkout" data-cb-plan-id="forest" >
            <button class="cta-button">Sign Up</button>
            </a>
        </div>
    </div>
</body>
</html>
