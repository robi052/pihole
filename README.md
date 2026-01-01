# Pi-hole Custom Blacklist (Croatia & Balkans)

[English](#english) | [Hrvatski](#hrvatski)

---

<a name="english"></a>
## 🇬🇧 English
A specialized Pi-hole blocklist focusing on regional threats and clutter. This list is based on the [bind9-rpz](https://github.com/robi052/bind9-rpz) logic but formatted for Pi-hole.

### 🚀 How to use
1. Open your **Pi-hole Admin Console**.
2. Navigate to **Adlists**.
3. Paste the following URL:
   `https://raw.githubusercontent.com/robi052/pihole/master/hosts`
4. Click **Add**.
5. Update your gravity: `Tools` -> `Update Gravity` (or run `pihole -g` in terminal).

### 🎯 What's inside?
- **Regional Ads:** Specialized filters for Croatian and Balkan news portals.
- **Malware & Scams:** Protection against local fraudulent webshops.
- **Privacy:** Clean of tracking domains, excluding Google Analytics/YouTube History (see whitelist notes).

---

<a name="hrvatski"></a>
## 🇭🇷 Hrvatski
Specijalizirana Pi-hole lista za blokiranje regionalnih oglasa i prijetnji. Ova lista se temelji na [bind9-rpz](https://github.com/robi052/bind9-rpz) logici, ali je prilagođena Pi-hole formatu.

### 🚀 Kako koristiti
1. Otvorite **Pi-hole Admin Console**.
2. Idite na **Adlists**.
3. Unesite sljedeći URL:
   `https://raw.githubusercontent.com/robi052/pihole/master/hosts`
4. Kliknite **Add**.
5. Ažurirajte bazu: `Tools` -> `Update Gravity` (ili pokrenite `pihole -g` u terminalu).

### 🎯 Što je uključeno?
- **Regionalni oglasi:** Filteri za hrvatske i balkanske portale.
- **Malware i prevare:** Zaštita od lokalnih lažnih web trgovina.
- **Privatnost:** Blokiranje tracking domena. 
- **Napomena:** Google Analytics i YouTube History **nisu** blokirani radi stabilnosti servisa.

---

**Last update:** 01/01/2026  
**Issues:** [Report here](https://github.com/robi052/pihole/issues)
