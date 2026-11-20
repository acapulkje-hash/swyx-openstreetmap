SwyxIt! 15.01 Leaflet Address Search demo

1. Upload index.html to an HTTPS-enabled static hosting service at a stable URL.
2. Confirm the URL loads in a regular browser, and address searches work.
3. Edit swyx-webextension.json: replace https://YOUR-HOST.example/swyx-maps/ with the real URL.
4. Create a Web Extension in Swyx Control Center and assign it to your user.
5. Add the extension to SwyxIt! homescreen or navigation.

Dependencies: Leaflet 1.9.4 from unpkg.com; OpenStreetMap tile server; public Nominatim search service.
This is a low-volume demonstration, not a production geocoding service. Public Nominatim requires an identifiable application, a maximum of 1 request per second, attribution, and compliance with its usage policy. A generic static site may not provide a sufficiently identifiable Referer; use a recognizable HTTPS hostname. No autocomplete or bulk geocoding. Check CSP and network policies. Do not send sensitive customer addresses to public services without approval.
For production, use an approved geocoding provider or your own Nominatim instance and an approved tile provider.
