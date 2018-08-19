
# ZAP Scanning Report




## Summary of Alerts

| Risk Level | Number of Alerts |
| --- | --- |
| High | 0 |
| Medium | 2 |
| Low | 5 |
| Informational | 0 |

## Alert Detail


  
  
  
### Session ID in URL Rewrite
##### Medium (High)
  
  
  
  
#### Description
<p>URL rewrite is used to track user session ID. The session ID may be disclosed via cross-site referer header. In addition, the session ID might be stored in browser history or server logs.</p>
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=DcpFgwMkdKGTyAyADpET](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=DcpFgwMkdKGTyAyADpET)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `DcpFgwMkdKGTyAyADpET`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_NfK&sid=MdCbywJqZdcnRSBfDk0T](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_NfK&sid=MdCbywJqZdcnRSBfDk0T)
  
  
  * Method: `POST`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `MdCbywJqZdcnRSBfDk0T`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=2BGpfYtiVrHfsXahDnHD](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=2BGpfYtiVrHfsXahDnHD)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `2BGpfYtiVrHfsXahDnHD`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=huxTim7B90oHAGTeDlVk](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=huxTim7B90oHAGTeDlVk)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `huxTim7B90oHAGTeDlVk`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=eV4jJ-UNiSfgcp70DkIy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=eV4jJ-UNiSfgcp70DkIy)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `eV4jJ-UNiSfgcp70DkIy`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=QKtwum7nbwnEBYfBDhxX](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=QKtwum7nbwnEBYfBDhxX)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `QKtwum7nbwnEBYfBDhxX`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=EnffXyich3PsIV98DiWH](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=EnffXyich3PsIV98DiWH)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `EnffXyich3PsIV98DiWH`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=gHbOioccS-l635n-DsDy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=gHbOioccS-l635n-DsDy)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `gHbOioccS-l635n-DsDy`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=tYFQtEjgF1Vf6fjTDmFS](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=tYFQtEjgF1Vf6fjTDmFS)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `tYFQtEjgF1Vf6fjTDmFS`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_)
  
  
  * Method: `POST`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `dVgZw4h3YvsURiDBDjD_`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=Kkmr-jUf5J6JLx8uDsBC](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=Kkmr-jUf5J6JLx8uDsBC)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `Kkmr-jUf5J6JLx8uDsBC`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=dVgZw4h3YvsURiDBDjD_](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=dVgZw4h3YvsURiDBDjD_)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `dVgZw4h3YvsURiDBDjD_`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=MPPRHwKobUGx_6VwDm0i](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=MPPRHwKobUGx_6VwDm0i)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `MPPRHwKobUGx_6VwDm0i`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=HsNrprkMlFi9BU08DiTA](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=HsNrprkMlFi9BU08DiTA)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `HsNrprkMlFi9BU08DiTA`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=KQ0vWaPnkyfB1srYDjoy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=KQ0vWaPnkyfB1srYDjoy)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `KQ0vWaPnkyfB1srYDjoy`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=Lgg2Hf2Nz0GEawQyDso-](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=Lgg2Hf2Nz0GEawQyDso-)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `Lgg2Hf2Nz0GEawQyDso-`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=GuK_a5U2jD9Z1CkRDkQd](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=GuK_a5U2jD9Z1CkRDkQd)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `GuK_a5U2jD9Z1CkRDkQd`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=eZyHNySjRU0NjD3pDjoc](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=eZyHNySjRU0NjD3pDjoc)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `eZyHNySjRU0NjD3pDjoc`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=YXHGgq-elERrkf4BDmjj](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=YXHGgq-elERrkf4BDmjj)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `YXHGgq-elERrkf4BDmjj`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=04siUL0khzXLjwKCDkZX](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=websocket&sid=04siUL0khzXLjwKCDkZX)
  
  
  * Method: `GET`
  
  
  * Parameter: `sid`
  
  
  * Evidence: `04siUL0khzXLjwKCDkZX`
  
  
  
  
Instances: 54
  
### Solution
<p>For secure content, put session ID in a cookie. To be even more secure consider using a combination of cookie and URL rewrite.</p>
  
