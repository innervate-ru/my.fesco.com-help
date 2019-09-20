---
date: "2019-03-21"
title: "USD invoice - RUB payment"
tags: ["api", "метод"]
Description: ""
type: help_doc
layout: help_doc
weight: 2
---

#### Instruction for closing foreign currency invoices with payments in rubles 

If the invoice was issued in foreign currency, and you made payments in rubles:

1.	Unbound invoices are displayed in the left part of the window. Select one of the invoices and tick the box next to it. <br/>
The currency must be rubles (RUB)

{{< img name="images/1*" class="img-fluid" style="width:90%">}} <br/>

* payment number – number of the payment order
* contract reference number – number used for payments
* payment date – date of carrying out banking operation
* payment amount – total amount of the payment 
* unbound balance – amount to be paid
* payment currency – currency used to make the payment
<br/>
<br/>

2.	In the bottom of the window you can see the details of the payment you selected:

{{< img name="images/4344*" class="img-fluid" style="width:80%">}} <br/>

* Payment details – the information indicated for transferring the payments
* Payment amount – total amount of the payment
* Paid – the amount paid on the invoice
* Unbound balance – amount to be paid 

3.	In the right part of the window select the unpaid invoice:

{{< img name="images/5*" class="img-fluid" style="width:80%">}} <br/>

Please note that: 

* Contract reference number must correspond with the reference number of the contract for contact reference number of unbound payment.
* Currency of the invoice you selected (USD, EUR, CNY, KZT, etc.) must be different from the currency of the payment. 

4.	Paying off foreign currency invoices with ruble payments is made according to the Central Bank rate on the date of transferring the payment to the bank (is the date of unbound payment).

5.	To cover the invoice press «<span style="color:orange">**“BIND”**</span>» .

6.	“Confirmation of binding the invoice to the payment” window will be opened.

{{< img name="images/4*" class="img-fluid" style="width:90%">}} 

* Information on the closing payment will be displayed in the first column;
* Information on the invoice you are binding will be displayed in the third column;
* Contract reference number will be displayed in the fourth column.

<br/>
7. If all the conditions comply, press «<span style="color:orange">**“BIND”**</span> <br/>
If you want to cancel the operation, press «<span style="color:blue">**CANCEL **</span>» .

8.	Payment bound to the invoice will be displayed in currency of the invoice as well as in currency of the payment.

{{< img name="images/6*" class="img-fluid" style="width:80%">}} 
<br/>

9.	Paid invoices will be displayed in “Bound payments”.

{{< img name="images/52*" class="img-fluid" style="width:60%">}} 

{{<isHelpful>}}

{{<seeAlso>}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/rouble-rouble/" text="Closing ruble invoices with ruble payments">}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/usd-usd/" text="Closing foreign currency invoices with foreign currency payments">}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/sample_letter/" text="Examples of letters">}}
{{</seeAlso>}}

