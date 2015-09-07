# annuity
Calculation of annuity payments

## Getting started

1. Include javascript's code

	```html
	<script src="/path/to/annuity.js"></script>
	```
2. Usage the script

	```javascript
	var obAnnuity = new annuity(credit_sum, month, rate, rate_compare);
	console.log(obAnnuity->GetCredit());
	console.log(obAnnuity->GetCreditCompare());
	console.log(obAnnuity->GetCreditDevide());
	```

##Usage

| Name           | Example      | Description                                                                                                                        |
|----------------|--------------|------------------------------------------------------------------------------------------------------------------------------------|
| credit_sum     | 2300000          | integer - Credit amount                                                                                      |
| month          | 120    | integer - Period of credit                                                                    |
| rate           | 12.5    | float - rate of credit                                                                    |
| rate_compare   | 11.5        | float - rate of credit for compare                                                       |