### Reference
* http://seclists.org/lists/webappsec/2002/Oct-Dec/0111.html

  
#### CWE Id : 200
  
#### WASC Id : 13
  
#### Source ID : 3

  
  
  
### X-Frame-Options Header Not Set
##### Medium (Medium)
  
  
  
  
#### Description
<p>X-Frame-Options header is not included in the HTTP response to protect against 'ClickJacking' attacks.</p>
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_NfK&sid=MdCbywJqZdcnRSBfDk0T](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_NfK&sid=MdCbywJqZdcnRSBfDk0T)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-Frame-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-Frame-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-Frame-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-jva&sid=aDx26gzeWGqHtn7ADjoM](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-jva&sid=aDx26gzeWGqHtn7ADjoM)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-Frame-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_6ga&sid=eV4jJ-UNiSfgcp70DkIy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_6ga&sid=eV4jJ-UNiSfgcp70DkIy)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-Frame-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzq6G&sid=3PjhsMTKjjhvr61QDhfF](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzq6G&sid=3PjhsMTKjjhvr61QDhfF)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-Frame-Options`
  
  
  
  
Instances: 6
  
### Solution
<p>Most modern Web browsers support the X-Frame-Options HTTP header. Ensure it's set on all web pages returned by your site (if you expect the page to be framed only by pages on your server (e.g. it's part of a FRAMESET) then you'll want to use SAMEORIGIN, otherwise if you never expect the page to be framed, you should use DENY. ALLOW-FROM allows specific websites to frame the web page in supported web browsers).</p>
  
### Reference
* http://blogs.msdn.com/b/ieinternals/archive/2010/03/30/combating-clickjacking-with-x-frame-options.aspx

  
#### CWE Id : 16
  
#### WASC Id : 15
  
#### Source ID : 3

  
  
  
### Incomplete or No Cache-control and Pragma HTTP Header Set
##### Low (Medium)
  
  
  
  
#### Description
<p>The cache-control and pragma HTTP header have not been set properly or are missing allowing the browser and proxies to cache content.</p>
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_QD2](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_QD2)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/api/Challenges/?name=Score+Board](https://crimdrac-juice-shop.herokuapp.com/api/Challenges/?name=Score+Board)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/node_modules/flag-icon-css/flags/4x3/gb.svg](https://crimdrac-juice-shop.herokuapp.com/node_modules/flag-icon-css/flags/4x3/gb.svg)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  * Evidence: `public, max-age=0`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/rest/product/1/reviews](https://crimdrac-juice-shop.herokuapp.com/rest/product/1/reviews)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_kgl](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_kgl)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_N_Q](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_N_Q)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF12Zy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF12Zy)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/node_modules/flag-icon-css/flags/4x3/jp.svg](https://crimdrac-juice-shop.herokuapp.com/node_modules/flag-icon-css/flags/4x3/jp.svg)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  * Evidence: `public, max-age=0`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-L2c](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-L2c)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzqO1](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzqO1)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_qvy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_qvy)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/api/Challenges/](https://crimdrac-juice-shop.herokuapp.com/api/Challenges/)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/rest/product/24/reviews](https://crimdrac-juice-shop.herokuapp.com/rest/product/24/reviews)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/node_modules/flag-icon-css/flags/4x3/lv.svg](https://crimdrac-juice-shop.herokuapp.com/node_modules/flag-icon-css/flags/4x3/lv.svg)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  * Evidence: `public, max-age=0`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/api/Products/26?d=Sat%20Aug%2018%202018](https://crimdrac-juice-shop.herokuapp.com/api/Products/26?d=Sat%20Aug%2018%202018)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH)
  
  
  * Method: `POST`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_)
  
  
  * Method: `POST`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/rest/product/8/reviews](https://crimdrac-juice-shop.herokuapp.com/rest/product/8/reviews)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/node_modules/cookieconsent/build/cookieconsent.min.css](https://crimdrac-juice-shop.herokuapp.com/node_modules/cookieconsent/build/cookieconsent.min.css)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  * Evidence: `public, max-age=0`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_wGj](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_wGj)
  
  
  * Method: `GET`
  
  
  * Parameter: `Cache-Control`
  
  
  
  
Instances: 134
  
### Solution
<p>Whenever possible ensure the cache-control HTTP header is set with no-cache, no-store, must-revalidate; and that the pragma HTTP header is set with no-cache.</p>
  
### Reference
* https://www.owasp.org/index.php/Session_Management_Cheat_Sheet#Web_Content_Caching

  
#### CWE Id : 525
  
#### WASC Id : 13
  
#### Source ID : 3

  
  
  
### Cookie Without Secure Flag
##### Low (Medium)
  
  
  
  
#### Description
<p>A cookie has been set without the secure flag, which means that the cookie can be accessed via unencrypted connections.</p>
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0gJz](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0gJz)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-k9E](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-k9E)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH)
  
  
  * Method: `POST`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0Ouu](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0Ouu)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_wGj](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_wGj)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_6ga&sid=eV4jJ-UNiSfgcp70DkIy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_6ga&sid=eV4jJ-UNiSfgcp70DkIy)
  
  
  * Method: `POST`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzqO1](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzqO1)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_qvy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_qvy)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_)
  
  
  * Method: `POST`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF12Zy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF12Zy)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0IF7](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0IF7)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_kgl](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_kgl)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-ZLP](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-ZLP)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_QD2](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_QD2)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzsrp](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzsrp)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_N_Q](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_N_Q)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF018b](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF018b)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-jva&sid=aDx26gzeWGqHtn7ADjoM](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-jva&sid=aDx26gzeWGqHtn7ADjoM)
  
  
  * Method: `POST`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-ehx](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-ehx)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_YAu](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_YAu)
  
  
  * Method: `GET`
  
  
  * Parameter: `io`
  
  
  * Evidence: `Set-Cookie: io`
  
  
  
  
Instances: 54
  
### Solution
<p>Whenever a cookie contains sensitive information or is a session token, then it should always be passed using an encrypted channel. Ensure that the secure flag is set for cookies containing such sensitive information.</p>
  
### Reference
* http://www.owasp.org/index.php/Testing_for_cookies_attributes_(OWASP-SM-002)

  
#### CWE Id : 614
  
#### WASC Id : 13
  
#### Source ID : 3

  
  
  
### X-Content-Type-Options Header Missing
##### Low (Medium)
  
  
  
  
#### Description
<p>The Anti-MIME-Sniffing header X-Content-Type-Options was not set to 'nosniff'. This allows older versions of Internet Explorer and Chrome to perform MIME-sniffing on the response body, potentially causing the response body to be interpreted and displayed as a content type other than the declared content type. Current (early 2014) and legacy versions of Firefox will use the declared content type (if one is set), rather than performing MIME-sniffing.</p>
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_wGj](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_wGj)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_qvy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_qvy)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_kgl](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_kgl)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_N_Q](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_N_Q)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF12Zy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF12Zy)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_QD2](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_QD2)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-L2c](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-L2c)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0gJz](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0gJz)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0Ouu](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0Ouu)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzsrp](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzsrp)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_YAu](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_YAu)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-k9E](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-k9E)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0c94](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0c94)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_hH3](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_hH3)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-ehx](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-ehx)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-ZLP](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-ZLP)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF07Y7](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF07Y7)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF03t8](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF03t8)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0B1I](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLF0B1I)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-Content-Type-Options`
  
  
  
  
Instances: 55
  
