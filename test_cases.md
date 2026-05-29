# Test Cases – SauceDemo Login

| TC ID | Test Case | Kroky | Expected Result | Actual Result | Status (PASS/FAIL) |
|-------|-----------|-------|-----------------|---------------|-------------------|
| TC_01 | Prihlásenie s platnými údajmi | 1. Otvor saucedemo.com<br>2. Zadaj `standard_user`<br>3. Zadaj `secret_sauce`<br>4. Klikni Login | Presmerovanie na `/inventory.html` | | |
| TC_02 | Neplatné heslo | 1. Otvor saucedemo.com<br>2. Zadaj `standard_user`<br>3. Zadaj `badpassword`<br>4. Klikni Login | Chybová správa: "Epic sadface: Username and password do not match" | | |
| TC_03 | Prázdne meno | 1. Otvor saucedemo.com<br>2. Nechaj username prázdne<br>3. Zadaj `secret_sauce`<br>4. Klikni Login | Chybová správa: "Epic sadface: Username is required" | | |
| TC_04 | Prázdne heslo | 1. Otvor saucedemo.com<br>2. Zadaj `standard_user`<br>3. Nechaj password prázdne<br>4. Klikni Login | Chybová správa: "Epic sadface: Password is required" | | |
| TC_05 | Prázdne obe polia | 1. Otvor saucedemo.com<br>2. Nechaj obe prázdne<br>3. Klikni Login | Chybová správa: "Epic sadface: Username is required" | | |
