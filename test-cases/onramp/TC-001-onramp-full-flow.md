ID		Title	Preconditions	Steps	Expected result
TC-01	1	Open Onramp screen	App installed	"1. Open the app 
2. Tap Buy button"	Onramp screen opens correctly without errors
	2	Select currency	Onramp screen opened	"1. Tap on currency selector 
2. Choose currency"	Selected currency is displayed and saved
	3	Enter valid amount	Currency selected	1. Enter amount within allowed range (0<n<2500)	Amount accepted, Continue button activated
	4	Select amount	Buy screen opened	1. Tap  button with amount	Amount accepted, Continue button activated
	5	Enter amount below minimum	Buy screen opened	1. Enter amount less than minimum (0.00)	The Continue button is not available
	6	Enter amount above maximum	Buy screen opened	1. Enter amount more than maximum	Error message displayed
	7	Continue to payment	Valid amount entered	1. Tap Continue	User redirected to Select platform page
	8	Select the platform	On Select plaform  page	1. Select Wise platform 2. Slide the Confirm button	Send or select payment
	9	Select Send payment 	On the page of selection the way 	1. Tap Send payment button	Wise is opened
	10	Send payment on Wise	Wise opened	1. Send Payment 2. Back to the App	Send or select payment page is opened
	11	Select Send payment 	On the page of selection the way 	1. Tap Select Payment	modal window  of selection payment
	12	Select payment	on the modal window	1. Tap the user's Payment	Payment is ready
					
TC-01	1	Open Onramp screen	App installed	"1. Open the app 
2. Tap Buy button"	Onramp screen opens correctly without errors
	2	Select currency	Onramp screen opened	"1. Tap on currency selector 
2. Choose currency"	Selected currency is displayed and saved
	3	Enter valid amount	Currency selected	1. Enter amount within allowed range (0<n<2500)	Amount accepted, Continue button activated
	4	Select amount	Buy screen opened	1. Tap  button with amount	Amount accepted, Continue button activated
	5	Enter amount below minimum	Buy screen opened	1. Enter amount less than minimum (0.00)	The Continue button is not available
	6	Enter amount above maximum	Buy screen opened	1. Enter amount more than maximum	Error message displayed
	7	Payment canceled	Valid amount entered	1. Cancel payment	App shows 'Canceled' status
					
	1	Open Onramp screen	App installed	"1. Open the app 
2. Tap Buy button"	Onramp screen opens correctly without errors
	2	Select currency	Onramp screen opened	"1. Tap on currency selector 
2. Choose currency"	Selected currency is displayed and saved
	3	Enter valid amount	Currency selected	1. Enter amount within allowed range (0<n<2500)	Amount accepted, Continue button activated
	4	Select amount	Buy screen opened	1. Tap  button with amount	Amount accepted, Continue button activated
	5	Enter amount below minimum	Buy screen opened	1. Enter amount less than minimum (0.00)	The Continue button is not available
	6	Enter amount above maximum	Buy screen opened	1. Enter amount more than maximum	Error message displayed
	7	Continue to payment	Valid amount entered	1. Tap Continue	User redirected to Select platform page
	8	Select the platform	On Select plaform  page	1. Select Wise platform 2. Slide the Confirm button	Send or select payment
	9	Select Send payment 	On the page of selection the way 	1. Tap Send payment button	There are no quotes message,  User redirected to Select platform page
	10	Payment canceled	Valid amount entered	1. Cancel payment	App shows 'Canceled' status
<img width="1833" height="821" alt="image" src="https://github.com/user-attachments/assets/c4a203bd-e3e6-48dc-898d-98e12ec66a16" />