### Solution
<p>Ensure that the application/web server sets the Content-Type header appropriately, and that it sets the X-Content-Type-Options header to 'nosniff' for all web pages.</p><p>If possible, ensure that the end user uses a standards-compliant and modern web browser that does not perform MIME-sniffing at all, or that can be directed by the web application/web server to not perform MIME-sniffing.</p>
  
### Other information
<p>This issue still applies to error type pages (401, 403, 500, etc) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.</p><p>At "High" threshold this scanner will not alert on client or server error responses.</p>
  
### Reference
* http://msdn.microsoft.com/en-us/library/ie/gg622941%28v=vs.85%29.aspx
* https://www.owasp.org/index.php/List_of_useful_HTTP_headers

  
#### CWE Id : 16
  
#### WASC Id : 15
  
#### Source ID : 3

  
  
  
### Web Browser XSS Protection Not Enabled
##### Low (Medium)
  
  
  
  
#### Description
<p>Web Browser XSS Protection is not enabled, or is disabled by the configuration of the 'X-XSS-Protection' HTTP response header on the web server</p>
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-jva&sid=aDx26gzeWGqHtn7ADjoM](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-jva&sid=aDx26gzeWGqHtn7ADjoM)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/](https://crimdrac-juice-shop.herokuapp.com/)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-Ivy&sid=EnffXyich3PsIV98DiWH)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_NfK&sid=MdCbywJqZdcnRSBfDk0T](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_NfK&sid=MdCbywJqZdcnRSBfDk0T)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE-VSI&sid=dVgZw4h3YvsURiDBDjD_)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_6ga&sid=eV4jJ-UNiSfgcp70DkIy](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLE_6ga&sid=eV4jJ-UNiSfgcp70DkIy)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzq6G&sid=3PjhsMTKjjhvr61QDhfF](https://crimdrac-juice-shop.herokuapp.com/socket.io/?EIO=3&transport=polling&t=MLEzq6G&sid=3PjhsMTKjjhvr61QDhfF)
  
  
  * Method: `POST`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/i18n/de.json](https://crimdrac-juice-shop.herokuapp.com/i18n/de.json)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/public/images/ribbons/forkme_right_%7B%7BgitHubRibbon%7D%7D.png](https://crimdrac-juice-shop.herokuapp.com/public/images/ribbons/forkme_right_%7B%7BgitHubRibbon%7D%7D.png)
  
  
  * Method: `GET`
  
  
  * Parameter: `X-XSS-Protection`
  
  
  
  
Instances: 9
  
### Solution
<p>Ensure that the web browser's XSS filter is enabled, by setting the X-XSS-Protection HTTP response header to '1'.</p>
  
### Other information
<p>The X-XSS-Protection HTTP response header allows the web server to enable or disable the web browser's XSS protection mechanism. The following values would attempt to enable it: </p><p>X-XSS-Protection: 1; mode=block</p><p>X-XSS-Protection: 1; report=http://www.example.com/xss</p><p>The following values would disable it:</p><p>X-XSS-Protection: 0</p><p>The X-XSS-Protection HTTP response header is currently supported on Internet Explorer, Chrome and Safari (WebKit).</p><p>Note that this alert is only raised if the response body could potentially contain an XSS payload (with a text-based content type, with a non-zero length).</p>
  
### Reference
* https://www.owasp.org/index.php/XSS_(Cross_Site_Scripting)_Prevention_Cheat_Sheet
* https://blog.veracode.com/2014/03/guidelines-for-setting-security-headers/

  
#### CWE Id : 933
  
#### WASC Id : 14
  
#### Source ID : 3

  
  
  
### Private IP Disclosure
##### Low (Medium)
  
  
  
  
#### Description
<p>A private IP (such as 10.x.x.x, 172.x.x.x, 192.168.x.x) or an Amazon EC2 private hostname (for example, ip-10-0-56-78) has been found in the HTTP response body. This information might be helpful for further attacks targeting internal systems.</p>
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/dist/juice-shop.min.js](https://crimdrac-juice-shop.herokuapp.com/dist/juice-shop.min.js)
  
  
  * Method: `GET`
  
  
  * Evidence: `192.168.99.100:3000`
  
  
  
  
* URL: [https://crimdrac-juice-shop.herokuapp.com/private/fontawesome-all.js](https://crimdrac-juice-shop.herokuapp.com/private/fontawesome-all.js)
  
  
  * Method: `GET`
  
  
  * Evidence: `10.6.2.8`
  
  
  
  
Instances: 2
  
### Solution
<p>Remove the private IP address from the HTTP response body.  For comments, use JSP/ASP/PHP comment instead of HTML/JavaScript comment which can be seen by client browsers.</p>
  
### Other information
<p>192.168.99.100:3000</p><p>192.168.99.100:3000</p><p></p>
  
### Reference
* https://tools.ietf.org/html/rfc1918

  
#### CWE Id : 200
  
#### WASC Id : 13
  
#### Source ID : 3
