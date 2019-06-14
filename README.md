# eligibility-demo
npm install

node app.js

Paste %WH9101000260BCBSMASS_001^FRANKLIN/BENJAMIN^DB17011212 into the first input box or put cursor in this input and scan a valid barcode

Once the data is parsed and all the text fields below have valid data click on Check Eligibility button

If member has coverage then you'll see a thumbs up.  Else you'll see a thumbs down.

Assumptions: These are hard coded assumptions passed into the API.  We'll need to understand if these values will be known to us

            payer_id: "TXBLS",
            provider_last_name: "Jefferson",
            provider_first_name: "Thomas",
            provider_npi: "1234567893",
            //remove this code to see thumbs-down png
            cpt_code:"98960",
