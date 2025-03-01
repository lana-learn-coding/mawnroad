---
title: "Actual Thank You Pixel"
date: "2024-09-04"
categories:
    - "Landing"
    - "Conversions"
tags:
    - "Real"
    - "Conversions"
    - "Ads"
description: "The thank you page after buying the product with pixel lib and configurable ?rate"
---

<script src="https://sdk.moneyoyo.com/v1/pxl.js"></script>

# Thank You!

**Thank You for Your Order!**

Hi [Customer's Name],

Thank you for shopping with **[Your Company Name]**! Your order **[#Order Number]** placed on **[Order Date]** is being
processed and will be shipped soon.

You'll receive a confirmation email with tracking info once your order is on its way.

If you have any questions, feel free to reach out to us at [Customer Service Email].

Thanks again for choosing us!

Best,  
**ChatGPT**


<script>
    document.addEventListener('DOMContentLoaded', () => {
        const rate = new URLSearchParams(window.location.search).get('rate');
        if (rate) {
            if (Math.random() > Number(rate)) {
                return;
            }
        }
        window.mnyypxl();
    })
</script>
