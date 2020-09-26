
(Error: No "Access-Control-Allow-Origin")
- Type: API Error, 
- Reason: API distributor has no CORS configuration, 
- WHEN: occurs when getting API data from an endpoint,
- Fix: (visit crossorigin.me website) &amp; prefix url of cross origin to the API url. 
Ex: fetch('https:/prefix/https//:api') 
