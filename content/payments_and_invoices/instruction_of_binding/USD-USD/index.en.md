---
date: "2019-03-21"
title: "USD invoice - USD payment"
tags: ["api", "метод"]
Description: ""
type: help_doc
layout: help_doc
weight: 4
---


#### Instructions for paying off foreign currency invoices with foreign currency payments.

If the invoice was issued in foreign currency (not RUB), and the payment was made in the same foreign currency:

1.	Unbound invoices are displayed in the left part of the window. Select one of the invoices and tick the box next to it. <br/>
Currency of the payment must be not RUB (USD, EUR, CNY, KZT or other).

{{< img name="images/7*" class="img-fluid" style="width:70%">}} <br/>

* payment number – number of the payment order
* contract reference number – number used for payments
* payment date – date of carrying out banking operation
* payment amount – total amount of the payment 
* unbound balance – amount to be paid
* payment currency – currency used to make the payment
<br/>
<br/>

2.	In the bottom of the window you can see the details of the payment you selected:

{{< img name="images/8*" class="img-fluid" style="width:45%">}} <br/>

* Payment details – the information indicated for transferring the payments
* Payment amount – total amount of the payment
* Paid – the amount paid on the invoice
* Unbound balance – amount to be paid 

3.	In the right part of the window select the unpaid invoice:

{{< img name="images/5*" class="img-fluid" style="width:80%">}} <br/>

Please note that: 

* Contract reference number must correspond with the reference number of the contract for contact reference number of unbound payment.
* Currency of the invoice you selected must be the same as currency of the payment.

4.	For paying off the invoice, you need to proceed with «<span style="color:orange">**BIND**</span>» .

5.	“Confirmation of binding the invoice to the payment” window will be opened.

{{< img name="images/4*" class="img-fluid" style="width:90%">}} 

* Information on the closing payment will be displayed in the first column;
* Information on the invoice you are binding will be displayed in the third column;
* Contract reference number will be displayed in the fourth column.

<br/>
6.	If all the conditions comply, press «<span style="color:orange">**BIND**</span>» <br/>
If you want to cancel the operation, press «<span style="color:blue">**CANCEL**</span>» .

7.	The invoices will be bound to the payments.

{{< img name="images/9*" class="img-fluid" style="width:70%">}} 

8.	If the invoice wasn’t fully covered, unbound balance will be displayed.

{{< img name="images/10*" class="img-fluid" style="width:70%">}} 

<br/>
9.	Bound payments will be displayed in “Bound payments” menu. 

{{< img name="images/52*" class="img-fluid" style="width:60%">}} 

{{<isHelpful>}}

{{<seeAlso>}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/rouble-rouble/" text="Closing ruble invoices with ruble payments">}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/usd-rouble/" text="Closing foreign currency invoices with ruble payments">}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/sample_letter/" text="Examples of letters">}}
    {{<seeAlsoItem link="/payments_and_invoices/closed_payment_orders/" text="Review information on paid invoices">}}
{{</seeAlso>}}



