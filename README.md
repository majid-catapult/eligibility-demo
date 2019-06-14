# eligibility-demo

1.  npm install
2.  node app.js
3. go to http://localhost:3000/eligibility-demo.html
4.  Paste %WH9101000260BCBSMASS_001^FRANKLIN/BENJAMIN^DB17011212 into the first input box or put cursor in this input and scan a valid barcode
5.  Once the data is parsed and all the text fields below have valid data click on Check Eligibility button
6.  If member has coverage then you'll see a thumbs up.  Else you'll see a thumbs down.
7.  Assumptions: These are hard coded assumptions passed into the API.  We'll need to understand if these values will be known to us


            payer_id: "TXBLS",
            provider_last_name: "Jefferson",
            provider_first_name: "Thomas",
            provider_npi: "1234567893",
            cpt_code:"98960",

# Open questions

1. What if eligible.com service is down or scanner goes bad?  back up measures?
2. How to handle discrepency?  Patient says they do have service but API says no?
3. Can we get more confidence by testing using real patient data?
4. Do we have above inputs?  What should they be?  Is it always the same inputs?
5. What is CPT code?  is it always 98960?
What data do we need back from eligible.com service?  And where is that data going?
