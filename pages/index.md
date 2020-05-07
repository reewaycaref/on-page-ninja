---
layout: home
title: OnPage Ninja
permalink: /
section: home
intro_paragraph: >-
  CORA is an Expert SEO Diagnostics tool that measures up to 2040 ranking
  factors and identifies the strongest ones and tells you exactly how much of
  each one your page needs! The only SEO tool on the market that adapts to
  Google updates.


  <div id="paypal-button-container"></div>

  <script src="https://www.paypal.com/sdk/js?client-id=sb&currency=USD" data-sdk-integration-source="button-factory"></script>

  <script>
    paypal.Buttons({
        style: {
            shape: 'pill',
            color: 'gold',
            layout: 'vertical',
            label: 'paypal',
            
        },
        createOrder: function(data, actions) {
            return actions.order.create({
                purchase_units: [{
                    amount: {
                        value: '24.99'
                    }
                }]
            });
        },
        onApprove: function(data, actions) {
            return actions.order.capture().then(function(details) {
                alert('Transaction completed by ' + details.payer.name.given_name + '!');
            });
        }
    }).render('#paypal-button-container');
  </script>
---
