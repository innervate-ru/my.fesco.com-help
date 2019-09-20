---
date: "2018-03-21"
title: "Rules for payment binding"
tags: ["api", "метод"]
Description: ""
type: help_doc
layout: help_doc
weight: 1
---

#### Automatic posting



Invoices are processed and closed automatically based on the information indicated by the client <b>in details of payment</b> such as: contract, account number (indicating amount is optional). </i>). 
If the amount isn’t indicated, the invoice will be fully covered. 
<br/>
<br/>
Examples of the information for indication in the details of payment for automatic processing are given below:  <br/>
<br/>
<b>Example 1 (several invoices):</b>: <br/>
Payment for logistics service, contract reference number № OME-15 /171 dated 15.06.2016, invoices FXXW005/180, 011/18, 012/180, 013/180, 019/18, 019/180, 022/180, 034/18, 035/171, 035/180, 045/180, 055/180, 056/180, including VAT (18%) 2232.94. <br/>
<br/>
<b>Example 2 (one invoice): </b>: <br/>
Payment for logistics service, contract reference number № OME-15 /171 dated 15.06.2015, invoice FXXW005/180, FXXW011/18, FXXW0358/18 (RUB 10 000), FXXW035/171. <br/>
<br/>

<div class="pixxett-alert pixxett-alert-icon alert11-light">
  <i class="fa fa-exclamation-circle"></i><b>Important notice</b> <br/> 
* If several invoices are indicated, they will be bound in the order a client indicated them in the details of payment. <br/>
* If the payment amount is not enough to pay off all the invoices indicated, the invoices will be paid in the order the client indicated, and the last invoice will be paid partially.
<br/>
* After full payment of the invoice a statement from the bank will be generated. The payment will be indicated in the statement in the morning of the next day. <br/>
</div>
<br/>
#### Making payments in My.FESCO 

Making payments in My.FESCO allows clients to proceed with the invoices that weren’t covered automatically: overpayments, balance and payments with unspecified details.
<br/>
<br/>
<b>The service is available for the following invoices:</b>

<p style="margin-left: 40px">I.	The invoice issued in rubles. / Payment made in rubles.</p>

<p style="margin-left: 40px">II.	The invoice issued in currencies other that rubles. / Payment made in rubles.</p>

<p style="margin-left: 40px">III.	The invoice issued in currencies other that rubles. / Payment made in billing currency.
<br/>


<b>Main features of the Service:</b>

1.	All the invoices are made for a particular contract.
2.	The invoice can be paid off only if the same contact is indicated in payment details and for billing.
3.	FIT LLC includes the following regional centers and branches:

    a.	<i>FIT central region</i> <br/>
            — FIT Moscow
            — FIT Saint-Petersburg
            — FIT Novosibirsk
            — FIT Novorossiisk
            — FIT Irkutsk
            — FIT Rostov
 
    b.	<i>FIT Far East</i> <br/>
            — FIT Vladivostok
            — FIT Petropavlovsk-Kamchatski
            — FIT Magadan
            — FIT Korsakov
            — FIT Sakhalin
            — FIT Holmsk
            — FIT Vostochnij

4.	Payments made for FIT Central region operating account can be used for closing invoices issued in branches of the central region. Payments made for FIT Far East operating account can be used for closing invoices issued in branches of the Far East (refer to i.3)

5.	Self-service mode doesn’t allow:

	a.	to close invoices with VO, ВОСТ/ prefixes.

	b.	to close invoice issued in one currency with payments in another currency (for example, invoice issued in dollars, payments in euro);

	c.	to close invoices with payments in rubles if the contract implies conversion according to the exchange rate relevant on the date different from the date of the payment.

<br/>
<b>Interaction with the Bank Group:</b>
<br/>

<div class="pixxett-alert pixxett-alert-icon alert11-light">
  <i class="fa fa-exclamation-circle"></i> 
Regarding bank statements’ delivery, settlement of disputes while paying off the invoicess, and in case of limited activity of the Service prescribed by this Regulations, please contact the Service center of the Bank Group at <b> FESCO Posting Bank Statement  <ercpostbank@fesco.com> </b> . 
<br/> 

Average time for processing the requests on the Bank Group e-mail is  <br/> <b>2-3 working days.</b> <br/>
</div>
<br/>
In <a href="/payments_and_invoices/instruction_of_binding/sample_letter" target="_blank">“Examples of letters” menu </a> there are examples of the letters that are required to be sent on the official letterhead of your company signed by authorized person and stamped with the organization seal at the Bank Group address in the following situations:

1.	Closing the invoice using advanced payment; <br/>
2.	Clarification of details of payment; <br/>
3.	Partial closing of the invoice. <br/>


Using the Service allows to save the Client’s time which previously was spent for making registers for closing the payments.
<br/>

 If indicating the invoices’ reference numbers in the field for payment details for automatical processing or the use of the Service in MY.FESCO seem to the Client impractical, there is an option of paying off the invoices on FIFO under an agreement.In this case, it is necessary to contact the CS service manager, sign an additional agreement to close invoices with FIFO payments and indicate only the contract information in the payment details. <br/>

{{<isHelpful>}}

{{<seeAlso>}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/rouble-rouble/" text="Closing ruble invoices with ruble payments">}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/usd-rouble/" text="Closing foreign currency invoices with ruble payments">}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/usd-usd/" text="Closing foreign currency invoices with foreign currency payments">}}
    {{<seeAlsoItem link="/payments_and_invoices/instruction_of_binding/sample_letter/" text="Examples of letters">}}
    {{<seeAlsoItem link="/payments_and_invoices/closed_payment_orders/" text="Review information on paid invoices">}}
{{</seeAlso>}}


